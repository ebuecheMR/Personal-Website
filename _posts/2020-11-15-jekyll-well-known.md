---
layout: post
title:  "Adding .well-known directory to Jekyll sites"
date:   2020-11-15 15:00:00 +0700
categories: jekyll
---

Recently I have to reset my phone which led to the lost of some 2-factor authentication (2FA) accounts on the LastPass Authenticator app. One of thoese accounts belongs to Cloudflare. As a bonus, I did not save the backup/recovery codes! Now I'm completely locked out from my account without the 2FA. 

I did some search and found out that I need to contact Cloudflare Support directly to request them to disable the 2FA function on my account. 

There are 6 domains associated with my Cloudflare account. They have requested my to put a `txt` file on all of them under the directory called `.well-knwon/`. The final result should look like `puttapirat.com/.well-known/cf-2fa-verify.txt` and there should be a unique string inside the file. 

After trying ot add `.well-known` directory to the site, I realized that Jekyll does not recognize the directories starting with `.`. [This post](https://josh.st/2015/10/22/jekyll-well-known-and-dotfiles/), then, suggest that we add a line to the `_config.yml` file and Jekyll should process such direcory. 

In the `_config.yml`
```
include: [".well-known"]
```

and that's it! After a few git commits and pushes and an email to the support team, I've regained access to my Cloudflare account. :-)

## Lesson learned 
- Keep the recovery code! 
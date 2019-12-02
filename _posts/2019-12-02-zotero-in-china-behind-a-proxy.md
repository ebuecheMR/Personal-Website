---
layout: post
title:  "Zotero in China behind a proxy"
date:   2019-12-02 09:00:00 +0800
categories: general
---

I have been with Zotero for a while. My situation is special since I'm in China and Zotero does not seems to connect well via a proxy. 
I have found two solutions to fix this particupar problem. 

## Reconfigure system's proxy setting. 

### In the system (macOS)
Go to advance setting of the NetworkPreference and add `*.zotero.org` to the _by pass list_. 

![Advance setting](/assets/img/proxy/advance.png)

![Proxy setting](/assets/img/proxy/proxy-setting.png)

### In ShadowSocks' setting 
Go to **Preference** and add `*.zotero.org` to the _by pass list_. 

![ShadowSocks by pass list](/assets/img/proxy/ss-by-pass-list.png)

## Configure it from Zotero 

This is an advance setting in Zotero. 

> If you need to configure the Zotero proxy settings separately from the system settings, you can access the Config Editor from the Advanced pane of the Zotero preferences, apply the same settings that you would in [Firefox](http://kb.mozillazine.org/Network.proxy.type), and restart Zotero, but the default setting (network.proxy.type = 5, to use the system proxy settings) is recommended.

From [Zotero Wiki](https://www.zotero.org/support/kb/connection_error)

Happy Zoteroing!
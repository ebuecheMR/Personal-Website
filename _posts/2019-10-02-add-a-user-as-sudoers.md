---
layout: post
title:  "Add a user a sudoers"
date:   2019-10-02 09:44:58 +0800
categories: general
---

Edit the file `/etc/sudoers` and add the following line. Replace `username` with the username you want. 

```
# User privilege specification
username    ALL=(ALL:ALL) ALL
```

/Pargorn

--- 
Update on 20191014

We can make the access even more permissive by specifying 

```
username    ALL=(ALL:ALL) NOPASSWD:ALL
```

After this, it is likely that you will forget your password soon! ;-P

/Pargorn

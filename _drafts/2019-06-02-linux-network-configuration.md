---
layout: post
title:  "Formatting flash drives on mac using terminal"
date:   2019-05-31 12:00:00 +0800
categories: technical
---

I was having unsuccessful attempts to format a flash drive using the built-in "Disk Utility" app. I came across [this discussion](https://discussions.apple.com/thread/8132218) and it solves my problem. So here's note for myself and others are welcome to use the same as well. 

```bash
diskutil list
diskutil eraseDisk free EMPTY /dev/disk4
diskutil eraseDisk ExFAT USB64 /dev/disk4
```

It works! 

/Pargorn 
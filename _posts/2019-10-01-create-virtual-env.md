---
layout: post
title:  "Creating a Python environment with virtualenv"
date:   2019-10-01 16:34:58 +0800
categories: general
---

Testing out Python code requires a quick creation of virtual environments. There are two popular tools that I use to create virtual environments: Anaconda and Virtualenv. Anaconda mostly works out-of-the-box. Once you created a new environment with Anaconda, the battery (frequently used libraries are included, e.g. Numpy, Scipy). However, I like the more "clean" and empty environment so I know what are missing and what is required. This post is a compilation of commands to create a virtual environment with `virtualenv`. It is just a note, not a complete guide. It should work for both macOS and Linux. 

## Install virtualenv
```
python3 -m pip install --user virtualenv
```

## Creating a virtual environment
```
python3 -m venv env
```

Note: If you wish to use specific python version to create virtual environments. You install the specific verison and change from `python3` to `python3.x` and replace `x` with the version number you wish. 

/Pargorn 
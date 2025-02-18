---
layout: post
title: Useful Tools and Packages
date: 2025-02-17 15:00:00
description: A simple tool packages for coding and productivity
tags: code python
categories: tools
featured: true
---

A curated collection of useful tools and programming language packages for development, data analysis, and more.

---

### Environment & IDE


- [Anaconda](https://www.anaconda.com/download) 
- [VS code](https://code.visualstudio.com/)
- [Nodejs](https://nodejs.org/en)


### Packages 

#### Python 

- **remove packages**
    Remove a package and its unused dependencies.
    ```python
    pip install pip3-autoremove
    # remove "somepackage" plus its dependencies:
    pip-autoremove somepackage -y
    # to remove packages including their extra packages (recursive).
    pip-autoremove -y -e somepackage

    ``` 


### Git 

- **remove the large file in the history**
    ```
    git filter-branch --prune-empty -d /dev/shm/scratch  --index-filter "git rm --cached -f --ignore-unmatch geckodriver.log"   --tag-name-filter cat -- --all
    ```



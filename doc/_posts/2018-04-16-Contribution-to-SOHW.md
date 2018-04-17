---
layout: post

#event information
title:  "Guide to access the SOHW repo"
description: "To add resources.."
cover: "http://lumin8media.com/wp-content/uploads/2014/12/coding-screen-1280x500.jpg "
comments: true

#event organiser details
author: "Fahima Zulfath"
category: "Contribution to SOHW"

---

## Welcome!!

First of all thanks for taking time to contribute for SOHW. Before you start, have a look at [README.md](https://github.com/SOHW/sohw.github.io/blob/master/README.md) and [CONTRIBUTING.md](https://github.com/SOHW/sohw.github.io/blob/master/CONTRIBUTING.md) file to know about how SOHW works.

### Step 1: Add yourself as a contributor for our repository
* Navigate to `doc` ---> `assets` ---> `data` ---> `contributors.yml` in the [repository](https://github.com/SOHW/Blogs)
* Include yourself as a contributor as per the following format

~~~
 Author_number:
    name: your name
    twitter: your twitter handle
    description: about you (Ex: Contributor to Open Science, Bug reporter, designer, etc)
~~~

### Step 2: To add a category
* Navigate to `doc` ---> `assets` ---> `data` ---> `categories.yml`
* Check whether the category that you want to contribute is included under categories.yml
* If not, include the category that you wish to add.

### Step 3: Fork the Repository
* [Fork](https://help.github.com/articles/fork-a-repo/) this repository
* This makes your own version of this project in your github repo
* Make changes in your repo that is been forked from the main repo

![Forking](https://im3.ezgif.com/tmp/ezgif-3-1b97043a1f.gif)

### Step 4: To write a blog
* Navigate to `doc` ---> `_post` in your forked repository
* Click on `Create new file`
* Enter the file name as per the following format
> yyyy-mm-dd-name.md (name should not contain any space. Instead, add "-") e.g.2018-01-01-Hello-world.md

* Include the following format before you write a blog

~~~
---
layout: post

#event information
title:  "Title of your blog"
cover: "add image link" (Not want to add cover image then remove it)
date:   yyyy-mm-dd 

#event organiser details
author: "name"
category: "Category name" (e.g. Rust)

---

  your blog content here.....
~~~

* Write your blog. [Simple formatting syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/
) can help your blogs to look just awesome
* Click on `Commit new file`

### Step 5: Submit a Pull Request
* Make sure that your forked repository is updated till now as like in master branch
* Click on `Pull Request` ---> `New Pull request` 
* The changes list will be shown down. Check once whether you have included all the files.
* Click on ` Create Pull Request`

Submit a [pull request](https://help.github.com/articles/proposing-changes-to-a-project-with-pull-requests/). This opens a discussion around your project and lets the project lead know you are proposing changes. Be sure to add the relevant tests before making the pull request. Docs will be updated automatically when we merge to `master`, but you should also build the docs yourself and make sure they're readable.


Hope it's helpfull :) Want to see something else added or report a bug? [Open an issue](https://github.com/SOHW/sohw.github.io/issues/new). Happy contributing!! Happy Global Sprint!!

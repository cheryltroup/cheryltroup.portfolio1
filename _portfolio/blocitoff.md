---
layout: post
title: Blocitoff
thumbnail-path: "img/blocitoff.png"
short-description: Blocitoff is a self-destructing to-do list!

---

{:.center}
![]({{ site.baseurl }}/img/blocitoff.png)

{:.center}
<a href="https://cheryltroup-blocitoff.herokuapp.com/" class="button">Heroku </a>
<a href="https://github.com/cheryltroup/bloccoff/" class="button">Github <i class="fa fa-fw fa-github"></i></a>

{:.center}
## Overview

Blocitoff allows users to create self-destructing to-do lists. Items are automatically deleted after seven days. The hypothesis is that if the to-do items is not important enough to be completed after seven days, it doesn’t belong on your to-do list. 

{:.center}
## Features

* Users can have multiple do-items
* A user can mark to-do items as complete and have item deleted
* User can see how many days items remain before automated deleted 
* Items are automately deleted after seven days

{:.center}
## Technologies

**Languages, Libraries, and Frameworks:** Ruby on Rails, Bootstrap

**Databases:** SQLite (Test, Development), PostgreSQL (Production)

**Development Tools:** 
                                                     
* Devise for user authentication
* Sendgrid for email confirmation
* Heroku scheduler for rake automation

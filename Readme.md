# pydo  :clipboard:
[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)]() [![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://varundey.mit-license.org/) [![PyPI](https://img.shields.io/badge/python-2.7-blue.svg)]()

Your personal terminal based to-do manager built on python
***
## Index
- [Demo](#demo)
- [Installation](#installation)
- [How to](#how-to-pydo)
- [Motivation](#motivation)
- [Contribute](#contribute)
- [Issues](#issues)

---
## Demo

---
## Installation

 - **Clone it**
```sh
$ git clone https://github.com/varundey/pydo.git
$ cd ~/Downloads/pydo
```
 - **Make our file executable and add a path**
```sh
$ chmod +x pydo
$ export PATH=$PATH:/home/[Your user name]/Downloads/pydo
```
If you are not sure, you can find `Your user name` with 
```sh
$ whoami
```
---
## How to pydo?
- **Add a task** :memo:

Your task should contain a unique id for your task separated by a comma
```
$ pydo
1,Feed the bunny
Feed the bunny successfully added in your to-do list!
```
 -  **View your to-do list**  :page_facing_up:

To view all the items you have added to your list, add `--v` or `-view`
```sh
$ pydo --v
Your to-do list contains following tasks:
(1, 'Feed the bunny')
```
 -  **Mark an item as done**  :white_check_mark:

Pass the argument `--d` or `-done`
```sh
$ pydo -d
Enter id no of done item: 1
Feed the bunny successfully marked as done!
```
- **Throw the list** :put_litter_in_its_place:

Done with your to-do? Good. Now tear it up, roll it up real good, take aim and shoot it in the bin
```sh
$ pydo --t
```
---
## Motivation
Just a weekend hack trying to put my unorganised life in track! :smile:

---
## Contribute
Thought of an awesome feature? Awesome! Just fork it, code it, push it. :smiley:

---
## Issues :bug:
Found a bug? Let's squash them together [here](https://github.com/varundey/to-do/issues).

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)
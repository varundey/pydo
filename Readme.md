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
- [To-do](to-do)
- [Issues](#issues-bug)

---
## Demo
[![asciicast](https://asciinema.org/a/6i0cg99rbpsvpjo4x1ldrr1qm.png)](https://asciinema.org/a/6i0cg99rbpsvpjo4x1ldrr1qm)
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
>If you are not sure, you can find `Your user name` with:
```sh
$ whoami
```


- **Create a symbolic link**
```sh
$ cd ~/bin
$ ln -s /home/[Your user name]/Downloads/pydo/pydo
```
> Make sure you have `bin` folder in your `home` directory. If not create it with:
```sh
$ mkdir ~/bin
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
## To-do
Coz even pydos need to-do (**pun intended**)

- [x]Mark the to-do list done at once
- [ ] Make a pydo pip
- [ ] Make a `pydo man` page
- [x] Unit tests
- [ ] Multiple to-do lists

---
## Issues :bug:
Found a bug? Let's squash them together [here](https://github.com/varundey/to-do/issues).

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

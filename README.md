The Ultimate Guide Plugin for Sketch
=============

Just another Guide plugin for Sketch.

**Currently under development**

## Feature

* Add guide in both direction, vertical and horizontal.
* Remove all guides in pages or artboards.

## Installation

### via Sketch

Open **Sketch**, on menu **Plugin > Reveal Plugins Folder**.
Download the repo as ZIP and extract to above directory.

### via Git (using Command-line)

```
$ cd ~/Library/Application Support/com.bohemiancoding.sketch3/Plugins

$ git clone https://github.com/petehouston/sketch-guides Guides
```

## Usage

The default command bind

* **Control + Shift + G** : to lauch the guide adding input.
* **Control + Shift + R** : to remove all guides on current page or current artboard.

### Syntax for adding guides

The format syntax is:

```
{v, h}<Space>{digit}
```

where, **v** for vertical, **h** for horizontal direction;
and **{digit}** is a coordinate value.

For example,

* Add a vertical guide at 150px: `v 150`
* Add a horizontal guide at 50px: `h 50`


## Future Development

* Show/Hide guides as in Photoshop.

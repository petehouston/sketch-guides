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
* **Control + Shift + H** : to add a horizontal guide.
* **Control + Shift + V** : to add a vertical guide.
* **Control + Shift + R** : to remove all guides on current page or current artboard.

### Syntax for adding guides

When using **Commands** dialog, you need to input with a format:

```
{v, h}<Space>{digit}
```

where, **v** for vertical, **h** for horizontal direction;
and **{digit}** is a coordinate value.

For example,

* Add a vertical guide at 150px: `v 150`
* Add a horizontal guide at 50px: `h 50`

However, if you use **Add Horizontal** or **Add Vertical**, simply input a coordinate number.

## FAQs

> **I added a guide but why it does not display on screen?**

You need to show the ruler because guides are associated with ruler.
Via menu **View**, select **Show Ruler**, or simple key combination **Control + R**.

> **I added a guide and showed the ruler but it still doesn't display?**

In this case, it could be in different artboards or pages. Iterate through all pages and artboards to find out which one you added.

> **Can I change the guide color? I don't like current one.**

Sure, you can. Via menu **Sketch**, select **Preferences**, select tab **Canvas**, pick your guide color at **Color Guide** at the bottom of the dialog.


## Future Development

Feel free to suggest if you would like something to have.

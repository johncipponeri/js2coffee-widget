## Synopsis

An embeddable version of [js2coffee](https://js2coffee.github.io/js2coffee/). How many times have you come across handy javascript snippets only to have to go through the trouble of converting to coffeescript yourself for your own project, or vice versa, coffeescript to javascript? 

Well those times are over. This embeddable version of js2coffee allows you to write one code snippet in either javascript or coffeescript and display both versions on your web page! By simply writing either a javascript or coffeescript snippet, this widget will generate the other version of the snippet for you.

## Code Example

The js2coffee-widget is self-contained so to utilize it all you have to do is ...

```
<div class=".j2cw-js" style="height: 250px;">code goes here ;)</div>
```

By adding a div with either the `.j2cw-js` or `.j2cw-cs` and inserting your snippet between the tags you can allow this widget to do the rest! 

By specifying either js or cs as an extension of the class name you will specify whether the snippet is written in javascript or coffeescript respectively.

## Motivation

Now unlike ever before you can easily and concisely support both javascript and coffeescript snippets in your tutorials and articles without even trying! This was motivated by frequent frustrations caused by doing this conversion by hand multiple times a day.

![alt text](https://github.com/johncipponeri/js2coffee-widget/demo/screenshot.png "Screenshot")

## Installation

Simply add the following to your `<head>` tag.

```
<link rel="stylesheet" href="js2coffee-widget.css">
<script src="js2coffee-widget.js">
```

And start making snippets!

**Note**: js2coffee-widget requires jQuery.

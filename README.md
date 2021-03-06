# JS-Sequence

## About
This is a great, lightweight tool to draw flow diagrams locally, without any dependencies.

## Installation

* Pull this repository to a folder
* Bookmark `index.htm` in your browser
* Refer to the syntax at [the js sequence website](https://bramp.github.io/js-sequence-diagrams/)

Simple syntax is:
```
// title of your flow diagram
title: blah

// connect a to b with some text
a->b: text

// use dashed lines for the connector
a-->b: text

// use open arrow for the connector
a->>b: text

// use dashed, open arrow for the connector
a-->>b: text

// connect a to b with a linebreak in some text
a->b: text\n text2

// put a note, left of a
note left of a: note text

// pit a note, right of a
note right of a: note text

// put a note over a
Note over a: Note over a

// put a note over a and b
Note over a,b: Note over both a and b
```

## Features
* break up flow diagrams
* export each diagram to SVG
* save text to localstorage

![image](https://user-images.githubusercontent.com/564911/171313023-28630025-f342-4006-9de5-30984d164b3b.png)


If this was useful, you could [!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/shailens)

---
layout: default
title: Web Browser

parent: Technologies
nav_order: 1
---

# Web Browser

On top of browser API, only HTML, CSS and JavaScript without external libraries are used to make Qia mdx Reader.

Among many, worth mentioning is IFrame and Channel Messaging API are used to have a clear seperation of the application and mdx content document.


## Tools

* Visual Studio Code for writing code
* Webpack for transpiling source code into minimized release code
* Babel (@babel/preset-env) to support non-modern browsers like Safari on iOS

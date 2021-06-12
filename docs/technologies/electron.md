---
layout: default
title: Electron

parent: Technologies
nav_order: 3
---

# Electron

Electorn is used for making the launcher of Qia mdx Reader version 2.

On top of Electron, only HTML, CSS and JavaScript without more external libraries are used to make the launcher.

As many other Eletron applications, the page in Qia mdx Reader launcher is also made by web browser technologies. Among which the following several points are worth mentioning.

* The list numbers are made with my custom SVG icon font, therefore the digits are displayed as Chinese charactors (一二三四五六七八九〇 for 1234567890)
  * I built my own icon font to use with list-style-type
* The laucher is also a WebSocket client of Qia mdx Reader server, therefore, the list will get updated when the opened mdx file list gets changed from other sides (some files closed at another connected launcher or directly at the server side)

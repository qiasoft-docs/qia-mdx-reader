---
layout: default
title: Commands

parent: Version One
nav_order: 3
---

# Commands

The are in general two categories of commands: the ones led by special charactor and the ones not. The ones which are not led by special charactor are just keyword for doing a dictionary search and match.

There are following several special leading charactors:

* `!` is the application level command leading charactor
  * `!exit` exits the application
  * `!state` tells the application state including history stack
  * `!rest` resets the application state
* `@` is the history stack navigation command leading charator
  * `@` navigates to the current internal page from external page just like the "empty" Enter keyboard shortcut
  * `@-$positiveInteger`, `@$positiveInteger`, `@+$positiveInteger` navigate to a page by relative or absolute position
* `?` is the mdx content leading charactor
  * `?config` tells the content configuration
  * `?pino=$positiveInteger` sets the configuration of item (entry) number in a single page
  * `?autoplay` and `?noautoplay` sets the configuration of whether automatically autoplay sound after loaded
  * `?autotransition` and `?noautotransition` sets the configuration of whether automatically transites to next page after all sound played-out
  * `?reset` resets the internal cursor of reading next page 

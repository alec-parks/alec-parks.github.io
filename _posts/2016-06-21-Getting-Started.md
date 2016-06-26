---
title: "01 - Getting Started"
layout: post
date:   2016-06-21 16:40:57 -0500
categories: java tutorial kotlin roguelike
permalink: /01-GettingStarted
---

## IDE

For this, I prefer to use [IDEA][idea]. You can use Eclipse if that's your taste, but as of this writing, I've not used it and am unsure of the support.

## Library
This tutorial will be using the AsciiPanel library ([source][src] | [jar][jr]). I'm going to be using the JAR.

## Setup

Start IDEA and select a new Kotlin Project. The library may not show up under ``Use Library:``
If it doesn't, select create, and the ``Use library from plugin`` radio button.
Name your project (I named mine roglin) and chose your directory. IDEA will set up your initial folder structure.

#### Adding the AsciiPanel Library

Once AsciiPanel is downloaded, place it in a folder of your chosing inside your project structure (I chose /roglin/lib/).
From within the IDE, right click your folder, and chose ``Add as Library`` option under the context menu

Once your initial structure is set up, it should look like [this][gh-commit].

[idea]: https://www.jetbrains.com/idea
[src]: https://github.com/trystan/AsciiPanel
[jr]: https://github.com/downloads/trystan/AsciiPanel/asciipanel.jar
[gh-commit]: https://github.com/alec-parks/roglin/tree/d0b29ba500a52e206872c9810651fe55125ecef1

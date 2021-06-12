---
layout: post
title: "What is in my OS (Mac version)"
comments: true
description: "What is in my OS (Mac version)"
keywords: "app, utilities"
---

In this post, I will share with you what I think is the most important apps/tools a software engineer should have, in order to be productive.

### Vim
First and foremost important tool any programmer must have is code editor.
I have used variety of the most popular IDEs/editors, such as
[IntelliJ IDEA](https://www.jetbrains.com/idea/){:target="_blank"},
[Eclipse](https://www.eclipse.org/ide/){:target="_blank"},
[NetBeans](https://netbeans.apache.org/){:target="_blank"},
[Visual Studio Code](https://code.visualstudio.com/){:target="_blank"},
[Sublime Text](https://www.sublimetext.com/){:target="_blank"}, etc.
I have to say none of them come close to Vim in terms of programmatically editting code.
Vim is a programming language itself, meaning you can write your own (or use other's) scripts/plugins to customize behaviour to fit your needs.

Eventhough I've only been consistently using Vim (recently [NeoVim](https://neovim.io/){:target="_blank"}) since 2019, I don't think I will ever come back to any other IDEs, except for Xcode, or Android Studio when I have to build native mobile apps.

Here is the link to my [vimrc](https://github.com/namnd/dotfiles-macos/blob/master/nvim/init.vim) if anyone is interested in.

### Clipy
One of the most simple but very useful app I use all the time is [Clipy](https://clipy-app.com/){:target="_blank"}. 
It's a Clipboard extension app that supports keeping track the history of your clipboard. 
You can configure as many items as you want to keep in the history. I feel like this should be a built-in Mac OS utilities.

The only missing (and frankly quite crucial) feature of this app is the ability to fuzzy search any record in the history. 
If anyone knows such an app, please share with me.
Otherwise, I might write one myself if I can find some spare time.

### Yabai + skhd
I am tending to not using the mouse while writing code, and while doing so, quite often, I will have many different apps openning at the same time:
one window for code editor, one for the local web app, another one for database console, and maybe another web page that has the resource/reference that I am looking for my current implementation.
That does not even include other productivity apps, such as slack, mail, calendar, etc.

In Mac OS, you can use shortcut `⌘ (command)` + `tab` to switch between apps, you can also use some other shortcut like `⌘ (command)` + `m` to minimize current active app. However, it's not efficient enough for my workflow.

Luckly, [Yabai](https://github.com/koekeishiya/yabai){:target="_blank"} comes to rescuse. Combining Yabai with [skhd](https://github.com/koekeishiya/skhd){:target="_blank"} (created by the same person), I can have a smooth workflow without touching the mouse.

(TBC)

---
date: 2024-09-15
authors:
  - daveebbelaar
categories:
  - Tools
  - Quick Tips
description: A quick fix for macOS users
---

# Opening VS Code Workspace Files with Cursor on macOS

I recently switched to Cursor, a new AI-enhanced code editor that's been getting a lot of attention lately. While it's been a great experience so far, there was one small hiccup on macOS with `.code-workspace` files. Here's how I solved it.

<!-- more -->

## Why Cursor?

If you're a developer, you might have noticed Cursor IDE popping up everywhere. It's a fork of VS Code but with added AI capabilities like autocomplete, inline edits, and a composer. After five years with VS Code, I decided to give Cursor a try. The transition was seamless since Cursor is built on top of VS Code, so all my settings, themes, and extensions worked right out of the box.

## The macOS Workspace Issue

One issue I ran into was with opening `.code-workspace` files on macOS. By default, Cursor couldn't open these files directly, which was pretty annoying. Fortunately, there's a straightforward fix.

## How to Make Cursor the Default for Workspace Files

Here's how to make Cursor the default application for `.code-workspace` files:

<div class="annotate" markdown>
1. Locate a `.code-workspace` file in Finder.
2. Right-click on the file and select “Get Info” from the context menu.
3. In the “Get Info” window, look for the “Open with:” section.
4. Click on the selection field and choose "Other".
5. In the Finder selection window, change the setting "Enable" to "All Applications" instead of the default "Recommended Applications"(1)
6. You can now select Cursor from the list.
7. After making the selection, click "Change All..." to make Cursor the default for all your `.code-workspace` files.
</div>
 
 1. This is where you need to change the setting to "All Applications".
    ![Enable All Applications](images/CleanShot%202024-09-15%20at%2012.03.17@2x.png)

## My Cursor Workflow

If you want to learn more about how to use Cursor effectively, you can check out the video below.

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
  <iframe
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    src="https://www.youtube.com/embed/CqkZ-ybl3lg?si=BIs59_CN1k2hGeVI?rel=0"
    title="YouTube video player"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    referrerpolicy="strict-origin-when-cross-origin"
    allowfullscreen
  ></iframe>
  <a href="https://www.youtube.com/watch?v=CqkZ-ybl3lg" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; z-index: 1;" target="_blank" rel="noopener noreferrer"></a>
</div>

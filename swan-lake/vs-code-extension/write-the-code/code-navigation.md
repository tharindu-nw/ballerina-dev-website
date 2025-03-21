---
title: Code navigation
description: The Ballerina VS Code extension provides code navigation to simplify the developing process of your code. 
keywords: ballerina, vs code extension, code navigation
intro: The Ballerina VS Code extension provides support for code navigation.
---

The Ballerina VS Code extension provides support for [code navigation](https://code.visualstudio.com/docs/editor/editingevolved). The different kinds of supported navigations are described in the following sections.

## Go to definition

The [Go to definition](https://code.visualstudio.com/docs/editor/editingevolved#_go-to-definition) feature navigates you to the definition of a particular symbol. For example, when you invoke the `Go To Definition` option on a function call expression, it navigates you to the definition of the function.

To go to a symbol's definition, press `F12`. Hold `Ctrl` on Windows and Linux or `⌘` on Mac and hover over the symbol to see a preview of its declaration.

<img src="/learn/images/vs-code-extension/edit-the-code/code-navigation/go-to-definition.gif" class="cInlineImage-full"/>

## Go to symbol

The [Go to symbol](https://code.visualstudio.com/docs/editor/editingevolved#_go-to-symbol) feature allows you to navigate symbols inside a file.

You can navigate symbols within a file by pressing `Ctrl` + `Shift` + `O` on Windows and Linux, or `shift` + `⌘`+ `O` on a Mac.
The symbols can be grouped by category by typing `:`.

<img src="/learn/images/vs-code-extension/edit-the-code/code-navigation/go-to-symbol.gif" class="cInlineImage-full"/>

## Find all references

Invoking the references (right click on a symbol and select **Find All References**) on a symbol will prompt you with all the symbol references in the current project.

You can also press `Alt` + `Shift` + `F12` on Windows and Linux, or `⌥` + `shift` + `F12` on Mac to find all references.

<img src="/learn/images/vs-code-extension/edit-the-code/code-navigation/find-all-references.png" class="cInlineImage-full"/>

## Peek

This feature allows you to [peek](https://code.visualstudio.com/docs/editor/editingevolved#_peek) the definition or references of a given symbol.

On Windows and Linux, press `Ctrl` + `Shift` + `F10`, or on Mac, press `shift` + `F12` to open the peek view.

<img src="/learn/images/vs-code-extension/edit-the-code/code-navigation/peek-definition.png" class="cInlineImage-full"/>

## Rename symbols

This feature allows you to rename symbols by renaming all the references of the particular symbol.

Press `F2`, type the new desired name, and then press `Enter`. This will rename all usages of the symbol across files.
You can also right-click on the symbol and select **Rename Symbol** to rename it.

<img src="/learn/images/vs-code-extension/edit-the-code/code-navigation/rename-symbols.gif" class="cInlineImage-full"/>

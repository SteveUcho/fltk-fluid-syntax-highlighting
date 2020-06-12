# fltk-fluid-syntax-highlighting README

This is the README for your extension "fltk-fluid-syntax-highlighting". After writing up a brief description, we recommend including the following sections.

> I included my own text using these tips boxes, because why not.

> I know, bad styling, rip

> I mostly wrote this to learn regular expressions, and learn I did... Quarantine has blessed(cursed) me with a lot of time

> If anyone actually manages to find this and use it, and wants me to make it better, I will, otherwise... prob not

## Features

Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

> Highlights 

## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them.

> No requirements, opening .fl files will trigger the syntax highlighter

> Now that I think about this, maybe at least the VScode version that uses TextMate Syntax Highlighting

> Note to the above: VScode 1.9 and above will work

## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something

## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.

> This Extension has only been tested on files produced directly using the FLUID application

> I made it intentionally bad, it mostly takes ranges from start of line to end, meaning for example: putting any "Fl_[A-Za-z_]+" before a curly brace "{" would break it

> I mostly wrote this for myself, just thought I would share this on VScode

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

>Initial release of syntax highlighting for the \"FLTK User Interface Designer (FLUID)\" .fl file format

-----------------------------------------------------------------------------------------------------------

## Working with Markdown

**Note:** You can author your README using Visual Studio Code.  Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+CMD+V` on macOS or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (macOS) to see a list of Markdown snippets

### For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**

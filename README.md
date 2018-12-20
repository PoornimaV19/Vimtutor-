# Vim Basics
> This tutorial is going to speak about vim basic use. Vim is a powerful text editor used in CLI (command line interface). Linux uses a lot of configuration files, you'll often need to edit them and vim is a great tool to do so. Alternatives to vim are the commandline editors nano and joe.
>
> Vim has a particular working method, there are two main modes: the command mode and the other modes.

> The command mode lets you select the working mode that you want to enter. Available modes are: save, quit, copy, paste and that kind of things but you can't edit the file in the command mode directly. This is what many users that are new to vim puzzles and one has to get used to first.
> 
# Vim Modes
* Insert Mode
* Visual Mode
* Command Mode
>
# Insert Mode
> The Insert mode lets you insert text in a document. The shortcut is: "i" (insert text where the cursor is) or "o" (insert text at the beginning of the following line).
>
# Visual Mode
> The visual mode permits the user to select the text like you would do with a mouse, but using the keyboard instead of the mouse. Useful to copy several lines f text for example. The shortcut is: "V".
>
# Command Mode
> Let's now speak about the command mode, a command begins with the symbol ":".
>
> When you are in another mod you can use the escape key (sometimes you'll need to hit it twice) to come back to command mod at any time.
>
> For a more in-depth explanation of the Vim modes, take a look at the tutorial:[Vim Editor modes Explained]()
>
# Vim Command Reference
```
save: :w
save and exit: :wq
exit: :q
force: ! (example :w! :q!)
vertical split: open a document and then type :vsplit /path-to-document/document and this will open the specified document and split the screen so you can see both documents.
copy: y
copy a line: yy
paste: p
cut: d
cut a line: dd
```
# Advanced Features
* [How to perform search operations in Vim]()
* [Vim Editor Modes explained]()
* [How to access shell or run external commands from within Vim]()
* [How to make file-specific setting changes in Vim using Modeline]()

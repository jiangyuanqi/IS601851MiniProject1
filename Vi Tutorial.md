# VI Tutorial

![VI Startup Screen](/images/VIStartup.PNG)

## Introduction

1. What is it?
    * VI is a text editor. Vim (VI improved) is a common replacement for it. Vim is fully backwards compatible with VI, and is used in most modern systems. The instructions here apply to VI, but your system will probably come with Vim which will work exactly the same.
2. Why do you do it?
    * You use vi when you want to edit any text file on a linux system
3. How do you do it?
    * See the below sections

## Accessing Vi

 To access VI, you type `vi` followed by the name of the file you want to create. If the file your want to create doesn't exist, it will be created.

## Using Vi

There are two main modes in VI, command mode and insert mode. Insert mode is used for actually writing and modifying text, while command mode is for everything else (eg. saving the file, exiting the file, etc.).

## Command Mode

![VI Startup Screen](/images/VICommandMode.PNG)

When you first open VI, it will open in command mode. If you are in insert mode and you want to enter command mode, just press `Escape`. You will know you are in command mode because any text you type will appear at the bottom left corner. Once you are inh command mode, there are several useful comamnds you can run. They are listed in the table below with a description of what they can do.

Command | Description
------------ | -------------
i | Enters insert mode
k | Moves the cursor up
j | Moves the cursor down
h | Moves the cursor left
l | Moves the cursor right
i | Enters insert mode
x | Deletes the currently selected character
:w | Saves the file to the disk
:q | Exits without saving
:q! | Exits forcefully without saving
:wq | Saves and exits

## Insert Mode

![VI Startup Screen](/images/VIInsertMode.PNG)

When you are in command mode, you can press `i` to enter insert mode. You will know you are in insert mode because at the bottom, it will say "`-- INSERT --`" Once you are in insert mode, just type whatever text you would like to. Be aware that the characters you enter will be placed before the currently selected character. To exit insert mode, just press `Escape`.

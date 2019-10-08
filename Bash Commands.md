
# Bash Command Introduction

## cd

------

1. What is it?
    * cd stands for change directory.
2. Why do you do it?
    * You use cd to navigate through your filesystem.
3. How do you do it?
    * you use cd by typing cd followed by a directory

### Examples

```bash
$ cd /mnt #changes the working directory to /mnt
$ cd ../ #changes the working directory to the parent of the working directory
$ cd projectFolder #changes the working directory to a folder name projectFolder located inside the working directory
```

## mkdir

------

1. What is it?
    * mkdir stands for make directory
2. Why do you do it?
    * You use mkdir to create directories in your filesystem.
3. How do you do it?
    * You use mkdir by typing mkdir followed by the name of the directory you want to create

### Examples

```bash
$ mkdir newFolder #creates a folder in the working directory called newFolder
$ mkdir ../secondNewFolder #creates a folder in the parent of the working directory called secondNewFolder
```

## cp

------

1. What is it?
    * cp stands for copy
2. Why do you do it?
    * You use cp to copy files and directories within your filesystem.
3. How do you do it?
    * You use cp by typing cp followed by the name of the file/directory you want to copy followed by the destination. If you are copying a directory, be sure to use the -r flag to copy recursively. You can also choose to give the file/directory a new name in it's destination by making the basename of the destination the new name.

### Examples

```bash
$ cp oldFile /bin/  #copies oldFile into /bin/
$ cp oldFile /bin/newFileName  #copies oldFile into /bin/ and renames it to newFileName
$ cp -r oldDirectory /bin/  #copies oldDirectory into /bin/
$ cp -r oldDirectory /bin/newDirectoryName   #copies oldDirectory into /bin/ and renames it to newFileName
```

## pwd

------

1. What is it?
    * pwd stands for print working directory
2. Why do you do it?
    * You use pwd to print out the location you are currently in
3. How do you do it?
    * You use pwd by typing out the pwd on the command line

### Examples

```bash
$ pwd #prints current directory
```

## mv

------

1. What is it?
    * mv stands for move
2. Why do you do it?
    * You use mv to move files and directories within your filesystem. You can also use it to rename files and directories by moving to the same location and changing the name
3. How do you do it?
    * You use mv by typing mv followed by the name of the file/directory you want to move followed by the destination. If you are moving a directory, be sure to use the -r flag to move recursively. You can also choose to give the file/directory a new name in it's destination by making the basename of the destination the new name.

### Examples

```bash
$ mv oldFile /bin/  #moves oldFile into /bin/
$ mv oldFile /bin/newFileName  #moves oldFile into /bin/ and renames it to newFileName
$ mv -r oldDirectory /bin/  #moves oldDirectory into /bin/
$ mv -r oldDirectory /bin/newDirectoryName   #moves oldDirectory into /bin/ and renames it to newFileName
```

## rm

------

1. What is it?
    * rm stands for remove
2. Why do you do it?
    * You use rm to remove files and directories within your filesystem.
3. How do you do it?
    * You use rm by typing rm followed by the name of the file/directory you want to remove. If you are removing a directory, be sure to use the -r flag to remove recursively within the directory.

### Examples

```bash
$ rm file  #deletes file
$ rm -r ./folder  #deletes folder and all of its contents
```

## history

------

1. What is it?
2. Why do you do it?
3. How do you do it?

## Home directory and ~

------

1. What is it?
2. Why do you do it?
3. How do you do it?

## file paths in linux

------

1. What is it?
2. Why do you do it?
3. How do you do it?

## Using the tab key to complete file paths

------

1. What is it?
2. Why do you do it?
3. How do you do it?

## Using up and down arrow for history

------

1. What is it?
2. Why do you do it?
3. How do you do it?

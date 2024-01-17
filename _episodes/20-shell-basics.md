---
title: "Introduction to the Command Line"
teaching: 95
exercises: 0
questions:
- "What is a command shell and why would I use one?"
- "How can I move around on my computer?"
- "How can I see what files and directories I have?"
- "How can I specify the location of a file or directory on my computer?"
- "How can I create, copy, and delete files and directories?"
- "How can I edit files?"
objectives:
- "Explain how the shell relates to the keyboard, the screen, the operating system, and users’ programs."
- "Explain when and why command-line interfaces should be used instead of graphical interfaces."
- "Explain the similarities and differences between a file and a directory."
- "Translate an absolute path into a relative path and vice versa."
- "Construct absolute and relative paths that identify specific files and directories."
- "Use options and arguments to change the behaviour of a shell command."
- "Demonstrate the use of tab completion and explain its advantages."
- "Create a directory hierarchy that matches a given diagram."
- "Create files in that hierarchy using an editor or by copying and renaming existing files."
- "Delete, copy and move specified files and/or directories."
keypoints:
- "A shell is a program whose primary purpose is to read commands and run other programs."
- "This lesson uses Bash, the default shell in many implementations of Unix."
- "Programs can be run in Bash by entering commands at the command-line prompt."
- "The shell’s main advantages are its high action-to-keystroke ratio, its support for automating repetitive tasks, and its capacity to access networked machines."
- "A significant challenge when using the shell can be knowing what commands need to be run and how to run them."
- "The file system is responsible for managing information on the disk."
- "Information is stored in files, which are stored in directories (folders)."
- "Directories can also store other directories, which then form a directory tree."
- "`pwd` prints the user’s current working directory."
- "`ls [path]` prints a listing of a specific file or directory; ls on its own lists the current working directory."
- "`cd [path]` changes the current working directory."
- "Most commands take options that begin with a single `-`."
- "Directory names in a path are separated with `/` on Unix, but `\\` on Windows."
- "`/` on its own is the root directory of the whole file system."
- "An absolute path specifies a location from the root of the file system."
- "A relative path specifies a location starting from the current location."
- "`.` on its own means ‘the current directory’; .. means ‘the directory above the current one’."
- "`cp [old] [new]` copies a file."
- "`mkdir [path]` creates a new directory."
- "`mv [old] [new]` moves (renames) a file or directory."
- "`rm [path]` removes (deletes) a file."
- "`*` matches zero or more characters in a filename, so `*.txt` matches all files ending in `.txt`."
- "`?` matches any single character in a filename, so `?.txt` matches `a.txt` but not `any.txt`."
- "Use of the Control key may be described in many ways, including Ctrl-X, Control-X, and ^X."
- "The shell does not have a trash bin: once something is deleted, it’s really gone."
- "Most files’ names are `something.extension`. The extension isn’t required, and doesn’t guarantee anything, but is normally used to indicate the type of data in the file."
- "Depending on the type of work you do, you may need a more powerful text editor than Nano."

---

## Software Carpentry lessons for shell basics

The "command line" or "shell" is an important tool for HPC work. To learn the basics, we will go through these episodes from the  [Software Carpentry Shell Novice][shell-novice] lesson.

- [Introducing the Shell][shell-intro]
- [Navigating Files and Directories][shell-filedir]
- [Working with Files and Directories][shell-create]

[shell-novice]: https://swcarpentry.github.io/shell-novice/index.html
[shell-intro]: https://swcarpentry.github.io/shell-novice/01-intro.html
[shell-filedir]: https://swcarpentry.github.io/shell-novice/02-filedir.html
[shell-create]: https://swcarpentry.github.io/shell-novice/03-create.html

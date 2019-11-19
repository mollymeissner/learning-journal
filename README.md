# Learning Journal
_by Molly Meissner_

[Github portfolio](https://github.com/mollymeissner)

**Bio:** As a former Software Business Development Representative at Algolia, I'm excited to challenge my brain to learn the skills of a Software Developer at Code Fellows. I'm ready to _learn how to learn_.

## Table of Contents
- [Growth Mindset](#GrowthMindset)

- [Git](https://mollymeissner.github.io/learning-journal/git.md)

## Growth Mindset

### A "growth mindset" is the perception that through you can further develop your abilities and intelligence through hard work and dedication.

**Reminders on how to keep a growth mindset:**
1. When it gets tough, or when you're confused, that's when the real learning begins
1. You learn more and achieve more when you're challenging yourself and pushing yourself to do what's uncomfortable
1. Studying, practicing, persisting, and listening to feedback leads to growth

## The Coder's Computer

#### Choosing a Text Editor

I chose to doanload the Text Editor, VS Code, rather than sticking with the Text Editor, "Text Edit" that comes with my Mac computer already. This decision was based on the fact that VS Code is recommended by Code Fellows. It provides more advanced features and allows you to code faster using shortcuts. You can also doanload extensions for css styling or other tools.

Definition Cheat Sheet of Terms (on Linux):
- The Command Line (or terminal): a text based interface to the system. Enter commands by typing them on the keyboard and feedback will be given to you similarly as text.
  - Line 1: Options are typically used to modify the behaviour of the command, and typically start with a dash ( - ).
  - Lines 2 - 5 are output from running the command.
  - Line 6 presents us with a prompt again.
  
- bash: a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you.
  
- Shortcuts: View your history to see your past commands, and use them again in the future.

#### Paths:
1. absolute: A file or directory location in relation to the root of the file system.
1. relative: A file or directory location relative to where we currently are in the file system.

### Basic Navigation in the Terminal
1. (pwd) Print Working Directory: remind yourself where you presently are
1. tree: directory in the view
1. ls : list of files
1. "- la" is a modifier (This will show me all the hidden files)
- ls -la : show hidden files and directories

1. root directory: It is denoted by a single slash ( / )
1. cd: Change Directories - ie. move to another directory.
1. (i.e.) "cd codefellows/"

1. /etc - Stores config files for the system.
1. /var/log - Stores log files for various system programs.
1. /bin - The location of several commonly used programs (some of which we will learn about in the rest of this tutorial.
1. /usr/bin - Another location for programs on the system.

1. "mkdir code-102": make directory
1. "touch": create a file (i.e.: "touch index.html")
1. "code .": to open your text editor
1. check history, and then "clear"
1. rm <file>: delete file (forever)

1. to go back to the top of your file system, use "cd /"
1. go back 1 levels: "cd ./"
1. go back 2 levels: "cd ../"

### About Files
- Everything is a file under Linux. Even directories.
- Linux is an Extensionless System
command "file [path]": to know for certain what type of file a particular file is
- a path is a means to get to a particular location in the system and that location is a file
- Files can have any extension they like or none at all.

Linux is Case Sensitive: Beware of silly typos!
- It is possible to have two or more files and directories with the same name but letters of different case

Spaces in names: 2 ways to use spaces in a command line
1. Quotes: cd 'Holiday Photos'
1. Escape Characters: cd Holiday\ Photos
*Shortcut*: use Tab Completion

### GitHub Pages:

- GitHub Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository on GitHub, optionally runs the files through a build process, and publishes a website

## Learning Markdown:

- Markdown is an easy-to-use syntax for styling writing. For examples, GitHub explains this further below!

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/mollymeissner/learning-journal/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

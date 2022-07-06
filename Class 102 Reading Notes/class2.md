# The Coder's Computer

##### *Monday, June 27, 2022*

## Choosing A Text Editor

#### What is a text editor

For starters, a text editor is maybe the most important tool in an aspiring web developer's tool box. The text editor does exactly what it sounds like, edits text. But the application itself is more complicated than that. A text editor allows an developer to type different syntax and code while assisting in formatting, copy editing and deployment.

#### Important Features of Text Editors

###### Code Complete

Many text editors can predict what syntax you are going to use and give you a list of common syntax that match the letters you are typing in the text editor. Instead of typing the entire line out use one of the suggestions and save yourself time and typing. 

###### Syntax Highlighting

Syntax highlighting helps a web developer stay more organized by color coding different syntax. This makes it clear to the developer where the key components of different code structures are. 

###### Extensions

Extensions are third-party sub-applications that add capability to a text editor. For example, instead of using a different application to preview your html, you can use an extension that is built into your text editor and keep all of your work within the application you're already using. There are thousands of different extensions available. Some text editors have a larger selection of extensions than others.

###### Themes

Eye strain is defintely a con in coding. You are staring at a screen all day. That's why a selection of different themes is important to making a great text editor. Themes change the color pallete of the text editor, allowing the user to select a theme that is easier on the eyes.

#### Final Thoughts

Ultimately, the text editor you choose will come down to personal preference which will likely be influenced by the features listed in the previous sections. There are many great text editors to choose from and you can make an argument about better or worse choices, but there seems to be no wrong choice.

## The Command Line

The command line lets you speak directly to the computer in an input / output method. Rather than navigate throught your desktop with a mouse, the entire computer is also accessible to you through the command prompt.

But, the command prompt is more than just a navigation shortcut. It allows you to many functions that aren't available through other means on the desktop. You can have multiple command prompts open to show pages, data and work behind the scenes on a task all at the same time.

## Basic Navigation

Basic navigation in the command prompt is done through a set of, you guessed it, commands. Each of these commands can be run with an option or an argument to vary the function of the command. These commands, options and arguments work together to tell you where you are in your computer. Location in the command prompt can be determined by which user, drive, director, folder and files you are in. Each of these also has it's own data that can be summoned through the command prompt. This data may be how many folders are in a directory or the names of files in a folder. Paths are commands that, rather than give you information about where you're at, navigate you to a specific file or directory. A relative path is file or directory location relative to where we currently are in the file system. An absolute path
is a file or directory location in relation to the root of the file system.

Here are a few common navigational commands: pwd - Print Working Directory - ie. Where are we currently.
ls - List the contents of a directory.
cd - Change Directories - ie. move to another directory.

You can use an option by placing "-l" in front of the command and an argument by placing "/etc". You can also perform an option and an argument on the same command.

## About Files

*A few tips and rules to consider when dealing with files in command prompt.*

In linux, everything from text to your monitor is considered a file. 

Linux does not use file extensions to determine what type of file it is. Linux looks at the contents of the file to make that determination.

Linux is case sensitive. Meaning file1 and File1 are two completely different files. 

You can use spaces in file names, but you need to know the rules. Ex: Wrong - Holiday Photos Right - 'Holiday Photos' Right - Holiday\ Photos
In the first example linux uses only the first word, therefor would not be able to find the actual file were looking for. In the second example we use single quotes to tell linux that these two words are to be searched together. In the last example we use a backslash to tell the linux to ignore the special meaning of the space after it, allowing linux to read the text correctly and not just search for holiday alone. 

Use a . in front of the file name to hide it and use ls -a to show hidden files. 

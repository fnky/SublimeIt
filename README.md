SublimeIt
=========

An extension for Alfred to open selected or specified files in Sublime Text 2

## How to use

It's really easy to use SublimeIt on your files and folders with [Alfred](http://alfredapp.com/ "Alfred"). Before you can use the extension, you will of course need the [Powerpack](http://www.alfredapp.com/powerpack/ "Alfred Powerpack") to get more features like using extensions and more. If all is set, grab the extension and open it to install it into Alfred. You are now ready!

Open Alfred with your hotkey. SublimeIt is triggered by the `subl` command. If no queries are specified, it will open selected files and/or folders in Sublime Text 2. Otherwhise, if you specify files or folders like this

	subl file.txt

It will open Sublime Text 2 with the specified file. You can also open with multiple files by using

	subl file1.txt file2.txt

If the files or folders is already existing it will just open those files or folders. Specify a path to the file or folder you wan't to open

	subl ~/Documents/My Project/
	subl ~/Document/My Project/index.html

Sublime Text 2's command line is also available. Especially the cool feature to open a file at a specified line and/or column

	subl existingfile.txt:4:2

You can read more about [Sublime Text 2 OS X Command Line](http://www.sublimetext.com/docs/2/osx_command_line.html "Sublime Text 2 OS X Command Line") for all available commands.

### TODOs
- Make it so if nothing is selected or specified, it will just open Sublime Text 2 with an empty file.
- Make it run with [@jdfwarrior](https://twitter.com/#!/jdfwarrior "@jdfwarrior on Twitter")'s [Extension Updater](http://jdfwarrior.tumblr.com/post/13826478125/extension-updater "Extension Updater") for easy updates.

### Credits
Thanks to Naatan & n8gray for making most of the scripts available.
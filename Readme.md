# Helper for Macintosh Computer programs that runs at Startup.

### It locates the programs that runs at startup.

### It allows quick, start/stop (remove) options.

### It ignores core default programs that are needed for appropriate machine operation.

## Why make a helper anyway?
When you turn on your computer some programs automatically run. These programs exist in 5 different locations. Ohh no!!

![image](https://github.com/MichaelDimmitt/quick_launch_agent_monitor/blob/master/launch_agent_locations.png)

This program lets you put in one command and WHAM!!!! you can quickly understand your startup programs. Secondly power to customize is made availiable, easy and safe. Enjoy being empowered. :smile:

## Bear Minimum Planned Features
step 1) textual list of the locations.
<br>step 2) store names of Launch Agents we want to ignore in an ignore file.
<br>step 3) Allow user search functionality... which simply greps User Input string.

## Features, if I build the whole Enchilada:

1) Make an interface for people to quickly load and unload the launch agents.
2) Make it easy to delete unwanted launch agents...

were talking start, stop, uninstall, and install.


3) Normal output piped to grep. Ignoring output is piped from a file to grep -v. Result should cut down output.
example: history | grep 'yum install' | grep -v 'history'; history | grep 'yum uninstall' | grep -v 'history';

4) keep an active list of the ignores... maybe a folder system. 
that way as a user adds launch agents they can organize, grouping launch agents by category. An example: dropbox and slack and chrome may bunch under folder name "core applications, safe, saving information". However, f.lux and shazam and ampetheatr may bunch under "minor convenience, menubar" also, "screensaver" grouping.
The point is that the user will be able to make custom names.

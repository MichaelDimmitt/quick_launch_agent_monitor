# QuickLaunchAgentMonitor: Manage your startup program list

The QuickLaunchAgentMonitor helps you manage your list of programs
that run during startup.  It will locate all the programs that run at
startup, and allows you to quickly add or remove programs to your
startup. It ignores core default programs that are needed for regular
machine operation and lists only those that are safe to remove from
the startup lit.

## Why make a helper anyway?
When you turn on your computer some programs automatically run. These programs exist in 5 different locations. Oh no!!

![image](https://github.com/MichaelDimmitt/quick_launch_agent_monitor/blob/master/launch_agent_locations.png)

This program lets you put in one command and WHAM!!!! you can quickly understand your startup programs. It gives you power to customize ???is made available???, easy and safe. Enjoy being empowered. :smile:

^^^ is made availiable seems to have been either part of the  original sentence or a new sentence that was never fully formed ^^^

## Development plan:
  1. Show a text list of the locations.
  2. Store names of Launch Agents we want to ignore in an ignore file.
  3. Allow user search functionality... which simply greps User Input string.

## Additional Features (if I build the whole Enchilada)

 1. Make an interface for people to quickly load and unload the launch agents.
 2. Make it easy to delete unwanted launch agents (start, stop, uninstall, and install)
 3. Pipe output to grep and add items from ignore file to grep -v. Result should cut down output.
    example: history | grep 'yum install' | grep -v 'history'; history | grep 'yum uninstall' | grep -v 'history';
 4. Keep an active list of the ignores.
 5. Add a folder system to allow grouping of applications
    a. A user adds launch agents they can organize
    b. Grouping launch agents by category
    The user will be able to make custom names like "core applications, safe, saving information" to include, for example, dropbox, slack, chrome, and a separate folder like "minor convenience, menubar" for things like f.lux, shazam and ampetheatre.  The user will be able to select the names and decide what to include under each folder.


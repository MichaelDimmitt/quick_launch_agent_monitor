# QuickLaunchAgentMonitor: Manage your Startup Programs

The QuickLaunchAgentMonitor helps you manage your list of programs that run during startup. 
<br>It will locate all the programs that run at startup, 
<br>and allow you to quickly add or remove programs from the startup list. 
<br>It ignores core default programs that are needed for regular
<br>machine operation and list only programs those that are safe to remove from the startup list.

## Why make a helper anyway?
When you turn on your computer some programs automatically run. 
<br>However, these programs exist in 5 different locations. Oh no!!

![image](https://github.com/MichaelDimmitt/quick_launch_agent_monitor/blob/master/launch_agent_locations.png)

Install with one command and WHAM!!!! Quickly understand your startup programs. 
<br>Secondly, an interface will be provided that  makes customization safe and easy. Enjoy being empowered. :smile:

## Development plan:
  1. Show a text list of all "Startup Programs" across various startup locations.
  2. Store names of Launch Agents we want to ignore in an ignore file.
  3. Allow user search functionality... which simply greps User Input string.

## Additional Features (if I build the whole Enchilada)

 1. Make an interface for people to quickly load and unload the launch agents.
 2. Make it easy to delete unwanted launch agents 
    interface: (start, stop, uninstall, and install)
 3. Pipe output to grep and add items from ignore file to grep -v. Result should cut down output.
    example: history | grep 'yum install' | grep -v 'history'; history | grep 'yum uninstall' | grep -v 'history';
 4. Keep an active list of the ignores.
 5. Add a folder system to allow grouping of applications<br>
    a. A user adds launch agents they can organize<br>
    b. Grouping launch agents by category<br>
    The user will be able to make custom names like "core applications, safe, saving information" to include, for example, dropbox, slack, chrome, and a separate folder like "minor convenience, menubar" for things like f.lux, shazam and ampetheatre.  The user will be able to select the names and decide what to include under each folder.


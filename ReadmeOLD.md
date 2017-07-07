## Curious about what programs run when you turn on your computer?

step 1) ignore launch agents are included as mac core OS by adding to an ignore file.
step 2) textual list of the locations.
step 3) grep the "ls" of those locations, ignoring results in the ignore file.

## Future use cases, 
1) Make an interface for people to quickly load and unload the launch agents.
2) Make it easy to delete unwanted launch agents...

were talking start, stop, uninstall, and install.

## Future Ideas

1) Allow user search functionality... which simply greps the string.
2) Normal output piped to grep. Ignoring output is piped from a file to grep -v. Result should cut down output.
example: history | grep 'yum install' | grep -v 'history'; history | grep 'yum uninstall' | grep -v 'history';
3) keep an active list of the ignores... maybe a folder system. 
that way as a user adds launch agents they can organize, grouping launch agents by category. An example: dropbox and slack and chrome may bunch under folder name "core applications, safe, saving information". However, f.lux and shazam and ampetheatr may bunch under "minor convenience, menubar" also, "screensaver" grouping.
The point is that the user will be able to make custom names.




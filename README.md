# hub
A bookmark / shortcut / symbolic link manager for the terminal

# Why?
Most graphical filemanagers allow for bookmarks. Those of course don't work whilst working in the terminal and using cd.<br>
That's why a hub for all shortcuts would be useful. By default a `hub` folder is created in your home folder, to keep it uncluttered.<br>
Just `cd` to the `hub` folder and directly go to your linekd folder.

# How?

- `hub -a selected/directory optionalnewname` creates a link to the selected directory and a new optional name may be specified.
- -r removes the shortcut / link
- -c renames the link
- just calling `hub` lists all links

```
Options:
	Add a file/dir to the hub [-a|add]; Can have an optional new name
	Remove a file/dir [-r|remove]
	Change a file/dir [-c|change]
	List all files/dirs [-l|list]
	Open the file/dir via xdg-open

Examples:
	hub -a ~/Programming/Somedir newname
	hub
	hub -r newname
	hub -c newname newername
	hub somefile
 ```
# Installing
- Just copy this script file into some bin folder (e.g.: /bin)
- hub directory can be changed via the *$HUB* variable

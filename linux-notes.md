- **/etc** - Stores config files for the system.
- **/var/log** - Stores log files for various system programs. (You may not have permission to look at everything in this directory. Don't let that stop you exploring though. A few error messages never hurt anyone.)
- **/bin** - The location of several commonly used programs (some of which we will learn about in the rest of this tutorial.
- **/usr/bin** - Another location for programs on the system.
- **Everything is a file under Linux** Even directories.
- **Linux is an extensionless system** Files can have any extension they like or none at all.
# Permissions
## Files
Linux permissions dictate 3 things you may do with a file, read, write and execute. They are referred to in Linux by a single letter each.
- r read - you may view the contents of the file.
- w write - you may change the contents of the file.
- x execute - you may execute or run the file if it is a program or script.

For every file we define 3 sets of people for whom we may specify permissions.
- owner - a single person who owns the file. (typically the person who created the file but ownership may be granted to some one else by certain users)
- group - every file belongs to a single group.
- others - everyone else who is not in the group or the owner.

Three persmissions and three groups of people. That's about all there is to permissions really. Now let's see how we can view and change them.

## Directories
The same series of permissions may be used for directories but they have a slightly different behaviour.
- r - you have the ability to read the contents of the directory (ie do an ls)
- w - you have the ability to write into the directory (ie create files and directories)
- x - you have the ability to enter that directory (ie cd)

# Filters
- head - View the first n lines of data.
- tail - View the last n lines of data.
- sort - Organise the data into order.
- nl - Print line numbers before data.
- wc - Print a count of lines, words and characters.
- cut - Cut the data into fields and only display the specified fields.
- sed - Do a search and replace on the data.
- uniq - Remove duplicate lines.
- tac - Print the data in reverse order.
- awk
- diff

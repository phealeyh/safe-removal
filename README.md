# safe-removal
A safe removal unix script that will safely remove your files into a recycling bin.
It will also restore files to the original location with the safe_rm_restore script.

# Usage

Removing a file
./safe_rm.rm <file_name>

Restoring a file
Check the /deleted directory to find the inode of the file and use that when restoring your file
./safe_rm_restore.rm <file_name_with_inode>

Tags/modifiers
-I = Interactive, provides a interactive way of deleting the files with prompts
-V = Verbose, displays the action taken
-R = Recursive, removes files rercusively if there is a folder

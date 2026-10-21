# Linux some important Commands for DevOps Engineer

# File and Directory Operations Commands

## ls commands : for List files and directories.

- l: Long format listing.
- a: Include hidden files hidden ones
- h: Human-readable file sizes.
- ls -l: displays files and directories with detailed information.
- ls -la: shows all files and directories, including
- ls -lh: displays file sizes in a human-readable format.

## cd: Change directory.

- cd: /path/to/directorychanges the current directory to the specified path.

## pwd: Print current working directory.

- pwd: displays the current working directory.

## mkdir Create a new directory.

- mkdir my_directorycreates a new directory named "my_directory".

## rm: Remove files and directories.

- -r: Remove directories recursively.
- -f : Force removal without confirmation
- rm file.txtdeletes the file named "file.txt".
- rm -r my_directory :eletes the directory "y_directory" and its contents.
- rm -f file.txtforcefully deletes the file "file.txt" without confirmation.

## cp: Copy files and directories.

- -r: Copy directories recursively.
- cp -r directory destination copies the directory "directory" and its contents to the specified destination.
- cp file.txt destinationcopies the file "file.txt" to the specified destination.

## mv: Move/rename files and directories.

- mv file.txt new_name.txtrenames the file "file.txt" to "new_name.txt".
- mv file.txt directorymoves the file "file.txt" to the specified directory.

##touch: Create an empty file or update file timestamps.

- touch file.txtcreates an empty file named "file.txt".

## cat: View the contents of a file.

- cat file.txtdisplays the contents of the file "file.txt".

## head: Display the first few lines of a file.

- n: Specify the number of lines to display.

- head file.txtshows the first 10 lines of the file "file.txt".
- head -n 5 file.txtdisplays the first 5 lines of the file "file.txt".

## tail: Display the last few lines of a file.

- -n: Specify the number of lines to display
- tail file.txt shows the last 10 lines of the file "file.txt".
- tail -n 5 file.txt displays the last 5 lines of the file "file.txt".

## ln: Create links between files.

- -s: Create symbolic (soft) links.
- ln -s source_file link_name
  creates a symbolic link named "link_name" pointing to "source_file".

## find: Search for files and directories.

- -name: Search by filename.
- -type: Search by file type.
- find /path/to/search -name "\*.txt"searches for all files with the extension ".txt" in the specified directory

# File Permission Commands

## chmod : Change file permissions.

- u: User/owner permissions.
- g: Group permissions.
- o: Other permissions.
- +: Add permissions.
- –: Remove permissions.
- =: Set permissions explicitly.

### chmod u+rwx file.txt

grants read, write, and execute permissions to the owner of the file.

## chown: Change file ownership

### chown user file.txt

- changes the owner of "file.txt" to the specified user.

## chgrp : Change group ownership.

### chgrp group file.txt

changes the group ownership of "file.txt" to the specified group.

## umask: Set default file permissions.

### umask 022

- sets the default file permissions to read and write for the owner, and read-only for group and others.

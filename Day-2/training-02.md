# File Compression and Archiving Commands

## tar: Create or extract archive files.

- -c: Create a new archive.
- -x: Extract files from an archive.
- -f: Specify the archive file name.
- -v: Verbose mode.
- -z: Compress the archive with gzip.
- -j: Compress the archive with bzip2.

### Example

- tar -czvf archive.tar.gz files/ creates a compressed tar archive named “archive.tar.gz” containing the files in the “files/” directory.

## gzip : Compress files.

- -d: Decompress files.

### gzip :

- file.txtcompresses the file “file.txt” and renames it as “file.txt.gz”.

### zip : Create compressed zip archives.

- -r: Recursively include directories.

### zip archive.zip file1.txt file2.txt

- zip archive.zip file1.txt file2.txtcreates a zip archive named “archive.zip” containing “file1.txt” and “file2.txt”.

# Process Management Commands :

## ps : Display running processes.

- -aux: Show all processes.

- ps auxshows all running processes with detailed information.

## top: Monitor system processes in real-time.

- top displays a dynamic view of system processes and their resource usage.

## kill : Terminate a process.

- -9: Forcefully kill a process.
- kill PID terminates the process with the specified process ID.

## pkill : Terminate processes based on their name.

- pkill process_nameterminates all processes with the specified name.

## pgrep: List processes based on their name.

- pgrep process_namelists all processes with the specified name.

## grep : used to search for specific patterns or regular expressions in text files or streams and display matching lines.

- -i: Ignore case distinctions while searching.
- -v: Invert the match, displaying non-matching lines.
- -r or -R: Recursively search directories for matching patterns.
- -l: Print only the names of files containing matches.
- -n: Display line numbers alongside matching lines.
- -w: Match whole words only, rather than partial matches.
- -c: Count the number of matching lines instead of displaying them.
- -e: Specify multiple patterns to search for.
- -A: Display lines after the matching line.
- -B: Display lines before the matching line.
- -C: Display lines both before and after the matching line.

## Example

- grep -i “hello” file.txt
- grep -v “error” file.txt
- grep -r “pattern” directory/
- grep -l “keyword” file.txt
- grep -n “pattern” file.txtIn these examples we are extracting our desirec output from filename (file.txt)

# System Information Commands

## uname : Print system information.

- -a: All system information.
- uname -a displays all system information.

## whoami : Display current username.

- whoami shows the current username.

## df : Show disk space usage.

- -h: Human-readable sizes.

- df -h displays disk space usage in a human-readable format.

## du : Estimate file and directory sizes.

- -h: Human-readable sizes.
- -s: Display total size only.
- du -sh directory/provides the total size of the specified directory.

## free : Display memory usage information.

- -h: Human-readable sizes.
- free -h displays memory usage in a human-readable format.

## uptime : Show system uptime.

- uptime shows the current system uptime.

## lscpu: Display CPU information.

- lscpu provides detailed CPU information.

## lspci : List PCI devices.

- lspci List PCI devices.

## lsusb : List USB devices.

- lsusb lists all connected USB devices.

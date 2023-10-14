# OS EX.4-LINUX-COMMANDS

## AIM:
To study and execute basic UNIX commands.

## Software requirements:
Linux operating system.

### COMMAND 1: ls - List Files and Directories
```
Syntax: 
	ls [options] [directory]
Code: 
	ls -l /home/user
Output: 
	List of files and directories in /home/user with details.
```

### COMMAND 2: cd - Change Directory
```
Syntax: 
	cd [directory]
Code: 
	cd /var/www
Output: 
	Change to the /var/www directory.
```

### COMMAND 3: pwd - Print Working Directory
```
Syntax: 
	pwd
Code: 
	pwd
Output: 
	/home/user (prints the current working directory).
```

### COMMAND 4: mkdir - Create Directory
```
Syntax: 
	mkdir [directory]
Code: 
	mkdir my_directory
Output:	
	Creates a new directory named my_directory.
```

### COMMAND 5: touch - Create Empty File
```
Syntax: 
	touch [filename]
Code: 
	touch newfile.txt
Output: 
	Creates a new empty file named newfile.txt.
```

### COMMAND 6: cp - Copy Files and Directories
```
Syntax: 
	cp [options] source destination
Code: 
	cp file.txt /backup/
Output: 
	Copies file.txt to the /backup/ directory.
```

### COMMAND 7: mv - Move/Rename Files and Directories
```
Syntax: 
	mv [options] source destination
Code: 
	mv oldfile.txt newfile.txt
Output: 
	Renames oldfile.txt to newfile.txt.
```

### COMMAND 8: rm - Remove Files and Directories
```
Syntax: 
	rm [options] [file/directory]
Code: 
	rm file.txt
Output: 
	Deletes file.txt.
```

### COMMAND 9: cat - Concatenate and Display File Content
```
Syntax: 
	cat [filename]
Code: 
	cat file.txt
Output: 
	Displays the content of file.txt.
```

### COMMAND 10: more - View File Content Page by Page
```
Syntax: 
	more [filename]
Code: 
	more longfile.txt
Output: 
	Allows you to view the content of longfile.txt one page at a time.
```

### COMMAND 11: less - View File Content with Navigation
```
Syntax: 
	less [filename]
Code: 
	less largefile.txt
Output: 
	Displays largefile.txt with navigation capabilities.
```

### COMMAND 12: head - Display Top Lines of a File
```
Syntax: 
	head [options] [filename]
Code: 
	head -n 5 file.txt
Output: 
	Shows the first 5 lines of file.txt.
```

### COMMAND 13: tail - Display Bottom Lines of a File
```
Syntax: 
	tail [options] [filename]
Code: 
	tail -n 10 file.log
Output: 
	Shows the last 10 lines of file.log.
```

### COMMAND 14: grep - Search Text in Files
```
Syntax: 
	grep [options] 'pattern' [file(s)]
Code: 
	grep 'keyword' file.txt
Output: 
	Lists lines containing 'keyword' in file.txt.
```

### COMMAND 15: find - Search for Files and Directories
```
Syntax:
	find [path] [expression]
Code: 
	find /home/user -name '*.txt'
Output: 
	Finds all .txt files under /home/user.
```

### COMMAND 16: chmod - Change File Permissions
```
Syntax: 
	chmod [options] permissions file(s)
Code: 
	chmod 644 file.txt
Output: 
	Sets read and write permissions for the owner and read-only permissions for others on file.txt.
```

### COMMAND 17: chown - Change File Ownership
```
Syntax: 
	chown [options] user:group file(s)
Code: 
	chown user:group file.txt
Output: 
	Changes the owner and group of file.txt.
```

### COMMAND 18: tar - Archive and Compress Files
```
Syntax: 
	tar [options] [file(s)]
Code: 
	tar -cvzf archive.tar.gz dir/
Output: 
	Creates a compressed archive of the dir/ directory.
```

### COMMAND 19: df - Display Disk Space Usage
```
Syntax: 
	df [options] [filesystem(s)]
Code: 
	df -h
Output: 
	Shows disk space usage in a human-readable format.
```

### COMMAND 20: du - Display Directory Space Usage
```
Syntax: 
	du [options] [directory]
Code: 
	du -sh /var
Output: 
	Displays the total size of the /var directory in a human-readable format.
```

### COMMAND 21: ps - Display Process Status
```
Syntax: 
	ps [options]
Code: 
	ps aux
Output: 
	Lists running processes with details.
```

### COMMAND 22: kill - Terminate Processes
```
Syntax: 
	kill [signal] [PID]
Code: 
	kill -9 1234
Output: 
	Sends a SIGKILL signal to process with PID 1234.
```

### COMMAND 23: ssh - Secure Shell
```
Syntax: 
	ssh [user@]hostname
Code: 
	ssh user@remote-server
Output: 
	Establishes a secure remote connection to remote-server.
```

### COMMAND 24: scp - Securely Copy Files Over SSH
```
Syntax:
	scp [options] source destination
Code: 
	scp file.txt user@remote-server:/path/
Output: 
	Copies file.txt to a remote server over SSH.
```

### COMMAND 25: wget - Download Files from the Internet
```
Syntax: 
	wget [options] [URL]
Code: 
	wget https://example.com/file.zip
Output: 
	Downloads file.zip from the specified URL.
```

## RESULT:
Thus basic UNIX commands are studied and executed.

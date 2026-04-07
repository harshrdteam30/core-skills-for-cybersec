## Bash
Bash (Bourne Again Shell) program. Bash is the default shell for most Linux distributions, making it an essential tool to learn.

## Commands 
- echo "Hello"   
	prints hello  
  
- pwd  
	shows current working directory  
  
- cd ../home../$HOME  
	changes current working directory  
  
- ls  
	lists all files in current directory  
	ls -a ( lists hidden files )  
  
- touch  
	creates new file also helps change timestamps
  
- file  
	determine the file type  
  
- cat  
	shows file content  
  
- [less](./less.md)  
  
- history  
	shows last 100 used commands  
  
- cp
	cp -r source/ dest/ 
	copies each and every file recursively from source to dest.

- mv 
	for moving content

- mkdir
	create directory
	mkdir -p dir/dir1/dir2 ( all created simultaneously)

- rm 	
	remove file
	rm -f (force ful deletion)
	rm -i (interactive deletion)
	rm -r (directory)
	rm -rf (recursively delete every file and folder)
	
- rmdir 
	delete empty directory

- find
	find /location -name "file" 	finds file
	find /location -type d(for directory) -name {foldername}	finds directory

- help
	help {command} 

- man
	man "comm" 	manual pages 

- whatis "cmd"
	know about command

- alias 
	alias update="sudo apt update"
	(for creating shortcuts )

- exit & logout

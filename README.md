### backup_your_files
a program to backup your local files to a remote server in debian and ubuntu systems

backup version 1.0

### NAME
  backup - is a tool that is used to backup your data to a remote machine
**SYSNOPSIS**
	backup -b [src] [dest]
		
#### DESCRIPTION
	backup - is a linux program that is used to backup your files
      or directories to a remote machine  Note the program will delete files 
      that are in the remote destination but not in the source dir
**The remote server or machine is accessed using ssh One needs to have set ssh keys to access the server.**
##### Executing
To run the program just download and extract to your local machine...copy the backup file to your path
**NOTE:you must have a remote server and ssh must be installed on both machines**

*REPLACE THE USERNAME and IP WITH YOUR OWN at the line that uses rsync*

```
  USAGE
	 backup  src dest
	 backup --help
				 
	  - The src option specifies the directory to backup
		  The path must be the full path not relative
		  if no path is given the default path is taken as the
		  users home directory
	  - The dest option signifies the name the file will
     	  be saved with on the remote machine
    	  if not given the default is used which is 
     	  mybackup.tar.bz2

```

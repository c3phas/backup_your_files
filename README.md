# backup_your_files
a program to backup your local files to a remote server in debian and ubuntu systems

<pre>
backup version 1.0

<h3>NAME</h3>
  backup - is a tool that is used to backup your data to a remote machine
<b>SYSNOPSIS</b>
	backup -b [src] [dest]</pre>
		
<h4>DESCRIPTION</h4>
	<pre><p>backup - is a linux program that is used to backup your files
      or directories to a remote machine  Note the program will delete files 
      that are in the remote destination but not in the source dir</p></pre>
<b> The remote server or machine is accessed using ssh One needs to have set ssh keys to access the server.</b>
<h5>Executing</h5>
<p>To run the program just download and extract to your local machine...copy the backup file to your path</p>
<b>NOTE:you must have a remote server and ssh must be installed on both machines</b>

<b>REPLACE THE USERNAME and IP WITH YOUR OWN at the line that uses rsync</b>



<pre>
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

</pre>

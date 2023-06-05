# Final-Assignment-Operating-Systems

<h3>week 13 lab </h3>

The tar command creates tar files by converting a group of files into an archive. It also can extract tar archives, display a list of the files included in the archive, add additional files to an existing archive, and various other kinds of operations.

For example:      
Inside Documents directory, there are 2 files.    
<img width="907" alt="Screenshot 2023-06-05 at 4 53 54 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/2b4b8bba-1b2f-4d4c-ae17-7a33fe3d5b8c">

To create a tar archive, we use the -c option followed by -f and the name of the archive.
For example, to create an archive named archive.tar from the files named file1, file2, I would run the following command:    
<img width="1039" alt="Screenshot 2023-06-05 at 4 56 14 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/ff56572b-16d7-4a37-9086-d48476ff36ee">

Listing Tar Archives.   
When used with the --list (-t) option, the tar command lists the content of a tar archive without extracting it.   
The command below, will list the content of the archive.tar file:    
<img width="478" alt="Screenshot 2023-06-05 at 8 04 15 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/4eb00831-57f9-4448-8e91-5fc7a07f8ea6">

To extract a tar archive, we use the --extract (-x) option followed by the archive name.    
It is also common to add the -v option to print the names of the files being extracted.   
<img width="471" alt="Screenshot 2023-06-05 at 8 24 50 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/59f3951a-5038-4ab1-84bf-0117820216dc">


Extracting Tar Archive in a Different Directory.    
By default, tar will extract the archive contents in the current working directory . We use the --directory (-C) to extract archive files in a specific directory.    
For example, to extract the archive contents to the any directory, I can use the following command:   
<img width="751" alt="Screenshot 2023-06-05 at 8 31 24 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/b446b3eb-8ab3-45a8-bce3-b356623ce45f">

Creating Tar Gz Archive.    
Gzip is the most popular algorithm for compressing tar files. When compressing tar archives with gzip, the archive name should end with either tar.gz or tgz.    
Another popular algorithm for compressing tar files is bzip2. When using bzip2, the archive name should end with either tar.bz2.  
<img width="759" alt="Screenshot 2023-06-05 at 8 44 36 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/cb616dab-4777-41b4-936e-f854e118e390">

Extracting Tar Gz and Tar Bz2 Archives.   
When extracting compressed archives such as tar.gz or tar.bz2 , we do not have to specify a decompression option. The command is the same as when extracting tar archive.   
It is also common to add the -v option to print the names of the files being extracted.   
<img width="739" alt="Screenshot 2023-06-05 at 8 55 34 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/de60bd06-ad1e-4bee-9db1-440e16c1ccd7">



<br />
<br />

<h3>week 14 lab </h3>.  
By default, the ls command will print the name of all the files and directories only. To get the additional information and a cleaner view, we use the flag “-l”.       
<img width="601" alt="Screenshot 2023-06-05 at 9 08 05 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/f1ef061a-4f46-4f40-8cc1-51eacafbbadb">

<br />

The df command stands for “disk filesystem“; it’s used to get a full summary of available and used disk space usage of the file system.    
-h command is to be used to display it in human-readable format. 
<br />
<img width="1280" alt="Screenshot 2023-06-05 at 9 08 39 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/3c1aa11c-c5db-4f29-a80a-cb4da5855133">

<br />

Command du stands for Disk Usage. It is used to check the information of disk usage of files and directories on a system.   
Command du display a list of all the files along with their respective sizes.   
<img width="563" alt="Screenshot 2023-06-05 at 9 13 49 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/510777ba-090f-4e1c-aee2-31a6b8863a7d">

-h command is to be used to display it in human-readable format. 
<img width="569" alt="Screenshot 2023-06-05 at 9 14 26 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/de8b7cc1-b097-4a0c-a651-06c14b5d455f">

<br />
<br />

The mount command allows users to mount, i.e., attach additional child file systems to a particular mount point on the currently accessible file system. The command passes the mount instructions to the kernel, which completes the operation.   
The standard mount command syntax is:    

mount -t [type] [device] [dir].   

mount command without any options displays all currently mounted file systems. The output also displays the mount points and mount options.    
<img width="735" alt="Screenshot 2023-06-05 at 10 14 31 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/7878271b-9aac-41dc-b5d3-f99fb4b523f5">

The -t option allows users to specify which file systems to display when running the mount command. For example, to show only ext4 file systems, we run the following command:    
<img width="685" alt="Screenshot 2023-06-05 at 10 26 00 PM" src="https://github.com/abdulloh3835/Final-Assignment-Operating-Systems/assets/90837231/2c414ce5-1fa8-46b7-8e96-6123ea954116">









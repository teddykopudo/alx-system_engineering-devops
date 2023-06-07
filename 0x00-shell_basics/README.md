0-current_working_directory:absolute path name of the current working directory,pwd
1-listit:display contents of lists in current directory;ls
2-bring_me_home:changes the working directory to the user's home directory;cd ~
4-listmorefiles:Display current directory contents, including hidden files using the long format;ls -al
5-listfilesdigitonly:display current working directory in long format,hidden files and user and group ID's numerically;ls -lna
6-firstdirectory:make directory under /tmp/;mkdir /tmp/my_first_directory
7-movethatfile:move file from /tmp/betty to /tmp/my_first_directory;mv /tmp/betty /tmp/my_first_directory
8-firstdelete:delete betty from /tmp/my_first_directory/betty;rm /tmp/my_first_directory/betty
9-firstdirdeletion:delete directory my_first_directory under /tmp/;rmdir /tmp/my_first_directory
10-back:go back to  previous directory;cd -
11-lists:list all file in current directory,parent directory and /boot in that order;ls -la . .. /boot
12-file_type:prints type of file named iamafile in directory /tmp/;file /tmp/iamafile
13-symbolic_link:create a symbolic link under /bin/ls,named __ls__ in current directory;ln -s /bin/ls __ls__
14-copy_html:copies all HTML files from working directory to parent directory;cp -rua *.html ../
100-lets_move: move all files beginning with uppercase to directory /tmp/u
101-clean_emacs;deletes all files in current working directory that ends with ~;rm *~
102-tree:creates a directories welcome/to/school;mkdir -p welcome/to/school
103-commas:write a command that lists all the files and directories of current directory separated by comma;ls -map
school.mgmagic file that can be used with the command file to detect school data files;0 string SCHOOL School data;!:mime School

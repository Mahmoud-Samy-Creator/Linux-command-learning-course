Lesson (1) :- Intro
1- What's shell ?
2- What is bash ?
3- command syntax 
	command -optional -files
4- To know the currunt working directory: pwd
Lesson (2):- ls command 
1- To list in a long form: ls -l
2- To list out all files with hidden files: ls -a {for both (1,2) in 1 command, U can combine the flags: ls -al}
2.1: To list in a long sorted form: ls -lSti
3- To list a certain directory contents: ls /dir_name
4- To list out the contents of the root folder: ls /
5- To list out the contents of the currunt or home directory: ls ~ or ls
6- To list out the contents of a certain directory in a directory structure: ls dir1/dir2/di3
7- To list out the contents of 1 step bach directory: ls ..
8- To list out the contents of 2 steps bach directory: ls ../..
9- To list out files of a certain extension: ls *extention {ex: ls *.txt to list all text files}
	Same for listing in a directory: ls dir/*.txt
	Same for listing all files: ls *.*
10- To list out all the directories only: ls -d */
11- To list out all the directories with it's contents: ls -R

Lesson (3):- cd command (It's used to navigation among directories)
1- To navigate to a directory: cd dir 
2- To navigate to a directory through dir sructure: cd /dir1/dir2/dir3
3- To navigate to home: cd or cd ~ 
4- To navigate to parent of currunt directory: cd ..
5- To navigate back one step: cd -

Lesson (4):- cat command (Most frequantly used command, can display, edit, create files and even compine files content)
	*Syntax: cat -options file_name
1- To creat a file: cat file 
2- To diplay a file content: cat file1 file2 
3- To type content in a file: cat > file_name
4- To show the line number for a file content: cat -b file_name
5- To show the line number for a file content even the blank line : cat -n file_name
6- To dipalay content in a file with one line blank (shaped better): cat -s file_name
7- To display content in a file with "$" at the end of each line: cat -E file_name

Sixth (6):- mkdir command (for making directories)
1- For making a diredctory:- mkdir directory_name
2- For making a tree (a structure of a directory): mkdir -p home_dir/dir0/dir1
3- To make an array (a group) of directories inside one=e directory: mkdir -p homedir/{dir1,dir2,dir3}

Lesson (7):- rm and rmdir (for removing files and directories)
1- To remove a directory: rmdir directory_name
2- To remove a certian directory by structure: rmdir a/b/c/d
3- To remove a hole directory structure: rm -p a/b/c/d
4- To remove an unempty dirctory: rm -r dir_name
5- To remove a certain unempty directory by structure: rmdir -r a/b/c/d
6- To remove a file: rm file_name

Lesson (8):- 
1-  

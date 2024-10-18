* Shell Basics
* 0-current_working_directory: script that prints the absolute path name of the current working directory
* 1-listit: script to display the contents list of the current directory
* 10-back: script that changes the working directory to the previous one
* 11-lists: script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
* 12-file_type: script that prints the type of the file named iamafile in the /tmp directory when we will run your script
* 13-symbolic_link: script to create a symbolic link to /bin/ls, named __ls__
* 14-copy_html: script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
* 15-lets_move: script that moves all files beginning with an uppercase letter to the directory /tmp/u
* 16-clean_emacs: script that deletes all files in the current working directory that end with the character ~
* 17-tree: script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory
* 2-bring_me_home: script that changes the working directory to the home directory
* 3-listfiles: script list directory contents in a long format
* 4-listmorefiles: script list directory contents in a long format and hidden ones
* 5-listfilesdigitonly: script to display current directory contents, including hidden files in long format.
* 6-firstdirectory: script that creates a directory named my_first_directory in the /tmp/ directory
* 7-movethatfile: script to move the file betty from /tmp/ to /tmp/my_first_directory
* 8-firstdelete: script to delete the file betty
* 9-firstdirdeletion: script to delete the directory my_first_directory that is in the /tmp directory
* Shell Permissions
* 0. My name is Betty: script that switches the current user to the user betty
* 1-who_am_i: script that prints the effective username of the current user
* 2-groups: script that prints all the groups the current user is part of
* 3-new_owner: script that changes the owner of the file hello to the user betty
* 4-empty: script that creates an empty file called hello
* 5-execute: script that adds execution permission for owner to file hello
* 6-multiple_permissions: script that adds execution permission for owner and group and read for other users
* 7-everybody: script that adds execution permission for everyone for hello file
* 8-James_Bond: script that sets permission for hello file as owner none, group none, others users all
* 9-John_Doe: script that sets permissions for hello to -rwxr-x-wx
* 10-mirror_permissions: script that sets the permissions of hello to the same as olleh
* 11-directories_permissions: script to add execution permissions for all users to all subdirectories in the working directory, plus at the end executes these all at once
* 12-directory_permissions: script to add directory and set permissions at the same time
* 13-change_group: change group owner to school for hello
* 14-change_owner_and_group: change owner and group owner for all files and directories in the current directory
* 15-symbolic_link_permissions: change owner and group owner for symbolic link
* 16-if_only: script if owner of file of hello is guillaume change to vincent for hello
* Shell, I/O Redirections and filters
* 0-hello_world: script that prints Hello, World
* 1-confused_smiley: script that prints a confused smiley
* 2-hellofile: script that displays file contents
* 3-twofiles: script that displays the contents of two files
* 4-lastlines: script that prints the last 10 lines of a file
* 5-firstlines: script that prints the first 10 lines of a file
* 6-third_line: script that prints the third line of a file
* 7-file: script that prints a file name with special characters
* 8-cwd_state: script that lists all files and directories in long form including hidden and outputs to a file
* 9-duplicate_last_line: script that duplicates the last line
* 10-no_more_js: script that finds .js files, not directories, within the working directory and deletes them
* 11-directories: script that counts how many directories and subdirectories in the working directory 
* 12-newest_files: script that lists the 10 newest files
* 13-unique: script that prints a sorted list of lines that appear only once
* 14-findthatword: script that finds all occurences of a word in a file
* 15-countthatword: script that counts occurences of a word in a file
* 16-whatsnext: script that finds for a word in a file and prints the next 3 lines after it
* 17-hidethisword: script that prints lines that don't contain a specific word
* 18-letteronly: script that prints lines that start with a letter, capital or lowercase
* 19-AZ: script that translates certain letters to different letters
* 20-hiago: script that deletes lower and uppercase c
* 21-reverse: script that reverses text
* 22-users_and_homes: script that lists and sorts users and homes directories by cutting and selecting sections of info.
* Shell, init files, variables and expansions

* 0-alias: script that creates an alias
* 1-hello_you: script that prints hello user for current user
* 2-path: script that adds folder to the end of PATH
* 3-paths: script that counts how many directories in the PATH
* 4-global_variables: script that lists environment variables
* 5-local_variables: script that lists local and environment variables and functions
* 6-create_local_variable: script that creates local variable
* 7-create_global_variable: script that creates global variable
* 8-true_knowledge: script that prints the result of adding 128 to variable number
* 9-divide_and_rule: script that prints the result of POWER divided by DIVIDE
* 10-love_exponent_breath: script that prints the result of BREATH to the power of LOVE
* 11-binary_to_decimal: script that converts a number from base 2 to base 10  
* 12-combinations: script that prints all combinations of a-z starting with aa, sorted in a list and doesn't print oo
* 13-print_float: script that formats the var value with two decimal places only
* 14-decimal_to_hexadecimal: script that converts a var value from base 10 to base 16

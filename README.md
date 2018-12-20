# UnixPrograms

| Script Name                            | Purpose                                                                    |
| :----------------------                | :------------------------------------------------------------------------- |
| `append_file_contents_in_directory.sh` | To read files in a given directory and append contents                     |
| `arithmetic_operations.sh`             | To perform arithmetic operations using expr and bc                         |
| `count_of_file_and_folders.sh`         | To display count of files and folders                                      |
| `if_then_else.sh`                      | To demonstrate if-then-else                                                |
| `play_with_text_formatting.sh`         | To demonstrate different ways to print the text                            |
| `tput.sh`                              | To use tput to play around on the terminal                                 |
| `banner.sh`                            | To display the input text as a large banner                                |                         
| `check_file_directory_existence.sh`    | To check if file/directory exists and display its size/contents            |
| `check_file_permission_and_append.sh`  | To check if the user has write permission to file and append contents      |
| `string_operations.sh`                 | To perform operations on strings                                           |
| `logical_operations.sh`                | To perform logical operations                                              |
| `case_block.sh`                        | To demonstrate usage of case statement                                     |
| `case_block_advanced.sh`               | To demonstrate advanced usage of case statement                            |
| `loops.sh`                             | To demonstrate the usage of different kind of loops                        |





## Other useful commands
1. **/etc/passwd** - The password file that stores the user accounts information
   username:x(password is encrypted):userid:groupid:computername:homedir:defaultshell 
   
2. The encrypted passwords are stored in the **/etc/shadow** file.

3. **grep** To find a pattern of text in a file
```sh
grep -n -i -c <pattern> <file_name>
```
-i = ignores case sensitivity
-n = displays the line number of the matched occurrence in the file
-c = displays only the count of occurrences
-v = invert matches - shows all the lines that do not match the given pattern

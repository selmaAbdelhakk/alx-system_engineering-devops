# 0x02. Shell, I/O Redirections and filters
### 0. Hello World
A bash script that prints “Hello, World”, followed by a new line to the standard output.
### 1. Confused smiley
A bash script that displays a confused smiley "(Ôo)'.
### 2. Let's display a file
A command that display the content of the /etc/passwd file.
### 3. What about 2?
A command that display the content of /etc/passwd and /etc/hosts.
### 4. Last lines of a file
A command that display the last 10 lines of /etc/passwd.
### 5. I'd prefer the first ones actually
A command that display the first 10 lines of /etc/passwd.
### 6. Line #2
A bash script that displays the third line of the file iacta.
The file iacta will be in the working directory and you’re not allowed to use sed.
### 7. It is a good file that cuts iron without making a noise
A shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
### 8. Save current state of directory
A bash script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
### 9. Duplicate last line
Abash script that duplicates the last line of the file iacta.
The file iacta will be in the working directory.
### 10. No more javascript
A bash  script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
### 11. Don't just count your directories, make your directories count
A bash script that counts the number of directories and sub-directories in the current directory.
The current and parent directories should not be taken into account.
Hidden directories should be counted.
### 12. What’s new
A bash script that displays the 10 newest files in the current directory.
One file per line. Sorted from the newest to the oldest.
### 13. Being unique is better than being perfect 
A bash script that takes a list of words as input and prints only words that appear exactly once.
Input format: One line, one word. Output format: One line, one word and words should be sorted.
### 14. It must be in that file
A command that display lines containing the pattern “root” from the file /etc/passwd
### 15. Count that word
A command that display the number of lines that contain the pattern “bin” in the file /etc/passwd
### 16. What's next?
A command that display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
### 17. I hate bins
A command that display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
### 18. Letters only please
A command that display all lines of the file /etc/ssh/sshd_config starting with a letter include capital letters as well.
### 19. A to Z
A bash Replace all characters A and c from input to Z and e respectively.
### 20. Without C, you would live in hiago
A bash script that removes all letters c and C from input.
### 21. esreveR
A bash script that reverse its input.
### 22. DJ Cut Killer
A bash script that displays all users and their home directories, sorted by users.
Based on the the /etc/passwd file.
### 23. Empty casks make the most noise
A command that finds all empty files and directories in the current directory and all sub-directories.
Only the names of the files and directories should be displayed (not the entire path). Hidden files should be listed. One file name per line. The listing should end with a new line ans you are not allowed to use basename, grep, egrep, fgrep or rgrep.
### 24. A gif is worth ten thousand words
A bash script that lists all the files with a .gif extension in the current directory and all its sub-directories.
Hidden files should be listed. Only regular files (not directories) should be listed. The names of the files should be displayed without their extensions. The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay). One file name per line. The listing should end with a new line and you are not allowed to use basename, grep, egrep, fgrep or rgrep.
### 25. Acrostic
A bash script that decodes acrostics that use the first letter of each line.
The ‘decoded’ message has to end with a new line and you are not allowed to use grep, egrep, fgrep or rgrep.
### 26. The biggest fan
A bash script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
Order by number of requests, most active host or IP at the top And you are not allowed to use grep, egrep, fgrep or rgrep.

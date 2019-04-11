first see where your terminal is
currently navigated to,

`pwd`{{execute}}

 and to create the script using vim:

`vim my_first_script.sh`{{execute}}

To Start Writing inyo File

`i`{{execute}}

Start Writting content:

`echo "Hello world! This is my first Bash script!"`{{execute}}

The echo command can be used to print text to the console or into files, and the -n flag 
prints text without the end line character (end line has the same effect as pressing Enter on the keyboard)
— this allows the output from the whoami and pwd commands to appear on the same line.

The program also exits with a status of 0, which means that it exited with a normal status.
This will be covered later as we move toward searching or checking command exit statuses
for errors and other conditions.

`echo -n "I am executing the script with user: "
whoami
echo -n "I am currently running in the directory: "
pwd
exit 0
`{{execute}}

Click anywhere in Terminal screen and press ** Esc : w q ! ** to exit Vim

To execute your first script, enter the bash my_first_script.sh command and the
console will return a similar output:

`bash my_first_script.sh`{{execute}}


``{{execute}}

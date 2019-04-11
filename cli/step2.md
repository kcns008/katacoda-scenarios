first see where your terminal is
currently navigated to,

`pwd`{{execute}}

 and to create the script using vim:

`vim my_first_script.sh`{{execute}}

To Start Writing inyo File

`i`{{execute}}

Start Writting content:

`echo "Hello world! This is my first Bash script!"
echo -n "I am executing the script with user: "
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

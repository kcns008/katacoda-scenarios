Your first Bash script with Vim

first see where your terminal is
currently navigated to, and to create the script using vim:

`pwd`{{execute}}


`vim my_first_script.sh`{{execute}}

The terminal window will transform into the Vim application (similar to the following
screenshot) and you will be just about ready to program your first script. Simultaneously
press the Esc+ I keys to enter Insert mode; there will be an indicator in the bottom left and
the cursor block will begin to flash:


`#!/bin/bash
echo "Hello world! This is my first Bash script!"
echo -n "I am executing the script with user: "
whoami
echo -n "I am currently running in the directory: "
pwd
exit 0
`{{execute}}


``{{execute}}


``{{execute}}

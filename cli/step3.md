The best way to think of variables is as placeholders for values. They can be permanent
(static) or transient (dynamic), and they will have a concept called scope (more on this
later). To get ready to use variables, we need to think about the script you just
wrote: my_first_script.sh. In the script, we could have easily used variables to contain
values that are static (there every time) or dynamic ones created by running commands
every time the script is run. For example, if we would like to use a value such as the value
of PI (3.14), then we could use a variable like this short script snippet:

`PI=3.14`{{execute}}

Now Print PI vaulue

`echo "The value of PI is $PI"`{{execute}}

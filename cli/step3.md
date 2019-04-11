The best way to think of variables is as placeholders for values. They can be permanent
(static) or transient (dynamic), and they will have a concept called scope (more on this
later). To get ready to use variables, we need to think about the script you just
wrote: my_first_script.sh. In the script, we could have easily used variables to contain
values that are static (there every time) or dynamic ones created by running commands
every time the script is run. For example, if we would like to use a value such as the value
of PI (3.14), then we could use a variable like this short script snippet:

`PI=3.14`{{execute}}

Now Print PI vaulue $PI

`echo "The value of PI is $PI"`{{execute}}

Notice that the idea of setting a value (3.14) to a variable is called assignment.
We assigned the value of 3.14 to a variable with the name PI. We also referred to the PI
variable using $PI. This can be achieved in a number of ways:

Method 1:
`echo "1. The value of PI is $PI"`{{execute}}

Method 2:
`echo "2. The value of PI is ${PI}"`{{execute}}

Method 3:
`echo "3. The value of PI is" $PI`{{execute}}

While the output is identical, the mechanisms are slightly different. In version 1, we refer to
the PI variable within double quotes, which indicates a string (an array of characters). We
could also use single quotes, but this would make this a literal string. In version 2, we refer
to the variable inside of { } or squiggly brackets; this is useful for protecting the variable in
cases where this would break the script. The following is an example:

`echo "1. The value of PI is $PIabc"`{{execute}}

Since PIabc is not declared, it will be empty string

`echo "2. The value of PI is ${PI}"`{{execute}}

Still works because we correctly referred to PI

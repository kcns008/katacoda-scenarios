The previous section introduced the concept that there are several reserved words and a
number of characters that have an effect on the operation of Bash. The most basic, and
probably most widely used conditional logic is with if and else statements. Let's use an
example code snippet:

`#!/bin/bash
AGE=17
if [ ${AGE} -lt 18 ]; then
    echo "You must be 18 or older to see this movie"
fi`{{execute}}

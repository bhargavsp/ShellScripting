## SHELL COMMANDS


| command | usage | example command |
| :-----: | :-----: | :---: |
| apt install ksh | To install the new shell interpretor | |
| ps -p $$ or echo $SHELL or echo $0| to know the current shell we are using | |
| env or printenv | Displays the system defind variables on to the commnd prompt | env |
| echo $SHELL | To display the value of the SHELL system defind variable | |
| export HISTSIZE=200 | changes the system defined variables value | | 
| echo ${11} | used to print the 11th argument value, if given echo $11 it takes the 1st argument and appends by 1 | |
| echo $$ | to display the process ID | |
| echo $# | print number of arguments | |
| echo $* | will print all the arguments as one string | |
| echo $@ | will print each argument as one string | |
| echo $? | gives the execution status of the previous command | |
| echo ${#string_value} | to display the number of characters in a string | |
| echo ${string_value:20} | to ignore and display the first 20 characters in a string | |
| echo ${string_value:20:14} | to ignore first 20 characters and display the next coming 14 characters in a string | |
| echo ${string_value:} -8 | to display last 8 characters in a string | |


# ShellScripting

## why we need shell in devops?
1. Automate our regular jobs
2. taking database backups
3. Monitoring serveral server resources like CPU, memory utilizations
4. Portable, can be used in any unix-like OS


## file naming conventions
1. a file name can be maximum of 255 characters
2. name may contain alphabets, digits, dots and unerscores
3. system commands(ls, mkdir) or linux reserve words (if, fi, case, esac, fo, while, for, in) can not be used for the file names
4. file system is case sensitive (bob.sh and Bob.sh are different)

## single line comment and multi line comment
for the single line comment we use *#* for the multi line *<<anyekyword   samekeyword* no need to use >> at the end
Ex: <<hello hello

## variables
To display the variables value, just give the $ sign before the variable name
Ex: echo $SHELL

## How to see the system defind/ bash variables
we use the *env* or *printenv*. All the system defined varilables are uppercase
EX: *PWD* is a system defined variables, *pwd* it is a command

## command line arguments
If we are passing any values while running the shell script those values are called command lines arguments. To use the CL arguments inside the script we use $0, $1, $2
$# gives number of arguments from the Coomand Line
$* --> will print all the arguments as one string
$@ --> prints each arguments as one single string

## what is the standard error code for the command not found ?
127 is the error code output for the standard command not found 

## what happens if we give the echo $11, does it display the 11th argument?
it actually takes the 1st argument and append by 1. if we want the 11th argument to be printed we should give the echo ${11}.
output: 1stargument1

## conditions
![image](https://github.com/bhargavsp/ShellScripting/assets/45779321/8acc1333-d326-44d9-8f8a-9d9ef303a240)



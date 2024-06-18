## shell Q&A

## common shell script files we write for the devops automaticion?
cleanup.sh, deploy.sh, automatetask.sh, dbBackup.sh, serverresourcemonitor.sh

## what are the commands used by you for writing the shell scripting
free, df -h, top, mailm hostname, ifconfig

## why we need shell in devops?
1. Automate our regular jobs
2. taking database backups
3. Monitoring serveral server resources like CPU, memory utilizations
4. Portable, can be used in any unix-like OS

## what is shebang line
It is used to tell what shell we are using to execute the current program, otherwise the default is the *bash* 

## why we need to run the shell script in the debug mode?
When we are getting the erros while running in the normal mode, we are running the script in the debug mode. To run just use the -x option
command: sh -x first.sh

## how to run only some lines in the debug mode?
keep the lines in the script in between set -x and set +x. So the particular code is run in the debug mode
Ex: echo "hello"
set -x
echo "world"
set +x
echo "bhargav"

## when we give the set -x in the script and as well as when we execute the script in sh -X first.sh what happens?
the execution starts from the first line as we specified the -x while executing the program and stops the execution in debug mode at the end of the set +x
Ex:![image](https://github.com/bhargavsp/ShellScripting/assets/45779321/5dad295a-ad30-4791-8f96-3c02bbf6c632)


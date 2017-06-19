# utils

One-off scripts and tools

run _create_ to add chmod+x all and copy to /usr/local/bin

workflow:

* cp to /usr/local/bin
* sudo chmod +x _script name_
* Profit!

_create_ - add chmod+x all and copy to /usr/local/bin

_makegit_ - make a new repo on github. Create directory on local machine, cd to directory and execute this script to automatically generate and push new repo

_myip_ - returns your _external_ ip address

_xargs_template_ - a handy reference to remember how to use xargs quickly

_bash_profile_go_ - a .bash_profile file to add go to the path in OSX (create .bash_profile in ~ and add contents)

_gotour_ - starts the go tool tour

_aws_makecreds_ - creates AWS credentials from .cvs file downloaded from AWS Console, secure delete .cvs file

_aws_env_ - creates environment variables from AWS credentials file. **Note** must use execute using the _source_ command eg. _source ./aws_env_ This is because environment variables cannot be set by a script, because the script runs in it's own environment. _source_ ensures the script runs in the calling environment


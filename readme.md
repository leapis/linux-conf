hi

these are my personal scripts for doing various things

ssh_ : this is a replacement for standard ssh. I use an alias to completely overwrite the ssh command. It requires pass and sshpass to run properly. If the host is specified in gethost and the password is in getpass (stored in pass), it will use sshpass to login. Otherwise, it will default to the normal ssh command.

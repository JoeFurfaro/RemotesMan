# RemotesMan
RemotesMan makes dealing with remotes easy by managing your SCP and SSH credentials for you in a simple way

## Getting Started
To get started, clone the repository into a directory of your choice
```
git clone https://github.com/JoeFurfaro/RemotesMan
```
Make the script executable and navigate to the repository
```
chmod +x RemotesMan/remotesman
cd RemotesMan
```
Run a RemotesMan command using the standard syntax
```
./rsmn [command] [extra arguments]
```

## Commands
#### ./rsmn add [host ID] [host address] <user name>
Adds a remote host to the saved hosts list
#### ./rsmn del [host ID]
Deletes a host from the saved hosts list
#### ./rsmn list
Lists the saved remote hosts in a table format
#### ./rsmn ssh [host ID]
Initializes an SSH connection with the specified remote host  
#### ./rsmn scp [host ID] [local path] [target path]
Copies a local file to a remote location

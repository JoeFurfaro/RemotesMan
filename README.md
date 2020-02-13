# RemotesMan
RemotesMan makes dealing with remotes easy by managing your SCP and SSH credentials for you in a simple way.

## Getting Started
To get started, clone the repository into a directory of your choice.
```
git clone https://github.com/JoeFurfaro/RemotesMan
```
Make the script executable, navigate to the repository, and run the script.
```
chmod +x RemotesMan/remotesman
cd RemotesMan
./remotesman
```

## Commands
#### hosts
Displays a list of the available host IDs that the user has defined
#### addhost
Runs the setup wizard for adding a new remote host to save  
Inputs: New remote ID name, remote address, and user
#### delhost
Allows the user to delete a host ID that they previously created  
Inputs: Remote host ID
#### ssh
Initializes an SSH connection with the specified remote host  
Inputs: Remote host ID
#### scp
Performs an SCP action to a remote host  
Inputs: Local file path, remote host ID, remote file path
#### exit
Closes the RemotesMan interface

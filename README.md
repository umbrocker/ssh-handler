# SSH config handler with fzf
# This is a work still in progress!

## Requirements
`fzf` 
[https://github.com/junegunn/fzf](https://github.com/junegunn/fzf)

## Your ~/.ssh/config should look like this
```shell
Host yourhostname # description for your host
    HostName [domain/IP address]
    User [username]
    IdentityFile [your ssh key path] # this is optional
```

## Example
```shell
Host localhost # ssh login for my own machine
    HostName 127.0.0.1
    User root
```

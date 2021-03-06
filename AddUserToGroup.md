# Add user to group from command line (CMD)

### Introduction:
Windows provides command line utilities to manager user groups. In this post, learn how to use the command net localgroup to add user to a group from command prompt’
### Net User Command Syntax
```
net user [username [password | *] [/add] [options]] [/domain]] [username [/delete] [/domain]] [/help] [/?]
```

#### Add user to a group
```
net localgroup group_name UserLoginName /add
```
- Example: to add a user ‘John’ to administrators group
```
net localgroup administrators John /add
```
- To add a domain user to local users group:
```
net localgroup users domainname\username /add
```
- To add a user to remote desktop users group:
```
net localgroup "Remote Desktop Users" UserLoginName  /add
```
- to list all the users belonging to administrators group 
```
net localgroup administrators
```

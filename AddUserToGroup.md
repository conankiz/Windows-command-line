# Add user to group from command line (CMD)

### Introduction:
Windows provides command line utilities to manager user groups. In this post, learn how to use the command net localgroup to add user to a group from command prompt’
### Net User Command Syntax
net user [username [password | *] [/add] [options]] [/domain]] [username [/delete] [/domain]] [/help] [/?]
#### Add user to a group
net localgroup group_name UserLoginName /add

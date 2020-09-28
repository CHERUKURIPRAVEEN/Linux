## Linux Users
#### User Management
```
In Linux there are three types of users.
>> super or root user: adminstrator user.
>> system user: user having software and apllication permissions.
>> normal user: user created by root.
```

#### how to create linux user.
```
> when ever a user created in linux, below things happen by default.
>> A home directory is created (/home/<user name>).
>> unique UID & GID are given to user.
>> An entry in '/etc/passwd'
```
#### Examples
```
# useradd <user name>
>> Operations:
# -u user id
# -G secondary group id
# -g primary group id
# -d home directory
# -c comment
# -s shell
```
#### Checking user details
```
# id <user name>
# whoami <user name>
# cat /etc/passwd
# cat /etc/group
```

#### user permission

## LINUX MACHINE CONNECT

#### Using `config` file
Here Create config file in user .ssh directory.
After that add below commands.
```
Host <YourRefNmae>
    HostName <IP ADREESS>
    Port 22
    User <User Name>
    IdentityFile  ~/.ssh/id_rsa
    IdentitiesOnly yes 
```
Connect
```
ssh <YourRefNmae>
```

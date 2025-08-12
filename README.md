# warnSSH
This tool, created in bash, is used to signal that someone is attempting to connect to the SSH server (port 22).  

This monitoring tool can notify the server that someone has been connected in ssh, the IP address, the username and the time.  
This is managed with systemd, you can check with ```systemctl status warnssh.service```  

WarnSSH can notify you by just a pop-up in the server, but also by email using Postfix.

## INSTALLATION
To install this tool, you just need to do this commands :  
```chmod +x requirements```  
```sudo ./requirements```  

For Postfix, you have to insert your address mail and app password that you have to generated before, you can check this :  
https://support.google.com/mail/answer/185833?hl=en

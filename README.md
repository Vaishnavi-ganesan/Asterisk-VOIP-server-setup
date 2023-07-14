### Asterisk-VOIP-server-setup
Updating the system 
```
sudo  apt-get update 
```
Install Asterisk 
```
sudo  apt-get install asterisk –y 
```
Launch Asterisk 
```
sudo asterisk –r  
```
Edit the configuration files in /etc/asterisk. 
NB: Before editing, take backup of these files below.
```
sudo mv sip.conf sip.conf.backup
sudo mv extensions.conf extensions.conf.backup
sudo mv voicemail.conf voicemail.conf.backup
```
Configure the files:https://github.com/Vaishnavi-ganesan/Asterisk-VOIP-server-setup   
Launch the Asterisk 
```
sudo asterisk –r  
```
Reload Asterisk 
```
reload
```
Check whether clients are added or not 
```
sip  show peers
```
Linphone android client was installed in two android phone(Note:Both must be connected to same wifi) The username,password and sip domain was configured. And the call is made via linphone     
To check the status
```
sip show peers
```

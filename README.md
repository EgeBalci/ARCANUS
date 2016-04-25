# ARCANUS
ARCANUS is a customized payload generator/handler for penetration testing only.(Use at your own risk !).

For Assistance : arcanusframework@gmail.com


# WHY USE ARCANUS ?
  İn pen.test world Metasploit is the mainstream for this job, but ARCANUS has few advantages.
  
- ARCANUS generates a unique payload for windows and linux systems that can't be detected with any antivirus programs. (Don't give any samples to Virus Total or similar web sites to keep it that way ;D )

- It has extra modules for exploitation. Ordinary reverse shell payloads offers only remote access to command prompts but ARCANUS has few special commands like " £persistence, £download, £upload, £meterpreter..."

- It is silent and continuous. Metasploit payloads attempts to connect remote host just for ones but when you execute ARCANUS payloads they makes connection attemps every 5 second silently in background.

- It is flexible. If you want to use it with Metasploit it has a meterpreter module for executeing meterpreter shellcodes on remote machine.

- Platform independent ! ARCANUS works both on windows and linux.


# HOW TO USE 

- In order to build/compile  or run the go script you need to install golang and " fatih/color " package OR you can run the windows/linux binarys directy but you still need to install golang to your system inorder to compile ARCANUS payloads. 


It works same as every reverse shell but it has some special module commands.
(You can also use ARCANUS paylaods with netcat, but you can't execute special commands with netcat.)


https://www.youtube.com/watch?v=BXYqeTs5RIE

   
                                                                                                     
                                                                                                     
                                                                                                     
                                                                                                     
     [ COMMAND ]                                       [DESCRIPTION]                                 
                            
                                                                                                     
     (*) £METERPRETER -C:                              This command executes given powershell        
                                                         meterpreter shellcode for metasploit        
                                                          integration.                               
                                                                                                     
                                                                                                     
     (*) £PERSISTENCE:                                 This command installs a persistence module    
                                                         to remote computer for continious acces.    
                                                                                                     
                                                                                                     
     (*) £DISTRACT:                                   This command executes a fork bomb bat file to
                                                         distrackt the remote user.          
                                                                                                     
                                                                                                     
     (*) £UPLOAD -F "filename.exe":                    This command uploads a choosen file to        
                                                         remote computer via tcp socket stream.      
                                                                                                     
                                                                                                     
     (*) £UPLOAD -G "http://filepath/filename.exe":    This command uploads a choosen file to        
                                                         remote computer via http get method.        
                                                                                                     
                                                                                                     
     (*) £DOWNLOAD -F "filename.exe":                  This command download a choosen file          
                                                         from remote computer via tcp socket stream. 
                                                                                                     
                                                                                                     
     (*) £DOS -A \"www.site.com\":               This command starts a denial of service atack to      
                                                         given website address.            
                                                                                                     
                                                                                                     
     (*) £PLEASE "any command":                        This command asks users comfirmation for      
                                                         higher privilidge operations.               
                                                                                                     
                                                                                                     
     (*) £DESKTOP                                      This command adjusts remote desktop options   
                                                         for remote connection on target machine     
                                                                                                     
                                                                                                     
                                                                                                  
# ANTIVIRUS AWARENESS
  
  Please don't submit any payload samples to any antivirus sites or online forums. I will publish manual AV Scan detection scores continuously.
  
http://NoDistribute.com/result/0Hnrt8obNyp9PF7cZV6GTKXa5W1qI




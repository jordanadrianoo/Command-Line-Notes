# NMap Command lines

This section will keep track of helpful commands used throughout NMap hacking tool.

***Warning:*** NMap is an offical Hacking tool that must be used with the utmost caution. Intended use is meant for *Ethical* or *Green Hat* hackers. **Never Hack or Scan Without Permission.**

***Note:*** any command that starts with **press** will not have a command to type in the console, but instead, a combination of buttons that will be pressed together.
 
 # Installing NMap
 
 ## NMap Command Library 

|                commands  $                   |                           definition:                              |
|----------------------------------------------|--------------------------------------------------------------------|
|  Sudo apt-get install nmap                   |    Installs nmap through the console command                       |
|  man nmap                                    |    Displays the NMap Manual page                                   |
|  nmap --help                                 |    Displays the NMap Manual in the console                         |
|  ssh (username)@(Victim's ip)                |    Logs into victim's computer                                     |
|  nmap -v (Victim's ip)                       |    Scans victim's verbose output                                   |
|  Nmap -v =sV -O (Victim's ip)                |    Attempts to see what OS the user is using by sending packages   |
|  hostname -I                                 |    Only shows your Ip                                              |
|  sudo tcpdmp                                 |    Shows what the computer is connecting to                        |
|  sudo tcpdump -i enp0s3                      |    Shows what is connecting to the computer                        |
|  vim                                         |    dd to delte line i for insert u to undo y to copy p to paste    |
| dw to delete all in front of the cursor :q! to quit |
| sudo timeout $1                                 |    sets a timer to timeout a command                               |
|chmod +x Example_file  | sets file to execute |
|:wq saves and quits|
| sudo apt-get install fswatch| tool to watch ssh |
|metasploitable login: msfadmin passwords: msfadmin|
| shift + pageUp or shift + pageDown |
| sudo apt-get install curl|
| curl https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb > msfinstall && \
chmod 755 msfinstall && \
./msfinstall| installs metaspoit tools|


 ## Port Commands

|                commands  $                   |                           definition:                              |
|----------------------------------------------|--------------------------------------------------------------------|
|  sudo apt-get install openssh-server         |    Installs an open SSH Port on current computer                   |
|  ps-aux \| grep ssh                           |    Checks status of SSH Port                                       |


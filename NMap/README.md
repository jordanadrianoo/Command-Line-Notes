# NMap Command lines

This section will keep track of helpful commands used throughout NMap hacking tool.

***Warning:*** NMap is an offical Hacking tool that must be used with the utmost caution. Intended use is meant for *Ethical* or *Green Hat* hackers. **Never Hack or Scan Without Permission.**

***Note:*** any command that starts with **press** will not have a command to type in the console, but instead, a combination of buttons that will be pressed together.
 
 ## General Commands

|                commands  $                   |                           definition:                              |
|----------------------------------------------|--------------------------------------------------------------------|
|  Sudo apt-get install nmap                   |    Installs nmap through the console command                       |
|  man nmap                                    |    Displays the NMap Manual page                                   |
|  nmap --help                                 |    Displays the NMap Manual in the console                         |
|  ssh (username)@(Victim's ip)                |    Logs into victim's computer                                     |
|  nmap -v (Victim's ip)                       |    Scans victim's verbose output                                   |
|  Nmap -v =sV -O (Victim's ip)                |    Attempts to see what OS the user is using by sending packages   |

 ## Port Commands

|                commands  $                   |                           definition:                              |
|----------------------------------------------|--------------------------------------------------------------------|
|  sudo apt-get install openssh-server         |    Installs an open SSH Port on current computer                   |
|  ps-aux \| grep ssh                           |    Checks status of SSH Port                                       |


# Linux Commands Recap



 - [ ] Commands Structure and man pages

  - [ ] [sudo] command [-options] [arguments]
  - [ ] man command

- [ ] File System Navigation

  - [ ] pwd
  - [ ] ls
  - [ ] cd
  - [ ] mkdir
  - [ ] mv      -> rename , cut
  - [ ] cp 
  - [ ] rm -r   -> remove recursively 


- [ ]  Text File Manipulation

  - [ ] touch
  - [ ] cat
  - [ ] nano/vim/subl
  - [ ] echo
  - [ ] rm
  - [ ] file
  - [ ] redirection
  - [ ] piping
  - [ ] grep
  - [ ] find
  - [ ] locate
  - [ ] head    -> prints the first 10 lines by default 
  - [ ] tail        -> prints the last 10 lines by default


- [ ] Users

   - [ ] id -> displays the details of the active user e.g. uid, gid, groups
   - [ ] adduser "name"
   - [ ] su <username>
   - [ ] groupadd "name"
   - [ ] userdel "name"
   - [ ] last -> shows the last logins in the system
   - [ ] who -> who is logged in

- [ ] Files Permissions

  - [ ] chmod 
  - [ ] chown
  
- [ ] Package Manager

    - [ ] apt/yum/pacman/..
    - [ ] sudo apt install <package>
    - [ ] sudo apt update -> updates all the packages 
    - [ ] sudo apt-cache search <package> -> search if a package exists
    - [ ] sudo apt-cache show <package> -> detailed info about the package  ex: firefox
    - [ ] sudo apt remove <package> -> removes an installed package

- [ ] Processes
  - [ ] ps
  - [ ] top
  - [ ] kill <pid>
  - [ ] killall <pname>


- [ ] Networking

  - [ ] hostname -i -> displays local ip address 
  - [ ]  ifconfig -> display IP addresses of all network interfaces
  - [ ] ping <host> -> send packets to test if the there is a connection
  - [ ] wget <file URL> -> downloads a file from online source
  - [ ] host <domain> -> performs IP lookup on a domain
  - [ ] nslookup <domain> -> retrieves DNS info about the domain 
  - [ ] nmap <host> -> scans a host for open ports
  - [ ] nmap <host> | grep <port> -> displays what service works on a specific port

  - SSH
    - [ ] ssh <username>@<host> -p <port>  -> securely connect to host as user - default port is 22
    - [ ] scp <file> <server>/<path> -> securely copy <file> in <path> in the <server>
	
  ### SSH Example
  - Connect using ssh with theese info.
  host: **bandit.labs.overthewire.org**
  port: **2220**  
  username: **bandit0**  
  pass: **bandit0**
	```bash
	ssh bandit0@bandit.labs.overthewire.org -p 2220
	```


# Help Commands 📚
You can use help commands to get information about a command or its usage. There are many ways to do so.

## -h or --help
This gives you help about a command's **USAGE** which is different from the `help []` command.
```
hamza@HM0PC:~$ apt --help
apt
Usage: apt command [options]
       apt help command [options]

Commands:
  add-repository   - Add entries to apt sources.list
  autoclean        - Erase old downloaded archive files
  autoremove       - Remove automatically all unused packages
...
```

## help
Gives help about a command.
```
hamza@HM0PC:~$ help cd
cd: cd [-L|[-P [-e]] [-@]] [dir]
    Change the shell working directory.
    
    Change the current directory to DIR.  The default DIR is the value of the
    HOME shell variable.
...
```

## man
Shows a manual page for a command.
```
hamza@HM0PC:~$ man sudo
```

## apropos
Search for anything and get a related command.
```
hamza@HM0PC:~$ apropos admin
arptables-nft (8)    - ARP table administration (nft-based)
ebtables-nft (8)     - Ethernet bridge frame table administration (nft-based)
gpasswd (1)          - administer /etc/group and /etc/gshadow
...
```

## whatis
A brief description of a command. Similar to an apropos result.
```
hamza@HM0PC:~$ whatis sudo
sudo (8)             - execute a command as another user
```

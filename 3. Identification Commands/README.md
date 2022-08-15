# Identification Commands 🗃️
You can use Identification Commands to identify or get info about things on your system.

## whoami
Tells you your username!

## neofetch
Shows the Distro name with an ASCII image and some system specs.
```
hamza@HM0PC:~$ neofetch
             ...-:::::-...                 hamza@HM0PC 
          .-MMMMMMMMMMMMMMM-.              ----------- 
      .-MMMM`..-:::::::-..`MMMM-.          OS: Linux Mint 20.2 x86_64 
    .:MMMM.:MMMMMMMMMMMMMMM:.MMMM:.        Host: HP EliteBook 840 G1 A3008FD10B 
   -MMM-M---MMMMMMMMMMMMMMMMMMM.MMM-       Kernel: 5.4.0-122-generic 
 `:MMM:MM`  :MMMM:....::-...-MMMM:MMM:`    Uptime: 13 mins 
 :MMM:MMM`  :MM:`  ``    ``  `:MMM:MMM:    Packages: 2392 (dpkg), 7 (flatpak) 
.MMM.MMMM`  :MM.  -MM.  .MM-  `MMMM.MMM.   Shell: bash 5.0.17 
:MMM:MMMM`  :MM.  -MM-  .MM:  `MMMM-MMM:   Resolution: 1600x900 
:MMM:MMMM`  :MM.  -MM-  .MM:  `MMMM:MMM:   DE: Cinnamon 
:MMM:MMMM`  :MM.  -MM-  .MM:  `MMMM-MMM:   WM: Mutter (Muffin) 
.MMM.MMMM`  :MM:--:MM:--:MM:  `MMMM.MMM.   WM Theme: Mint-Y-Dark (Mint-Y-Dark) 
 :MMM:MMM-  `-MMMMMMMMMMMM-`  -MMM-MMM:    Theme: Mint-Y-Dark [GTK2/3] 
  :MMM:MMM:`                `:MMM:MMM:     Icons: Mint-Y-Dark [GTK2/3] 
   .MMM.MMMM:--------------:MMMM.MMM.      Terminal: gnome-terminal 
     '-MMMM.-MMMMMMMMMMMMMMM-.MMMM-'       CPU: Intel i5-4200U (4) @ 2.600GHz 
       '.-MMMM``--:::::--``MMMM-.'         GPU: Intel Haswell-ULT 
            '-MMMMMMMMMMMMM-'              Memory: 1755MiB / 15811MiB 
               ``-:::::-``
```
You can also use `neofetch --ascii_distro` to change the ASCII image to another distro (Example: `neofetch --ascii_distro Arch`).

## id
Tells you all about you, including the groups you are in.
```
hamza@HM0PC:~$ id
uid=1000(hamza) gid=1000(hamza) groups=1000(hamza),4(adm),24(cdrom),27(sudo),30(dip),46(plugdev),114(lpadmin),134(sambashare)
```

## hostname
Gives you the name of the host computer.

## df
Shows the current amount of free space on your disk drives.
```
hamza@HM0PC:~$ df
Filesystem     1K-blocks     Used Available Use% Mounted on
udev             8048140        0   8048140   0% /dev
tmpfs            1619140     1724   1617416   1% /run
/dev/sda6       28811292 15238336  12084060  56% /
tmpfs            8095700   115232   7980468   2% /dev/shm
tmpfs               5120        4      5116   1% /run/lock
tmpfs            8095700        0   8095700   0% /sys/fs/cgroup
tmpfs            1619140       24   1619116   1% /run/user/1000
/dev/sda5       68444156 30587220  37856936  45% /media/hamza/Personal Folders
```

## free
Displays the amount of free memory (RAM/Swap/Cache).
```
hamza@HM0PC:~$ free
              total        used        free      shared  buff/cache   available
Mem:       16191400     1465724    13138644      333216     1587032    14098184
Swap:       1999868           0     1999868
```

## which
Tells you the location of the command you just typed (stored as a file).
```
hamza@HM0PC:~$ which sudo
/usr/bin/sudo
```

## type
Tells you the command's type. There are 4 types of commands: **Executable Programs, Shell Builtin, Shell Function, and Aliased Commands**.
```
hamza@HM0PC:~$ type ls
ls is aliased to `ls --color=auto'
```

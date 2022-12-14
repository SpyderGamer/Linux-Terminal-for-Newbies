# Get to Know Your Workspace 🖥️
This is basically a small introduction about things you need to know before getting into the terminal. The command line is a tool that communicates with the shell, and the shell is a program that takes in keyboard inputs and passes them over to the OS to carry out the task. When we launch our terminal, we see something that looks like this:
```
hamza@HM0PC:~$ 
```
This is the shell prompt waiting for an input.

# Linux Things you Have to Know 🐧️
1. So there is this concept in Linux that "Everything is a file" Which is true, because if you see a directory such as `/usr/bin`, all the commands there are stored as files.
2. A dollar sign **($)** indicates that you are using **normal user privileges** and a hashtag **(#)** shows that you are using **root privileges**. Root is like being Admin in Windows. To login as root, use this command:
```
hamza@HM0PC:~$ sudo su -
```
3. **~** is the shortcut for the home directory (Example: /home/hamza). You can type: "~" to see your home folder!
4. **"."** is the **current working directory**, and **".."** is the **working directory's parent directory**. We will get to see how we can use these later on.
5. It is possible to include multiple commands on one line. **(Example: `command1; command2; command3`)**.
6. It is possible to integrate a command's output as a parameter **(Example: `cat $(which sudo)`)**. Here, the output command of `which sudo` is is the parameter of `cat`. We are basically running `cat /usr/bin/sudo`.
7. **/home** contains all users' folders. Which holds things like: Config files, Documents, Pictures, etc. It is equivalent to **C:\Users** in Windows.

# Keyboard Shortcuts ⌨
- Opening a Terminal Window: **Ctrl + Alt + T**.
- Switching to TTY Mode (Which is a Full Command Line Interface with No Desktop Environment): **Ctrl + Alt + F1** to **Ctrl + Alt + F6**.
- Returning Back to the Graphical Desktop: **Ctrl + Alt + F7**.

# Example 💻️
Locating your home directory:
```
hamza@HM0PC:~$ ~
bash: /home/hamza: Is a directory
```

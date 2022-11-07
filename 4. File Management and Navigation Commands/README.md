# File Management and Navigation Commands 📁
These commands help you manipulate and navigate your files. Delete, view, or even edit your file through the command line! Play around with some files and understand what each command does.

## ls
List files in the current/chosen directory. This command has multiple parameters such as:
- `ls -a`: Show hidden directories and files.
- `ls -l`: Output in more detail such as permissions and file owner.
- Parameters can also be combined: `ls -la`.
- There are much more parameters, but these are the essential ones.

You can view multiple directories at once `ls /usr /lost+found`.

## file
Displays what chosen file contains.
```
hamza@HM0PC:~$ file .bashrc
.bashrc: ASCII text
```

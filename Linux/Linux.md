## What is Linux?
Linux is an open source operating system. Just like other operating system (Windows, Mac OS and Android  etc.). An operating system is software that manages all of the hardware resourcess associated with your desktop or laptop.

## what is Shell?
 A shell is user interface or an environment for accessing operating system services. Using shell we can run our command, program and shell script.

### Type of shell 
- There are two type of shell.
    ### 1. Command line shell
    - Command line shell require the user to enter text command to excecute specific program. For Example
      - Bash (the default shell for Linux and macOS)
      - DOS
      - cmd.exe (the default shell for Windows)
    ### 2. Graphical shell (GUI)
    - Graphical shells provide a GUI for interacting with the operating system. For Example
      - macOS Finder
      - Windows Explorer
      - GNOME Shell (the default shell for GNOME desktop environment)
      - KDE Plasma (the default shell for KDE Plasma desktop environment)

## Linux Commands

1. `whereis` - Find the path of an executable file.

2. `man <command_name>` - Get information about a command.

3. List command:
   - `ls` - Show all the files and folders under a specific folder/directory.
   - `ls -a` - Show all the file/folder including hidden files.
   - `ls -al` - Show all the file/folder including hidden files with detailed information.
   - `ls -R` - Show all the file/folder in a directory and its subdirectory recursively.

4. pwd (Print Working Directory)
   - `pwd` - It's print current working directory

5. cd (Change Directory):
   - `cd <folder_name>` - Go to a specific folder/directory.
   - `cd .` - Go to the present directory.
   - `cd ..` - Go to the previous directory.

6. cat (Concatenate or Display Files):
   - `cat <file_name>` - Read/display the data of a file.
   - `cat > <file_name>` - Create a new file.
   - `cat <file1> <file2> > <file3>` - Concatenate multiple files together.
   - `cat <file1> | tr a-z A-Z > <file2>` - Translate file1 data to uppercase and insert into file2.

7. man (Manual):
   - `man <command_name>` - Get information about a command.

8. mkdir (Make Directory) 
   - `mkdir <folder_name>` - use to create new folder/directory

9.  touch (Create New File) 
    - `touch <file_name>` - user to create empty new file

10. cp (Copy Command) -
    - `cp <file_name> <destination>` - use to Copy a file.
   
11. man (use to give info about any command)
   
       - `man <command_name> ` - it's give the info about commands
   
12. tr  (use to translate or delete the character)

       - `cat <file1> | tr a-z A-Z > <file2> ` - it's traslate file1 data to upper case and insert into file2
    
13. mv ( move or rename file/directory)
    
    - `mv <source_file> <destination_file>` - its move to destination file
    
    - `mv <source_file> <new_file> ` - its rename the files
14. rm (remove file)
    - `rm file_name` - remove files
      -  `-r` - Recursively delete directories and their contents.
      -  `-f` - Forcefully delete files without asking.
      -  `-i` - Prompt before deleting each file.
      -  `-l` - Prompt only once before deleting multiple files.
      -  `-v` - Verbosely list the files that are being deleted.
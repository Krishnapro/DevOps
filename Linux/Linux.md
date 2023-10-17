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
1. List command
   
   ```
   ls -> show all the files and folders under a specific folder/directory
   ```
   ```
   ls -a -> show all the file/folder including hidden files
   ```
   ```
   ls -al -> show all the file/folder including hidden files with details information
   ```
   ```
   ls -R -> show all the file/folder in a directory and its subdirectory recursively
   ```

2. pwd (Print Working Directory)
   ``` 
   pwd ->  It's print current working directory
   ```
3. cd ( Change Directory)
   ```
   cd <folder_name> -> go to under specific folder/directory
   ```
   ```
   cd . -> single(.) means present directory
   ```
   ```
   cd .. -> double(..) means previous diretory
   ```
4. cat (use to concatenate or display files)
   ```
   cat <file_name> -> Read/display data of file
   ```
   ```
   cat > <file_name> -> use to create new file
   ```
   ```
   cat <file1> <file2> > <file3> -> it's use to concate multiple file together(i.e- concate file1 and file2 into file3)
   ```
   ```
   cat <file1> | tr a-z A-Z > <file2> ->
   ```
5. man (use to give info about any command)
   ```
    man <command_name> -> it's give the info about commands
   ```
6. tr  (use to translate or delete the character)
   ```
   cat <file1> | tr a-z A-Z > <file2> -> it's traslate file1 data to upper case and insert into file2
   ```
7. mkdir (make directory)
   ```
   mkdir <folder_name> -> use to create new folder/directory
   ```
   
8. touch (crate new file)
   ```
   touch <file_name> -> user to create empty new file
   ```
9. cp (copy command)
    ```
    cp <file_name> <destination> -> use to copy file
    ```
10. mv ( move or rename file/directory)
    ```
    mv <source_file> <destination_file> - its move to destination file
    ```
    ```
    mv <source_file> <new_file> -> its rename the files
    ```
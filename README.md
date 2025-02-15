# Linux for the Sega Genesis, Game Boy, SNES, NES & Atari 2600 & GameCube (v0.1)
Linux for Sega Genesis/Mega Drive & SNES
I did this using SGDK!
# Essential Commands for the Mega Drive Linux

This is a list of essential commands for the custom Linux system running on the Mega Drive. Due to hardware limitations, the system supports a minimal set of commands, which can be used to interact with the system.

## Available Commands

### 1. `help`
Displays a list of available commands or provides brief information about a specific command.
- Example: `help` or `help ls`

### 2. `ls`
Lists the files and directories in the current directory.
- Example: `ls`

### 3. `cd`
Changes the current working directory.
- Example: `cd /home`
- ### 3. `startx`
Enter to the GUI.
- Example: `startx`

### 4. `pwd`
Displays the absolute path of the current directory.
- Example: `pwd`

### 5. `cat`
Displays the content of text files.
- Example: `cat file.txt`

### 6. `echo`
Prints a line of text or a variable to the terminal.
- Example: `echo "Welcome to Mega Linux!"`

### 7. `mkdir`
Creates a new directory.
- Example: `mkdir new_data`

### 8. `rmdir`
Removes an empty directory.
- Example: `rmdir old_data`

### 9. `rm`
Removes files.
- Example: `rm file.txt`

### 10. `cp`
Copies files or directories.
- Example: `cp file.txt /home/user/`

### 11. `mv`
Moves or renames files and directories.
- Example: `mv file.txt /home/user/new_name.txt`

### 12. `clear`
Clears the terminal screen.
- Example: `clear`

### 13. `date`
Displays the current date and time.
- Example: `date`

### 14. `shutdown`
Shuts down or reboots the system.
- Example: `shutdown -h now`

### 15. `reboot`
Reboots the system.
- Example: `reboot`

### 16. `touch`
Creates an empty file or modifies the timestamp of an existing file.
- Example: `touch new_file.txt`

### 17. `mount`
Mounts storage devices (such as external disks or cartridges).
- Example: `mount /dev/sda1 /mnt`

### 18. `unmount`
Unmounts a storage device.
- Example: `unmount /mnt`

### 19. `man`
Displays the manual for a command (if implemented).
- Example: `man ls`

### 20. `exit`
Exits the terminal or shell.
- Example: `exit`

## Considerations for Implementation

- **Simple and Basic**: The goal is to have a minimal set of tools for basic interaction. Advanced commands are not included at this stage.
- **Hardware Adaptation**: Due to the Mega Drive's limited resources, the implementation of these commands should be efficient with minimal overhead.
- **File System**: The Mega Drive does not have a modern file system, so a simple file structure or simulated file system is required.
- **Interactivity**: Commands like `echo`, `cat`, and `ls` provide basic terminal interactivity.
- **Gradual Expansion**: Start with these basic commands, and expand as the system evolves to include more complex features.

This set of commands provides a basic command-line interface to interact with the Mega Drive's Linux system.
Button A: Advances to the next letter (circular, from a to z).
Button B: Adds the letter to the command.
Button C: Deletes the last letter.
Start Button: Executes the command or confirms the input.
All the same commands for the SNES, Game Boy, NES, Atari 2600 are the same as the Mega Drive | Genesis

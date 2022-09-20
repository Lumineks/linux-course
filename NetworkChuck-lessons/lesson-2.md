# NetworkChuck course. Lesson 1

## Video course - https://youtu.be/A3G-3hp88mo

## Commands:

These commands are files that are located in /bin folder.

1. `whoami`

Prints current user name.

2. `cat <filename>` - stands for 'concatenate'

Prints file content.

3. `cp <filename> <new_filename>` - stands for 'copy'

Copies speciefied file and sets specified new filenmae.

4. `sudo <command>` - stands for 'super user do'

Grants permissions of the root user for the specified command execution.

5. `rm <filename>` - stands for 'remove'

Removes specified file

6. `sudo adduser <username>` - special admin command, located in the /sbin folder (super bin).

Adds new user with specified name and other params

7. `which <command>`

Prints where specified command's binary file is located in the system.

## File system

1. 'bin' folder - contains essential binary commands-files which let us execute them (command) by using filename.
   Each command from above is a file located in the bin directory.

2. 'sbin' folder - stands for 'super bin' and contains special administrator binary files commands that are primary used by the administrators to admin the machine. All commands from this folder are going to need 'sudo' permission

3. 'home/<username>' - home directory for existing machine users, can contain any user-related files.

4. 'usr' - In the usr folder there are 'bin' and 'sbin' dirs too, as in the root of the file system. They contains almost the same files as root folders, but usually there are some commands present which we cannot find in the root bin/sbin folders

There is 'local' folder as well where commands-binary files are located, but these are the commands which we as a users can create.

'lib' folder holds shared files that can be used elsewhere.

5. 'boot' folder - contains files required for system boot.

6. 'var' folder - contains log files and web-application related files

7. 'tmp' folder - contains temporary files, usually deleted at system start/close.

8. 'lib' folder - shared library, files needed to system boot and other proccesses to work.

9. 'root' folder - root user folder.

10. 'dev' folder - stands for devices. Holds devices binary files.

11. 'etc' folder - stands for etcetera. Contains system and applications config files, like settings and so on. 

12. 'mnt' and 'media' folders - media: mount drives like usb flash cards. mnt: mount something manually, by hand.  
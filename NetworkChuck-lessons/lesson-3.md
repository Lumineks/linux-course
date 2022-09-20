# NetworkChuck course. Lesson 3

## Video lesson - https://youtu.be/Y17KTiJLcyQ

## Linux terminal

Word 'terminal' used in a meaning of a GUI application where we execute commands is actually just a convention, the right word for this kind of applications is a 'terminal emulator'. What is terminal then? Originally, 'terminal' is a device that has a monitor and keyboard. Thats what people used back in the past, 1980s particularly. And now we do not need to use one thanks to having terminal emulators. Terminal gives us access to commands used to iteract with the computer. And diving more into terminology, terminal executes out commands, but the actual GUI application is called 'Shell'. Examples are 'bash', 'zsh', 'bat' and so on . We can find out what shell we are currently using by running 'ps' command (docs below).

## Terminal line

In the terminal we usually see the next format: <username@hostname>-[<location>]$

- '$' means that we are currently logged in a terminal as a user.
- '#' means that we are currently logged in a terminal as a root user.

## Commands

0. `man <command>` or `<command --help/-h>` - stands for 'manual', help simply for 'help')

0.1. `apropos <description>`

Searches suitable command's names based on provided description. That's a must when we forget command we want to use, but we can describe what one should do. Just do not forget apropos command :)

Prints command's documentation.

1. `ps` - stands for 'process status'.

Prints proccesses and their statuses.

2. `id` - prints current user id.

3. `hostname` - prints hostname

4. `uname <flags>` - prints system info based on provided flags, see --help to get to know about it's flags

5. `ifconfig`, `ip`, `netstat` - prints network info.

6. `ss` - prints sessions status

7. `who` - prints users who logged in to current machine

8. `env` - prints env variables

9. `lsblk` - stands for list blocks, prints some harware info.

10. `lsusb` - stands for list usb, prints plugged in usbs.
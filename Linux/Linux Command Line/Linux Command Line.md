# Linux Command Line

## What is Command Line Interface
Text based interface which allows us to interact with programs using text commands.

## What is Shell?
Software that is used to work with command lines. Also called command-line interpreter. Bash is one of the most commonly used Shell.

Shell is the software that accepts & runs those commands & terminal emulator/command line interface is the software the shell runs inside of. 

## General Command Syntax
*Command 	option(s) 	argument(s)*

Examples:
  - ls -lh /usr/bin
  - sort -u users.txt
  - grep -i “needle” haystack
  - apropos “search”

Commands are the programs that are used to perform operation. Options tell the command how to operate. Arguments tell the command what to operate on.

Finding help for commands:
  - Manual Pages (man): built-in documentation for commands. Example “man ls”.
  - Commands also have option called help, provides brief information. Example “ls --help".
  - apropos: search command using keyword that can match description. Example “apropos list”.

## Linux File System
Most Linux distributions follows, Filesystem Hierarchy Standard (FHS), a standard which define where certain kind of files are stored on the file system. Having files like configurations, programs, or binaries and so on in predictable locations is important for the operability of software across Linux distributions.

The file system starts with the root represented by a slash (/). It is the highest level of the organizational hierarchy of the file system. Each Linux system only has one file system and everything else directories, external hard drives, network shares, and so on are represented within it.

At the next level down the hierarchy, there are set of specific folders, defined by the Filesystem Hierarchy Standard. 
  - The **home** directory is where each user has separate personal accounts & files stored.
  - The etc directory is where each user keep their configuration files.
  - The **bin & sbin** directory is used to store programs which is required by system for operating.
  - The lib directory is where shared libraries & modules are stored.
  - The **mnt** directory is where local & network file systems are mounted into the overall file system.
  - The **media** directory is where removable file systems like USB drives & optical drives are mounted. 
  - The **dev** folder (device) is where system keeps references to all of the hardware it has hard drives, memory, CPU's, and everything else.
  - The **proc** directory, which contains references to processes that are running on the system. And this directory contains details on other aspects of the system as well. 
  - The **sys** directory, which holds files representing different kernel parameters and system information.









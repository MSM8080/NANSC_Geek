# Things that was mentioned during the session
---
## Topics
- archiving & compressing
- filesystem hirarechy 
- tar extraxting path
- wild cards: {}
- bash shell scripting
- permissions bits
- disks types
---
## Commands 
- `$ tar`           # archiving files
- `$ whoami`        # print current user name
- `$ id`             # print users & groups id
- `$ su`             # run command with speciefc user / group 
- `$ groupadd`       # creat new group
- `$ chmod`          # change file permissions
- `$ chown`         # change owener user of the file
- `$ chgrp`          # change owener group of the file
- `$ ls`             # list content of directory
- `$ df`             # size of file system space
- `$ find`           # search for files
- `$ free`           # display free / used amount of memory


## Command with options
- `$ tar -c`    # create archive
- `$ tar -f`    # name the archive
- `$ tar -t`    # display archive content
- `$ tar -x`    # extract archive content here
- `$ tar -z`    # compressing algorithm {.gz}
- `$ tar -J`    # compressing algorithem {.xz}
- `$ tar -C`    # change directory path of archiving
- `$ tar -h`    # follow symbolic links to archive & compress original files

- `$ su -`      # login as default user: {root}

- `$ ls -R`      # list content of directory & subdirectory {recursively}
- `$ df -h`     # size of file system space in human-readable format

- `$ du -h --max-depth=1`    # disk usage of files {human-readable size} in directory but not files in subdirectories

- `$ find -exec`    # execute what is found by another command

- `$ free -m`       # display memeory size in megabytes
- `$ free -g`       # display memeory size in gigabytes
- `$ free -h`       # display memeory size in human-readable foramt


## complex commands expressions
- `$ rm dir/{file_1.txt,file_2.txt}`     # delete 2 files

- `$ sudo chown user:group file`        # change both owener group & user

- `$ find /home/msm/Downlods -mtime +30 -exec rm {}`    # delete all files it founds that was older than 30 dayes


## files extensions
- .tar  # tar archive extension
- .gz   # z algorithem extension
- .xz   # J algorithem extension


## file systems
- ext4      # timestamp is a feature in this filesystem


## files
- /etc/sudoers.d    # configuration file for users that can use sudo command


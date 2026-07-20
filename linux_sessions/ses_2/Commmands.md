# Things that was mentioned during the session

## Topics
    - archiving & compressing
    - filesystem hirarechy 
    - tar extraxting path
    - wild cards: {}
    - bash shell scripting
    - permissions bits
    - disks types


## Commands 
    $ tar
    $ whoami
    $ id 
    $ su
    $ groupadd
    $ chmod
    $ chown
    $ chgrp
    $ ls
    $ df
    $ find
    $ free

    
## Command with options
    $ tar -c    # create archive
    $ tar -f    # name the archive
    $ tar -t    # display archive content
    $ tar -x    # extract archive content here
    $ tar -z    # compressing algorithm
    $ tar -J    # compressing algorithem
    $ tar -C    # change directory
    $ tar -h    # follow symbolic links to archive & compress original files

    $ su -
    
    $ ls -R

    $ df -h

    $ du -h --max-depth=1

    $ find -exec    # execute what is found by another command

    $ free -m       # display memeory size in megabytes
    $ free -g       # display memeory size in gigabytes
    $ free -h       # display memeory size in human-readable foramt

## complex commands expressions
    $ rm dir/{file_1.txt,file_2.txt}     # delete 2 files

    $ sudo chown user:group file
    
    $ find /home/msm/Downlods -mtime +30 -exec rm {}

## files extensions
    - .tar  # tar archive extension
    - .gz   # z algorithem extension
    - .xz   # J algorithem extension


## file systems
    - ext4      # timestamp is a feature in it


## files
    - /etc/sudoers.d    # configuration file for users that can use sudo command


# Things that was mentioned during the session


## topics
    - process managment
    - signals: {terminate - killing}
    - foreground & background
    - secure shell ssh    
    - mount devices
    - kernel events messages


## commands
    $ htop
    $ top
    $ man
    $ ps 
    $ kill
    $ ping
    $ bg        # activate the last process in background
    $ fg        # activate the last process in background
    $ ssh
    $ rsh
    $ nohup     # don't terminate background process there, when i stop ssh session 
    $ tmux
    $ wc
    $ mount
    $ lsblk
    $ dmesg
    $ fdisk
    $ umount
    $ fuser
    $ exit
    $ lsof


## commands with options
    $ man -k 
    
    $ ps aux

    $ kill -TERM                    # nicely kill
    $ kill -KILL                    # brutely kill
    $ kill -15                      # nicely kil
    $ kill -9                       # brutely kill
    $ tmux new -s session_name      # create new tmux session
    $ tmux a -t session_name        # attach to tmux session

    $ wc -l

    $ mount -t

    $ fdisk -l 

    $ fuser -u                      # identify user that make the file busy
    $ fuser -v                      # identify process that make the file busy
    $ fuser -k                      # kill process that make the file busy


## complex commands
    $ command &             # run the command in the background
    $ ctrl+z                # suspend (stop it) the process in background
    $ ssh user@ip
    $ nohup command &
    $ ctrl+b+d              # de-attach to tmux session
    $ !!                    # execute last command
    $ ctrl+r                # serach for command in history
    $ ctrl+d


## files
    - /etc/hosts    # contain all local DNS IPs mapped names in the system



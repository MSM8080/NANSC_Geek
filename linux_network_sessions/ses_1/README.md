# Things that was mentioned during the sessions


## Topics
- permissions bits [RedHat doc](https://www.redhat.com/en/blog/linux-file-permissions-explained)
- absolute/relative path [RedHat doc](https://www.redhat.com/en/blog/linux-path-absolute-relative)
- user/group [Medium doc](https://medium.com/@jasurbek.go.dev/users-groups-and-permissions-in-linux-1fa6d56b744a)
- default permissions bits [RedHat doc](https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/8/html/configuring_basic_system_settings/managing-file-system-permissions_configuring-basic-system-settings)
- hard/soft links [Dev doc](https://dev.to/kamruldev/linux-soft-links-and-hard-links-2g3l)
- file type charachter [Linuxcom doc](https://www.linux.com/training-tutorials/file-types-linuxunix-explained-detail/)
- pipeing commands [GeekforGeeks doc](https://www.geeksforgeeks.org/linux-unix/piping-in-unix-or-linux/)
- redirections commands [DigitalOcean doc](https://www.digitalocean.com/community/tutorials/an-introduction-to-linux-i-o-redirection)
- hidden files [GeekforGeeks doc](https://www.geeksforgeeks.org/linux-unix/how-to-view-and-create-hidden-files-in-linux/)
- wild cards [Medium doc](https://medium.com/@saikiransarvepalli/mastering-wildcards-in-linux-89206f2d595e)
- directory size [Linuxize doc](https://linuxize.com/post/how-get-size-of-file-directory-linux/)
- killing signals [man7 doc](https://man7.org/linux/man-pages/man7/signal.7.html)
- aliasing [GeekforGeeks doc](https://www.geeksforgeeks.org/linux-unix/alias-command-in-linux-with-examples/)
- creation & modification time
- archive [Linux foundation doc](https://training.linuxfoundation.org/blog/how-to-create-and-manage-archive-files-in-linux/)
- logs [Loggly doc](https://www.loggly.com/ultimate-guide/linux-logging-basics/)
- standard streams [tutorials doc](https://www.tutorialspoint.com/unix/unix-io-standard-streams.htm)


## Commands 
   `$ ls`                # list directory content
    $ ll
    $ cd  
    $ pwd
    $ ln
    $ clear
    $ reset
    $ history
    $ touch
    $ du
    $ echo 
    $ rm
    $ mkdir
    $ rmdir
    $ alias
    $ find
    $ man
    $ cp
    $ tar
    $ cat
    $ more
    $ less
    $ tail
    $ head
    $ echo
    $ watch 
    $ ps
    $ top
    $ htop
    $ grep
    $ sync
    $ rsync


## Command with options
    $ cd -                  # return to most recent previous directory path
    $ cd ~                  # return to home directory path
    $ cd .                  # go to current directory path
    $ cd ..                 # return one step backward directory path
    
    $ ls -l                 # list content with more info
    $ ls -h                 # list content with human-reada ble size
    $ ls -t                 # list content sorted by time stamp
    $ ls -r                 # list content sorted reversed 
    $ ls -a                 # list all content even hidden
    $ ls -d                 # list only directory 

    $ ln -s                 # create symbolic link
    
    $ du -h                 # display files disk usage in human readable file
    $ du --max-depth=1      # display files disk usage but not files in sub-directory

    $ rm *                  # remove all 
    $ rm -i                 # remove with asking every time for inshuring removing
    $ rm -r                 # remove recursively
    $ rm -I                 # remove but ask just one time for inshuring removing

    $ find -name            # by file name
    $ find -type            # by type
    $ find -mmin -n         # by time n minutes ago
    $ find -mmin +n         # by time n hours ago
    $ find -mtime -n        # by time n hours ago
    $ find -mtime +n        # by time n days ago

    $ cp -p                 # preserve creation & modification time stamp
    $ cp -a                 # copy only modified files + preserve + recursivly
   
    $ head -n               # print first n line in file

    $ tail -n               # print last n lines in file
    $ tail -f

    $ watch [ command ] -n  # execute command periodically every n seconds
    
    $ ps aux                # print snapshot report for current processes states
    
    $ grep -i               # case insensitive
    $ grep -v               # display non matching pattern
    $ grep -l               # mention only name of the file that conatins the pattern

    $ less -R               # view logs files in suitable format
    $ less -f               # force less to open & view non regualr files


## complex commands expressions
    $ watch "ps aux | grep process_name"    # serach specifiec process in processes report
    $ | > >>        # tools for redirection & piping 
    $ ctrl+c        # termiante running process
    $ ctrl+z        # pauses & suspends a running process
    $ ctrl+r        # search inside commands history
    $ !!            # rexecute last command
    $ !n            # n: number of command in history
    $ tab           # auto complete in terminal
    $ tab+tab       # display all auto complete suggestions
    $ up arrow      # moving backward through previous executed commands in terminal
    $ down arrow    # moving forward thorough previous executed commands in terminal
    $ esc+.         # insert last executed command in terminal line  
    $ 2>            # redirect (with override) the error stream
    $ 1>            # redirect (with override) the output stream 
    $ 2>>           # redirect the error stream
    $ 1>>           # redirect the output stream
    $ > 2>&1        # redirect (with override) error stream to what output stream redirect (with override) to
    $ >> 2>>$1      # redirect error stream to what output stream redirect to `


## file systems
    - zfc           # file system with feature of storing automaticly history for modifications
    - ext4          # modern linux file system
    - ext3          # old linux file system


## files
    - ~/.bash_history   # file contain most recent old executed commands (commands history)
    - ~/.bashrc         # file that executed every time a terminal session is opend



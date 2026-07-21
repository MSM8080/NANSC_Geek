# Things that was mentioned during the sessions


## Topics
    - permissions bits
    - absolute/relative path 
    - user/group
    - default permissions bits
    - hard/soft links
    - file type charachter
    - pipeing commands
    - redirections commands
    - hidden files
    - wild cards
    - directory size
    - killing signals
    - modifications types of files & directories
    - aliasing
    - creation & modification time
    - archive
    - logs
    - standard streams


## Commands 
    $ ls
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
    $ cd - 
    $ cd ~
    $ cd .
    $ cd ..
    
    $ ls -l
    $ ls -h
    $ ls -t
    $ ls -r
    $ ls -a
    $ ls -d

    $ ln -s
    
    $ du -h
    $ du --max-depth=1 

    $ rm *
    $ rm -i
    $ rm -r
    $ rm -I

    $ find -name
    $ find
    $ find -type
    $ find -mmin -n     # n minutes ago
    $ find -mmin +n     # n hours ago
    $ find -mtime -n    # n hours ago
    $ find -mtime +n    # n days ago

    $ cp -p     # preserve
    $ cp -a     # copy only modified files + preserve + recursivly
   
    $ head -n

    $ tail -n 
    $ tail -f

    $ watch [ command ] -n
    
    $ ps aux
    
    $ grep -i   # case insensitive
    $ grep -v   # display non matching pattern
    $ grep -l   # mention only name of the file that conatins the pattern

    $ less -R
    $ less -f


## complex commands expressions
    $ watch "ps aux | grep process_name"
    $
    $ | > >>
    $ ctrl+c
    $ ctrl+z
    $ ctrl+r        # search inside commands history
    $ !!
    $ !n            # n: number of command in history
    $ tab
    $ tab+tab
    $ up arrow
    $ down arrow
    $ esc+.
    $ 2>            # redirect (with override) the error stream
    $ 1>            # redirect (with override) the output stream 
    $ 2>>           # redirect the error stream
    $ 1>>           # redirect the output stream
    $ > 2>&1        # redirect (with override) error stream to what output stream redirect (with override) to
    $ >> 2>>$1      # redirect error stream to what output stream redirect to `


## file systems
    - zfc # automatic history for modifications
    - ext4
    - ext3


## files
    - ~/.bash_history
    - ~/.bashrc



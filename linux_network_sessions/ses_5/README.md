# Things that was mentiond during the session
---
## topics
- $ services managment
- $ Run levels
- $ systemd
- $ system v init
- $ regular expression
---
## commands
- $ systemctl
- $ chkconfig
- $ journalctl
- $ nmcli
- $ blkid
- $ mount
- $ ip
- $ dnf           # REHL packages manager
- $ yum
- $ cut
- $ pkill         # kill al processes that matches the name that be given 
- $ init 
- $ runlevel      # check my pc current level run 
- $ logrotate     # periodically archive the log file
- $ dmidecode
- $ iostate
- $ netstate
- $ netcat
- $ gzip
- $ which         # locate binary file absolute path
- $ hostnamectl
- $ sed
- $ usermod
- $ fallocate     # allocate file size on a drive
- $ service
- $ chown
- $ chgrp
- $ locate
- $ chattr        # chnage attribute
- $ partprobe
---
## commands with complex options
- $ systemctl start NetworkManger
- $ systemctl restart NetworkManger
- $ systemctl reload NetworkManger
- $ systemctl status NetworkManger
- $ systemctl stop NetworkManger
- $ systemctl enable NetworkManger
- $ systemctl disable NetworkManger
- $ systemctl set-default multi-user.target 

- $ chkconfig NetworkManger

- $ nmcli connection modify enp0s3 ip4.address 192.168.1.7

- $ sudo mount -a                                             # remount for every things that doesn't be mounted in /etc/fstab file

- $ ip route add 192.168.1.0/24 via 192.168.1.1               # adding static route for another network through the getway that i'm connected with in my pc routing table
- $ ip route                                                  # display routing table for my pc

- $ cut -d':' -f1 /etc/passwd                                 # extract first column data from (:)file that named /etc/passwd
 
- $ pkill -f galaxy                                           # kill all processes with name galaxy

- $ init 6                                                    # swithc to run level 6 (restart device)
- $ init 0                                                    # switch to run level 0 (shutdown)

- $ dmidecode -t memory

- $ iostate -x 2 

- $ hostnamectl set-hostname stage-node-01.local

- $ sed -i 's/new_string/old_string/g' file_name.txt              # replace all matched old strings with new strings in a file

- $ usermod -aG group_name user_name

- $ ip link show

- $ service service_name status
- $ service service_name restart
- $ service service_name reload
- $ service service_name start
- $ service service_name stop
- $ service service_name enable
- $ service service_name disable

- $ chattr +i
---

## important files
- /etc/fstab
- /etc/passwd
- multi-user.target
- /etc/sysconfig/network-scripts/                       # redhat 7 network config files
---
## Some regular expressions 
- ^ : starting of the line
- $ : end of the line
- * : any pattern
---


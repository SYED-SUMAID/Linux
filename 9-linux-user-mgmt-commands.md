
## Linux User Management Commands


#Debian/Ubuntu
```bash
-> Adding Users
  ============== 
  sudo useradd username              # create a new user
  sudo useradd -m username           # create user with home directory
  sudo useradd -m -s /bin/bash username   # set home dir + default shell
  sudo adduser username              # interactive user creation (Debian/Ubuntu)


-> Setting / Changing Passwords
  ============================== 
  sudo passwd username               # set/change a user's password
  passwd                             # change your own password
  sudo passwd -l username            # lock a user's password
  sudo passwd -u username            # unlock a user's password
  sudo passwd -S username            # show password status
 

-> Deleting Users
  ================
  sudo userdel username              # delete user (keeps home directory)
  sudo userdel -r username           # delete user + home directory
  sudo deluser --remove-home username   # remove user + home dir


-> Viewing User/Group info
  =========================
  id username                        # show UID, GID, groups
  whoami                             # show current logged-in user
  who                                # show who is logged in
  w                                  # show logged-in users + activity
  last                               # show login history
  groups username                    # show groups a user belongs to
  cat /etc/passwd                    # list all users
  cat /etc/group                     # list all groups


-> Switching Users/Privileges
  ============================
  su username                        # switch user 
  su - username                      # switch user with full login environment
  sudo command                       # run a single command as root
  sudo -i                            # start root login shell
  sudo -u username command           # run command as another user
  visudo                             # safely edit /etc/sudoers file
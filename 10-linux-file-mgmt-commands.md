
# Linux File Management Commands

## Debian/Ubuntu
```bash
-> Creating File & Directories
  =============================
  touch file.txt                 # create empty file / update timestamp
  mkdir dirname                  # create a directory
  mkdir dir1 dir2 dir3           # create multiple directories at once


-> Viewing Files & Directories
  =============================
  ls                              # list files in current directory
  ls -l                           # long listing (permissions, size, date)
  ls -a                           # show hidden files too
  ls -la                          # combine long + hidden
  ls -S                           # sort by file size
  pwd                             # print current working directory


-> Removing Files & Directories
  ==============================
  rm file.txt                     # delete a file
  rm -i file.txt                  # confirm before deleting
  rm -f file.txt                  # force delete (no prompt)
  rm -r dirname                   # delete directory recursively
  rm -rf dirname                  # force delete directory (use with caution!)
  rmdir dirname                   # delete empty directory only
  

-> File Permissions
  ==================
  chmod 755 file.txt              # rwxr-xr-x
  chmod 644 file.txt              # rw-r--r--
  chmod +x script.sh              # make file executable
  chmod -x script.sh              # remove executable permission

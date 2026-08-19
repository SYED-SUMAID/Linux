
## Linux nano Editor Commands


#Debian/Ubuntu
```bash
-> Opening Files
  ===============
  nano file.txt                  # open or create a file
  nano +15 file.txt              # open file and jump to line 15
  sudo nano /etc/hosts           # open a system file (needs root)


-> Saving & Exiting
  ==================
  Ctrl + O    # Write Out (save file)
  Enter       # confirm filename when saving
  Ctrl + X    # exit nano


-> Cut,Copy,Paste
  ================
  Ctrl + K    # cut current line (or selected text)
  Ctrl + U    # paste (uncut) what you cut
  Alt + 6     # copy current line (or selected text)
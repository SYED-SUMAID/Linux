
## Vi Editor Commands


# Debian/Ubuntu
```bash
-> Opening a File
  ================
  vi filename    # Opens or creates a file in the vi editor
  i              # Inserts before the cursor
  I              # Inserts at the beginning of the current line
  a              # Inserts after the cursor
  A              # Inserts at the end of the current line
  o              # Opens a new line below and enters Insert mode
  O              # Opens a new line above and enters Insert mode
  Esc            # Exits Insert mode and returns to Command mode


-> Saving & Exiting
  ==================
  :w             # Saves the file
  :q             # Quits the editor
  :wq            # Saves the file and quits the editor
  :x             # Saves the file (if modified) and quits
  ZZ             # Saves the file and quits (shortcut)
  :q!            # Quits without saving changes


-> Copy & Paste
  ==============
  yy             # Copies the current line
  5yy            # Copies 5 consecutive lines
  p              # Pastes below the cursor
  P              # Pastes above the cursor

-> Undo & Redo
  =============
  u              # Undoes the last change
  Ctrl + r       # Redoes the last undone change

-> Searching
 ===========
  /word          # Searches for a word in the file
  n              # Moves to the next search result
  N              # Moves to the previous search result


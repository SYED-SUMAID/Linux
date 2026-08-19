
## Systemctl Commands


# Debian/Ubuntu

-> Service Control
```bash
  =================
   sudo systemctl start apache2        # start Apache
   sudo systemctl stop apache2         # stop Apache
 
   sudo systemctl restart apache2      # restart (stop then start)
   sudo systemctl reload apache2       # reload config without restart


-> Enable/Disable at Boot
  ========================
  sudo systemctl enable apache2       # start automatically at boot
  sudo systemctl disable apache2      # don't start at boot
  sudo systemctl enable --now apache2 # enable + start immediately
  sudo systemctl disable --now apache2 # disable + stop immediately


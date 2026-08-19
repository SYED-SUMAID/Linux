
## Kill Commands & Signals
```bash
1. "kill"

Used to send a signal to a process using its PID

kill 1234

Example: Terminate the process with PID "1234"

# -----------------------------------------------------

2. "kill -9"

Used to forcefully terminate a process

kill -9 1234

Example: Forcefully terminate the process with PID "1234"

# -------------------------------------------------------

3. "kill -15"

Used to gracefully terminate a process. "15" represents "SIGTERM"

kill -15 1234

Example: Ask process "1234" to terminate normally.

# -------------------------------------------------------


4. "kill -2"

Sends "SIGINT" to a process and interrupts it

kill -2 1234

Example: Interrupt process "1234", similar to pressing "Ctrl + 

# -------------------------------------------------------


5. "kill -1"

Sends "SIGHUP" to a process

kill -1 1234

Example: Send a hang-up signal to process "1234"

# --------------------------------------------------------


6. "kill -3"

Sends "SIGQUIT" to a process

kill -3 1234

Example: Request process "1234" to quit

# -------------------------------------------------------


7. "kill -STOP"

Stops a running process

kill -STOP 1234

Example: Pause process "1234"

# -------------------------------------------------------


8. "kill -CONT"

Continues a process that was stopped

kill -CONT 1234

Example: Resume process "1234" after it was stopped

# -------------------------------------------------------


9. "kill -0"

Checks whether a process exists and whether you have permission to signal it

kill -0 1234

Example: Check whether process "1234" is running

# -------------------------------------------------------


10. "kill -l"

Lists the available signals.

kill -l

Example: Display all signals supported by the system

# -------------------------------------------------------


11. "pkill"

Sends a signal to processes using their name instead of their PID

pkill firefox

Example: Send the default termination signal to Firefox processes

# -------------------------------------------------------


12. "pkill -9"

Forcefully terminates processes by name

pkill -9 firefox

Example: Forcefully terminate Firefox processes

# -------------------------------------------------------


13. "killall"

Terminates processes using their name

killall firefox

Example: Terminate all matching Firefox processes

# -------------------------------------------------------


14. "killall -9"

Forcefully terminates processes by name

killall -9 firefox

Example: Forcefully terminate all matching Firefox processes

# -------------------------------------------------------


15. "SIGTERM"

"SIGTERM" is signal number "15". It requests a process to terminate gracefully

kill -SIGTERM 1234

Example: Gracefully terminate process "1234"

# -------------------------------------------------------

16. "SIGKILL"

"SIGKILL" is signal number "9". It forcefully terminates a process

kill -SIGKILL 1234

Example: Forcefully terminate process "1234" when it does not respond to normal termination

# -------------------------------------------------------


17. "SIGINT"

"SIGINT" is signal number "2". It interrupts a running process

kill -SIGINT 1234

Example: Interrupt process "1234", similar to "Ctrl + C"

# -------------------------------------------------------


18. "SIGSTOP"

"SIGSTOP" stops a process immediately

kill -SIGSTOP 1234

Example: Stop process "1234" temporarily

# -------------------------------------------------------


19. "SIGCONT"

"SIGCONT" resumes a stopped process

kill -SIGCONT 1234

Example: Resume process "1234" after using "SIGSTOP"

## Displaying the process status

Alternatively to the `top` command, the `ps` command allows us to get a _non interactive_ display of __the current running processes__.

In the current _bash session_ execute: 

```
# -f option of the `ps` command extends the information to be displayed:
ps -f
```

Result (PID's may vary):

```
UID        PID  PPID  C STIME TTY          TIME CMD
codio      359   358  0 02:17 pts/0    00:00:00 -bash
codio      466   359  0 03:17 pts/0    00:00:00 bash 
codio      469   466  0 03:17 pts/0    00:00:00 ps -f
```

Two `bash` commands are currently on the list. Let's switch to the default _bash shell_ with the more familiar `codio ~/workspace $` prompt by executing: 

```
suspend
```

|||definition
## Command: 
```
ps <options>
```
__Definition:__ The `ps` utility displays information about about the current running processes, including their process identification numbers (PIDs).
|||
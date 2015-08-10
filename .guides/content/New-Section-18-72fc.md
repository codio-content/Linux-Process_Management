It is possible to track the `loop.sh` file process by executing the `ps` command during the 30 seconds that the _bashscripts_ takes to complete: 

```
PID TTY          TIME CMD
359 pts/0    00:00:00 bash
488 pts/0    00:00:00 loop.sh
492 pts/0    00:00:00 sleep
493 pts/0    00:00:00 ps
```
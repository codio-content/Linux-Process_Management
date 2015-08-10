It is possible to track the `loop.sh` file process by executing the `ps` command during the 30 seconds that the _bashscript_ takes to complete (if the process has ended, you can execute the file again):

```
PID TTY          TIME CMD
359 pts/0    00:00:00 bash
488 pts/0    00:00:00 loop.sh
492 pts/0    00:00:00 sleep
493 pts/0    00:00:00 ps
```

In this case, the _PID_ of the `loop.sh` process is `488`. 

### What if a process becomes unresponsive?

Whenever a computer starts to feel _laggy_, it is most probably that one of the current running processes is taking too much CPU power, too much memory power or it could be because the program becomes _unresponsive_ (also called _Zombie_ processes).

PID numbers are very useful references to processes because we can use them to `kill` _unresponsive programs_.

Lets `kill` the `loop.sh` process: 

1. Execute the `loop.sh` file again
2. Do a `ps` while its running
3. Identify the `PID` number
4. Execute: `kill <PID>` where `<PID>` is the `loop.sh` PID number


Additionaly, you can open the `count.txt` file to confirm the _loop count_ interruption.
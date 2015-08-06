Computer processes are divided into 2 kinds: 

- Foreground processes
- Background processes

Lets understand the difference between both of them by executing the `sleep` command in the terminal screen. This command pauses the CLI during the specified amount of time:

```
# Try typing or executing other commands while the 5 secs. pause:
codio ~/workspace $ sleep 5
```

### Foreground processes

A foreground process is different from a background process in 2 ways:

1. Some foreground processes show the user an interface, through which the user can interact with the program. In this case the CLI is that user interface.
2. The user must wait for one foreground process to complete before running another one.

### Background processes
Unlike with a foreground process, the shell does not have to wait for a background process to end before it can run more processes.

You can enter as many background commands one after another within the limit of the amount of memory available. 
The `top` command is one fo the most intuitive CLI commands.

For example, while the `top` command is still running, try pressing the `?` key to get more information about the usage of the command. 

For instance, lets focus on the `shift + f` option for sorting the program information. 

Press the `shift + f` key to get a list of possible sorting keys:

```
Current Sort Field:  A  for window 3:Mem 
Select sort field via field letter, type any other key to return
a: PID        = Process Id 
e: USER       = User Name 
k: %CPU       = CPU usage 
n: %MEM       = Memory usage (RES)
x: COMMAND    = Command name/line
...
```

Press the `k` key for sorting the proccesses by _CPU usage_ and then press the _return_ key.

__Take a closer look at the _top_ command _%CPU_ indicator while pressing the _return key_ several times__. 

Did the value change?

The `top` command periodically updates the status of the processes and sorts them accordingly. 

__Quit the `top` command__ by pressing the `q` key or `ctrl + c`.
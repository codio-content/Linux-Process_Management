Take a closer look at the _top_ command column labelled with a letter 'S' for _Process Status_.

Whether you open T1 or T2, you'll notice that one of the `top` command processes is _Sleeping_ while the other is _Running_. 

The `top` process that is _Running_ is the one of the selected terminal (the foreground process). 

Whenever you switch from T1 to T2 or the other way around, the _Running_ process becomes the one of that current terminal window.

|||info
### Real world foreground processes

Computer operating systems such as UNIX (Codio's terminal), Linux (An improvement on UNIX), Darwin (Mac's version of Linux) or Windows just to name a few; are designed to optimize the performance of software execution by delegating CPU and Memory power to the current running program or _foreground process_.

Whenever your computer starts to feel slow or _out of the expected performance_, could be because one background process is taking too much of this CPU/MEM power.

#### 2 open web-browser windows

Whenever you open 2 or more windows of the same web-browser on your computer, the principles of background and foreground processes are being executed. 

Therefore CPU and Memory power is delegated to the current web-browser window in order to improve its performance.
|||
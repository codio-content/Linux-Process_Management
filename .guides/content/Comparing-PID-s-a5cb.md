By having 2 active terminal windows, we assume that: 

- Each of them is running a _bash_ process
- Each of them is running a _top_ process

Our assumptions can be supported by comparing both __terminal 1__ and __terminal 2__ `top` command `PID` columns:

![cli6-top-cmd-terminals](.guides/img/cli6-top-cmd-terminals.png)
<small>Note: _PID's may vary_</small>.

T1 and T2 `top` command rows have different `PID` numbers. This indicator means that we are in fact running 2 different _top_ processes. Each of them can have its own sorting options and work independently from one another. 

Have you tried selecting a different sorting key for one of the _top_ processes?


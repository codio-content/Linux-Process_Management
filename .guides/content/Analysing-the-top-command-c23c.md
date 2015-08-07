If you've tried running the `top` command, a similar output might be displayed:

![cli6-top-cmd](.guides/img/cli6-top-cmd.png)

- __Tasks__: A list of the number of current processes the computer is running. The `top` program is the one labelled as _running_ while other software such as the _bash shell_ is paused.
 _Zombie_ programs are the ones that fail to quit or _crash_ because of a bug or a system memory overload.
- __PID__: The _process identication number_ is the default sorting key of the `top` processes list. _Running_ or _Zombie_ programs can be _killed_ by using this unique id.
- __USER__: The user that started the task. For example, the _root_ user tasks, also called _super user_ are running on the background. The _codio_ user is running a _bash_ shell and the _top_ command itself (PID 349 and 367).
- __%CPU & %MEM__: Display the percentage of the computer's _Central Processing Unit_ usage and the _Random Access Memory_ or RAM usage. These indicators are great for identifying what program is making the computer _laggy_ or slow sometimes.
- __COMMAND__: The program (software) name.
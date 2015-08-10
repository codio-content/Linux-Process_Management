## Running multiple _bash_ sessions in a single terminal

_Bash_ itself is a command that can be executed on its own: `bash`

The `bash` command will create another _shell session_ which behaves as a separate terminal window because it becomes a foreground process. 

Click on the terminal on the left and execute: 

```
codio ~/workspace $ bash
```

A new _bash session_ has been created. 

For instance, we know this because the command prompt changed to something like this:
  
```
# Prompt may vary from shell to shell:
codio@couple-capital:~/workspace$
```

### Become more productive

When working on a software project, sometimes we need to constantly `cd` into different directories. Different _bash sessions_ on a single terminal can hold different current directories. 

Try navigating into the `config` directory in the current _bash session_: `cd config/`

```
# The prompt will display the current directory:
codio@couple-capital:~/workspace/config$
```
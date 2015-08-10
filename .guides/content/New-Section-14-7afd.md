## Running multiple _bash_ sessions in a single terminal
We've created a _bashscript_ that would take 30 seconds to complete.

__As a foreground process__, this process will totally block the current terminal until it's completed. 

However, by adding the `&` _ampersand_ symbol, we can put the process to be executed __as a background process__ 

Copy and paste the following code into the terminal and press the return key: 

```
~/workspace/.guides/bashtests/loop.sh &
```

### 


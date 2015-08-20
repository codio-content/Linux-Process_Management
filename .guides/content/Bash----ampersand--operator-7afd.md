### Putting processes in the background

We've created a _bashscript_ that would take 30 seconds to complete. This _bashscript_ will: 

1. Create a new `~/workspace/count.txt` file
2. Append a new "This is count: $COUNT" line every 3 seconds until `COUNT = 10`

__As a foreground process__, this process will totally block the current terminal until it's completed.

However, by adding the `&` _ampersand_ symbol, we can put the process to be executed __as a background process__ 

Copy and paste the following code into the terminal and press the return key (a `chmod` command was automatically executed on the terminal for allowing you to run the file):

```
~/workspace/.guides/bashtests/loop.sh &
```

While the process is running on the background, we can keep using our terminal for executing other commands. 
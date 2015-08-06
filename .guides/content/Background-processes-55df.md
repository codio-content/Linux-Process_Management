As we mentioned earlier, the shell does not have to wait for a background process to end before it can run more processes.

We've enabled 2 terminal windows on the left panel. Lets understand _background processes_ by comparing the `top` command output between 2 terminal windows, each of them running a _top command_ process at the same time.

On __*terminal 1*__ (choose the first terminal from left to right): 

1. Execute the `top` command
2. Display the sort keys menu: `shift + f`
3. Sort by Proccess Status: `w + return key`
4. Sort by ascending order: `shift + r`

For __*terminal 2*__ repeat the same instructions:

1. Execute the `top` command
2. Display the sort keys menu: `shift + f`
3. Sort by Proccess Status: `w + return key`
4. Sort by ascending order: `shift + r`

---

__NOTE:__ Process status is the _S_ column and indicates: `S` for _Sleeping process_, `R` for _Running process_.
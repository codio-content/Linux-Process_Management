## I suspended the _bash_ process, how do I go back?

We can identify a _suspended_ process by looking at the _process status_ (S) column of the `top` command. 

_Suspended_ or _stopped_ processes are labelled with an uppercase `T`. 

Currently, our _stopped_ process is a _bash_ session left inside the `config/` directory. 

Lets get back to the other _bash process_ by executing: 

```
codio ~/workspace $ fg
```

The `fg` command switches from the _foreground process_ (the current bash session) and switches to the _suspended_ process. 

### Exiting processes

Unlike the `suspend` command, the `exit` command totally finishes the process.

By executing the `exit` command in our 2nd current bash session (the one with the long prompt), the user is logged out from the session and the default bash session takes its place.

---

Try executing either a `top` or a `ps -f` command to verify that the process has been terminated.
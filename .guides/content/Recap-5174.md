## Security in mind

The `chmod` command is a very powerful one. By determining the _read, write and execute_ permissions of a file hierarchy the owner decides _who_ is allowed to perform _what_ inside a directory. 

### Different user types

The way in that the _change mode_ command works is by specifying permissions or modes for the different types of users: 

- The owner user is represented by a letter `u`
- The group which the user belongs to is represented by a letter `g`
- The _world_ or _other_ users are represented by a letter `o`

### Mode assignment

The __string permissions__ as they are commonly known are assigned to a file or directory by using the user type letters `ugo` and the permissions type letters `rwx` with the `+-` operands to add or remove permissions respectively.

__Numerical mode assignment__ is another way of changing any file or file hierarchy permissions. The _read_ permission gets a value of `4`, the _write_ permission a value of `2` and the _execute_ permission a value of `1`. By adding this values to each of the user types we determine the system cappabilities that each of them have.
Some useful bash functions

Currently implemented:

`is_true`
-------
check pseudo-boolean values

`check_rc`
--------
checks a programs return code for success for failure

`is_decimal`
----------
Determines if a value is decimal

`is_decimal`
----------
Determines if a value is hex

`is_octal`
--------
Determines if a value is hex

`log`
---
Logs a message to stdout or stderr

`log_syslog`
----------
Logs a message to syslog

`die`
---
Logs a message and exits the program with a defined exit code

`exec_or_die`
-----------
Executes a command and exits the program if the command failed

`check_pid`
---------
Checks a pid for existance

`vargrep`
-------
Greps in string variables

`array_push`
----------
Pushes a value to an array

`array_get`
---------
Gets an value from an array an sets it to a var

`array_get_first`
---------------
Gets the first element of an array

`array_get_last`
--------------
Gets the last element of an array

`array_copy`
----------
Copies an array to another

`array_set`
---------
Sets the value of an array

`array_reset`
-----------
Resets an array to zero or to the defined elements

Author
======
Lukas Grässlin <lukagraesslin@gmx.de>

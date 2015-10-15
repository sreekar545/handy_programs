# dynamic-logroller

Dynamic Logroller (Single executable, plain old C program, portable to any OS)

  This program handles the output(STDOUT for C/C++) of your application when your application doesn't have a log rolling mechanism. You can redirect the output of your application to logroller and it dynamically rolls the logs so you don't need to restart your application to roll the logs. It has arguments to set the size of the log before rolling and the frequency to check for size.

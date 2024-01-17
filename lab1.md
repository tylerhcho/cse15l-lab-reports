# 1. Examples running `cd` with no arguments, a directory as an argument, and a file as an argument:\
![Image](cd) \
As seen in the picture, the working directory was `home` for the first 2 examples and `home/lecture1/` for the last example.\
\
The `cd` command is used to change directories, so the working directory is set to whatever directory is given in the argument.\
When no argument was given, the working directory remains the same because it just "changes" to the current directory. This is not an error.\
When a directory was given as an argument, the working directory was set to that directory. This is not an error.\
When a file was given as an argument, an error message was given because it is expected to be given a directory name as an argument.\
\
# 2. Examples running `ls` with no arguments, a directory as an argument, and a file as an argument:\
![Image](ls) \
As seen in the picture, the working directory was set to `home/lecture1` for all the cases.\
\
The `ls` command is used to list all the items in the working directory or specified directory.\
When no argument was given, all items within the working directory were returned by default. This is not an error.\
When a directory was given, all items within that directory were returned. This is not an error.\
When a file was given as an argument, only the file in the argument was returned. This is not an error because the file itself is the only thing to be listed.\
\
# 3. Examples running `cat` with no arguments, a directory as an argument, and a file as an argument:\
![Image](cat) \
As seen in the picture, the working directory was set to lecture1 for all the cases.\
\
The `cat` command is used view the contents of a file. \
When no argument was given, nothing happened, but I was not able to give any commands afterwards, so I had to press `Ctrl-C` in order to reset the console. This is not an error.\
When a directory was given, it returned: `cat: messages: Is a directory`. This is an error message because a file name is expected as an argument.\
When a file was given, it returned the contents of the file. In this case, the java code in the `Hello.java` file. This is not an error.\

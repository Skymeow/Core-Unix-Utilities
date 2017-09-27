# Core: Unix Utilities

_More powerful than the spiky blue shell_

## Challenges, Part 1

Challenges within each section are meant to be solved in order.

### Navigation

1.  Print the path of your working directory
- `pwd`
1.  List the files in your working directory
-`ls`
1.  List the files with a particular extension, like `.txt`
-`ls *.txt`
1.  List the files in a subdirectory, like `project`
-`cd ./project; ls`
1.  Navigate to a subdirectory, like `project`
-`cd ./project`
1.  Navigate to the parent directory of your working directory
-`pwd; cd ../../`
1.  Navigate to a nested subdirectory, like `path/to/project`
-`cd ~/path/to/project`
1.  Navigate to your home directory
-`cd /`
1.  Navigate back to the previous directory
-`cd ../`

### Variables

1.  Print a sentence, like `Hello world`
-`echo "Hello World"`
1.  Print a variable value, like `$USER` or `$PATH`
-`echo "$USER"`
1.  Set a variable `NAME` equal to your first name, then print its value
-`NAME="sky"; echo "NAME"`
1.  Set a variable `FULL_NAME` equal to your full name, then print its value
-`FULL_NAME="skyxu"; echo "$FULL_NAME"`
1.  Print all environment variables (names and values)
-`printenv`
1.  Make an alias named `hello` that prints `Hello world`
-`bashrc`
1.  Make an alias named `gocode` that navigates to your code directory
-`bashrc ~/code`
1.  Print all aliases (names and values)
- `alias`

### Getting Help

1.  Print what options a command accepts, like `bash` or `python`
-`man options`
1.  Read the manual for a command, like `echo` or `ls`
-`man echo` -`man ls`
1.  Print the file path to a command, like `bash` or `python`
-`python -c "import sys; print(sys.path)`
this prints out the dir in an arr
-`python -c "import sys; print(':'.join(x for x in sys.path if x))`

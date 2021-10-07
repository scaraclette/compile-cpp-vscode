# compile-cpp-vscode
Example on how to compile cpp files in vscode

# Understand
1. Before running C++, understand how to compile a program. In Java, when we create a program we needed to do:
```$ javac program.java``` to compile, then enter ```$ java program``` to run the compiled program.

# How to run in vscode
1. Make sure you have gcc, run the following command in terminal/bash/zsh:
```$ gcc --version```. If you do not have it, download with the following instructions https://discussions.apple.com/thread/8336714
2. Read how to compile c++ program: https://www.tutorialspoint.com/How-to-compile-and-run-the-Cplusplus-program. When you know how to compile, you can use a script to run a program (while also compiling).
3. Have basic understanding about what are scripts: https://www.shellscript.sh/
4. An example script to compile this repo's C++ program is by running ```$ ./run.sh```

# Creating your own scripts
1. Try creating a new script by making a new .sh file. For example, create new_script.sh file.
2. Copy paste the contents of run.sh to new_script.sh file.
3. Unlike, we cannot run the new_script.sh file yet because we haven't changed access permission (https://en.wikipedia.org/wiki/Chmod).
4. To make new_script.sh be an executable, run ```$ chmod 755 new_script.sh```
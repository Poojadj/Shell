# Shell
A Simple Shell in C

Functionalities :

The following functions have been written explicitly in C.

cd - Change directory

pwd - Present Working directory

mkdir - Make a directory (Alerts if already exists)

rmdir - Remove the directory (Alerts if no such file or directory)

ls - List contents of pwd

cp - Copy contents of file1 to file2; only if file1 was more recently modified. Create file2 if not present already.

exit - Exit the shell ;

Supports running the execuables (predominanatly, ./a.out and scripting commands, like touch, cat, python notif.py )

Any path added to your $PATH folder will work. 

Input from and output to files, such as ./d < in.txt and ./inc > in.txt supported. (Both can work simultaneously.)

Support piping upto 2 levels - such as ./inc | ./d and ./inc | ./d | ./t

Issue :

For some freaking reason, editor does'nt work properly. Looks like editor has grudge against me or something.

CLI = Comand line interface
THe termninal is a text-based interface for controlling a Linux sistem. In this you type commands that tell the computer what to do
some commands are:

pwd ==> This commnad return the path where i am.
ls ==> this command list the content of the current directory. If we want more details, we can use ls -l
ls -al ==> With this command, we can display all the hiden files present in the directory. Hidden files start with a dot(.).

If we need move though the filesystem, we can use cd <Directory>. To go back we use, cd ..

find ==> Is used to locate files within the file system. find <startin_point> -name <filename>. If i out ~, this indicate the search begin the home directory.
          If the file exists, Linux will print the full path to it.

cat ==> This command is use to read the content of the file.
whoami ==> Print the current username
uname -a ==> See details about the operating system, kernel version, and architecture
df -h ==> This command is use for check disk usage or available space. -h means "human readable"
    dev/root/ ==> is the main disk of the system
    tmpfs ==> entries are temporary filesystems stored in RAM, not on the physical disk.
    dev/shm/ ==> is a shared memory
    run/user/114 ==> is similar temporary storage for another system user.

Linux store configuration and information files in the /etc directory.

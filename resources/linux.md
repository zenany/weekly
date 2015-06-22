Linux
========

## 分布式系统

**Distributed systems readings**  
http://www.andrew.cmu.edu/course/15-749/READINGS/required/  

## tools

[Linux 和类 Unix 系统上5个最佳开源备份工具](http://linux.cn/article-4623-1.html)  
[Bash 快捷键大全](https://linux.cn/article-5660-weibo.html)  

**The Art of Command Line**  
https://github.com/jlevy/the-art-of-command-line  
This is a selection of notes and tips on using the command-line that I've found useful when working on Linux. Some tips are elementary, and some are fairly specific, sophisticated, or obscure. This page is not long, but if you can use and recall all the items here, you know a lot.  

## basic

**WhyTheName**  
https://wiki.debian.org/WhyTheName  

**An Introduction to Unix**  
http://www.oliverelliott.org/article/computing/tut_unix/  

**race condition**  
A race condition occurs when two or more threads can access shared data and they try to change it at the same time. Because the thread scheduling algorithm can swap between threads at any time, you don't know the order in which the threads will attempt to access the shared data. Therefore, the result of the change in data is dependent on the thread scheduling algorithm, i.e. both threads are "racing" to access/change the data.   
http://stackoverflow.com/questions/34510/what-is-a-race-condition  
http://www.dwheeler.com/secure-class/Secure-Programs-HOWTO/avoid-race.html  

**Futex**  
http://man7.org/linux/man-pages/man7/futex.7.html  
The Linux kernel provides futexes ("Fast user-space mutexes") as a 
building block for fast user-space locking and semaphores.  Futexes 
are very basic and lend themselves well for building higher level 
locking abstractions such as POSIX mutexes.

**umask**  
http://www.cyberciti.biz/tips/understanding-linux-unix-umask-value-usage.html  

**file permissions**  
http://www.linux.com/learn/tutorials/309527-understanding-linux-file-permissions  
http://en.wikipedia.org/wiki/File_system_permissions  
http://linuxcommand.org/lts0070.php  
http://www.ics.uci.edu/computing/linux/file-security.php  
http://blog.csdn.net/timewalker08/article/details/6765000  
http://www.bashguru.com/2010/03/unixlinux-advanced-file-permissions.html  
+------------------+
|rwxrwxrwx     777 | all permissions granted
|rwxr-xr-x     755 | Group and world readbale/eecutable
|rwx------     700 | Private
|rwsr-xr-x    4755 | set UID
|rwxr-sr-x    2755 | set GID
|rwxr-xr-t    1755 | Sticky bit
|rwSw-xr-x    4655 | setUID but not executable by user
|rwxr-Sr-x    2745 | getGID, but not executable by group members
|rwxr-xr-T    1754 | Sticky bit, but not world executable
stick-bit 
The stick-bit on the other hand is denoted as a t, such as with the /tmp directory:
This bit should have always been called the "restricted deletion bit" given that's what it really denotes. When this mode bit is enabled, it makes a directory such that users can only delete files & directories with in it that they are the owners of.
UNIX/Linux Advanced File Permissions - SUID,SGID and Sticky Bit

Advanced Permissions
The special permissions flag can be marked with any of the following:
    _ - no special permissions
    d - directory
    l - The file or directory is a symbolic link
    s - This indicated the setuid/setgid permissions. This is not set displayed in the special permission part of the permissions display, but is represented as a s in the read portion of the owner or group permissions.
    t - This indicates the sticky bit permissions. This is not set displayed in the special permission part of the permissions display, but is represented as a t in the executable portion of the all users permissions


zsh  http://macshuo.com/?p=676  

## study 

[The problem with select() vs. poll() (code)]
(http://beesbuzz.biz/blog/e/2013/10/10-the_problem_with_select_vs_poll.php)  
[poll vs select vs event-based](http://daniel.haxx.se/docs/poll-vs-select.html)  

## tools

[neu_sshbl_hosts](http://antivirus.neu.edu.cn/ssh/lists/neu_sshbl_hosts.deny)

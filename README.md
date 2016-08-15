# Priority-scheduler-and-Multithreading-support-to-xv6-Operating-system
Added a support of Priority scheduler to xv6 operating system which had a default round-robin scheduler and also added support for multithreading in xv6.
For priority based scheduler Modified the folowing files:
proc.c, proc.h, sysproc.c, sysproc.h, syscall.c, syscall.h, user.h, usys.S, defs.h
added a tesc code to test the working of scheduler.

For Multi threading added code in these files:
syscall.c ,syscall.h ,proc.c,proc.h ,sysproc.c,defs.h,pthread.c ,pthread.h,user.h
added a mul1 code to test how multithreading works.


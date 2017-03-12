language
========
- C Primer Plus, 6th edition. (已读)
- C11 Standard (在读)
- crt0 wiki
  https://en.wikipedia.org/wiki/Crt0
- not to use scanf
  http://c-faq.com/stdio/scanfprobs.html
- Why use apparently meaningless do-while and if-else statements in C/C++ macros?
  http://stackoverflow.com/questions/154136/why-use-apparently-meaningless-do-while-and-if-else-statements-in-c-c-macros
- Bit fields
  http://en.cppreference.com/w/c/language/bit_field
- enum
  http://en.cppreference.com/w/c/language/enum
- conditional operator
  http://en.cppreference.com/w/c/language/operator_other#Conditional_operator

source codes
============
- glibc source (在读)
- evince source (在读)

dev tools
=========
gdb
---
- Peter's gdb tutorial. (无笔记)
- gdb manual (在读)

cscope
------
- Using Cscope on large projects
  http://cscope.sourceforge.net/large_projects.html
- vim cscope doc: if_cscop.txt
- cscope(1) manpage

libraries and syscalls
======================
IO
--
- file and stream

  * fcntl.h(0P), fcntl(2)
    - open(2)

  * unistd.h(0P)
    - lseek(2)
    - fsync(2)
    - fdatasync(2)

    - dup(2)
    - dup2(2)
    - dup3(2)

  * fcntl.h(0P), fcntl(2)
    - fcntl(2)

  * stdio.h(0P), stdio(3)
    - stdin, stdout, stderr
    - fopen(3), fdopen(3), freopen(3), fclose(3)
    - fileno(3)
    - feof(3), ferror(3), clearerr(3)
    - fread(3), fwrite(3)
    - fseek(3), ftell(3), rewind(3)
    - setvbuf(3), fflush(3)

- text io

  * stdio.h(0P), stdio(3)
    - printf(3), fprintf(3), sprintf(3),
    - dprintf(3), snprintf(3), asprintf(3)
    - vprintf(3), vfprintf(3) vsprintf(3),
    - vdprintf(3), vsnprintf(3), vasprintf(3)
    - scanf(3), fscanf(3), sscanf(3)
    - getchar(3), getc(3), fgetc(3), gets(3), fgets(3), ungetc(3)
    - putchar(3), putc(3), fputc(3), puts(3), fputs(3)

- binary io

  * unistd.h(0P)
    - read(2)
    - write(2)
    - close(2)

    .. positioned and scattered io

    - pread(2)
    - pwrite(2)
    - readv(2)
    - writev(2)
    - preadv(2)
    - pwritev(2)

- error handling

  * stdio.h(0P), stdio(3)
    - perror(3)

  * errno(3), errno.h(0P)

  * string.h(0P)
    - strerror(3)

- file operations

  * unistd.h(0P)
    - unlink(2)
    - rmdir(2)

  * stdio.h(0P), stdio(3)
    - remove(3)

  * fcntl.h(0P), fcntl(2)
    - fallocate(2)
    - posix_fallocate(3)

- temp file

  * stdlib.h(0P)
    - mkstemp(3)
    - mkostemp(3)
    - mkstemps(3)
    - mkostemps(3)
    - tmpfile(3)
    - mkdtemp(3)

- device manipulation

  * sys/ioctl.h
    - ioctl(2)
    - ioctl_list(2)

file system
-----------
- path_resolution (7)

system limits and options
-------------------------
- get limits and options

  * limits.h(0P)

  * posixoptions(7)

  * unistd.h(0P)
    - sysconf(3) --- get runtime invariants and runtime increasable
    - pathconf(3), fpathconf(3) --- get pathname variables
    - confstr(3) --- get string values

type and constant definitions
-----------------------------
- stdbool.h(0P)

- stdarg.h(0P), stdarg(3)
  * va_list
  * va_start
  * va_arg
  * va_end
  * va_copy

- stdint.h(0P), inttypes.h(0P)

- limits.h(0P)

- float.h(0P)

- stddef.h(0P)

string operations
-----------------
- length

  * string.h(0P)
    - strlen(3)

- comparison

  * string.h(0P)
    - strcmp(3), strncmp(3)
    - strcoll(3)

  * strings.h(0P)
    - strcasecmp(3), strncasecmp(3)

- character set

  * ctype.h(0P)
    - isalnum(3)
    - isalpha(3)

    - isgraph(3)
    - isprint(3)
    - isspace(3)
    - ispunct(3)

    - iscntrl(3)

    - islower(3)
    - isupper(3)

    - isdigit(3)
    - isxdigit(3)

- copy

  * string.h(0P)
    - strcpy(3), strncpy(3)
    - strcat(3), strncat(3)
    - stpcpy(3)

    - strdup(3), strndup(3)
    - strdupa(3), strndupa(3)

    - memcpy(3), memmove(3)
    - memset(3)

    - strxfrm(3)

- find, split

  * string.h(0P)
    - strchr(3), strrchr(3)
    - strstr(3), strcasestr(3)

    - strpbrk(3)
    - strspn(3), strcspn(3)

    - strtok(3), strtok_r(3)

- conversion

  * stdlib.h(0P)
    - atoi(3), atol(3), atoll(3)
    - strtol(3), strtoll(3)
    - strtof(3), strtod(3), strtold(3)

- misc
  * string.h(0P)
    - strfry(3)

- string(3)

process
-------
- process creation

  * unistd.h(0P)
    - fork(2)
    - execve(2)

- process termination

  * unistd.h(0P)
    - _exit(2)

  * stdlib.h(0P)
    - exit(3), EXIT_SUCCESS, EXIT_FAILURE
    - _Exit(3P)
    - atexit(3)
    - abort(3)

- memory allocations

  .. allocate and free

  * unistd.h(0P)
    - brk(2)
    - sbrk(2)

  * stdlib.h(0P)
    - malloc(3)
    - calloc(3)
    - realloc(3)
    - posix_memalign(3)
    - aligned_alloc(3)
    - free(3)

  .. debug

  * mcheck.h
    - mtrace(3)
    - muntrace(3)
    - mcheck(3)

  .. malloc tuning and status info

  * malloc.h
    - mallopt(3)
    - mallinfo(3)

  .. stack memory allocation

  * alloca.h
    - alloca(3)

- mmap and shared memory

  * sys/mman.h
    - mmap(2)
    - munmap(2)

  * sys/shm.h
    - shmat(2)
    - shmdt(2)

- environment

  * environ(8)

  * stdlib.h(0P)
    - getenv(3)
    - putenv(3)
    - setenv(3)
    - unsetenv(3)
    - clearenv(3)

- process credentials(7)

  * uids, gids, groups

    - unistd.h(0P)
      * getuid(2), geteuid(2)
      * getgid(2), getegid(2)

      * setuid(2), seteuid(2)
      * setgid(2), setegid(2)

      * getresuid(2), getresgid(2)
      * setresuid(2), setresgid(2)

      * setreuid(2), setregid(2) (painful)

      * getgroups(2), setgroups(2)

    - grp.h(0P)
      * initgroups(3)

    - sys/fsuid.h
      * setfsuid(2) (obsolete)
      * setfsgid(2) (obsolete)

  * process identifiers

    - unistd.h(0P)
      * getpid(2), getppid(2)
      * getpgid(2)
      * getpgrp(2)
      * getsid(2)

- resource usage

  * get info

    - sys/resource.h
      * getrusage(2)

  * usage limit

    - sys/resource.h
      * getrlimit(2)
      * setrlimit(2)
      * prlimit(2)

- nonlocal goto

  * setjmp.h(0P)
    - setjmp(3)
    - longjmp(3)

- process manipulation

  * sys/prctl.h
    - prctl(2)

dynamic library
---------------
- dlfcn.h(0P)
  * dlopen(3)
  * dlclose(3)
  * dlerror(3)
  * dlsym(3)
  * dlvsym(3)

- ltdl.h

cmdline
-------
- argument parsing

  * unistd.h(0P)
    - getopt(3)
    - optarg(3), optind(3), opterr(3), optopt(3)

  * getopt.h
    - getopt_long(3)
    - getopt_long_only(3)

  * stdlib.h(0P)
    - getsubopt(3)

  * argp.h
    - arg_parse

concurrency
-----------
- multiprocessing

  * unistd.h(0P)
    - fork(2)
    - execve(2)

  * sys/wait.h
    - wait(2)
    - waitpid(2)

- multithreading

  * pthread.h(0P)
    - pthread_create(3)
    - pthread_join(3)
    - pthread_exit(3)

interprocess communication
--------------------------
- signal

  * signal.h(0P), signal(2)

    - kill(2)

    - sigemptyset(3)
    - sigfullset(3)
    - sigaddset(3)
    - sigdelset(3)
    - sigismember(3)

    - sigprocmask(2)

- mmap

  * sys/mman.h
    - mmap(2)
    - munmap(2)

- shared memory

  * sys/shm.h
    - shmat(2)
    - shmdt(2)

time
----
- time(7)

- calendar time

  .. get

  * sys/time.h
    - gettimeofday(2) (obsolete)

  * time.h(0P)
    - time(2)

  .. set

  * sys/time.h
    - settimeofday(2) (obsolete)
    - adjtime(3)

  * time.h(0P)
    - stime(2) (obsolete)

- process time

  * sys/time.h
    - times(2)

  * time.h(0P)
    - clock(3)

- time conversion

  * time.h(0P)

    - gmtime(3), gmtime_r(3)
    - localtime(3), localtime_r(3)
    - mktime(3)

    - asctime(3), asctime_r(3) (obsolete)
    - strftime(3), strptime(3)

    - ctime(3), ctime_r(3) (obsolete)

- timezone

  * tzfile(5)

  * time.h(0P)
    - tzset(3)
    - tzname(3)
    - daylight(3)
    - timezone(3)

- RTC

  * rtc(4)

- HRTs

  * time.h(0P)
    - clock_getres(2)
    - clock_gettime(2)
    - clock_settime(2)

* unistd.h(0P)
  - sleep(3)

internationalization
--------------------
- wide character

  * wchar.h(0P)

  * uchar.h

  * wctype.h(0P), wctype(3)

- locale

  * locale(7)

  * locale.h(0P)
    - setlocale(3)
    - localeconv(3)

- iso646.h(0P)

terminal
--------

system configuration
--------------------
- sysconf(3)
- confstr(3)

system administration
---------------------
- reboot

  * unistd.h(0P)
    - reboot(2)

  * sys/reboot.h

- user account system

  * pwd.h(0P)

    .. get one entry

    - getpwnam(3)
    - getpwuid(3)

    .. reentrant version

    - getpwnam_r(3)
    - getpwuid_r(3)

    .. iterate all entries

    - getpwent(3)
    - setpwent(3)
    - endpwent(3)

    .. reentrant version

    - getpwent_r(3)
    - fgetpwent_r(3)

  * grp.h(0P)

    .. get one entry

    - getgrnam(3)
    - getgrgid(3)

    .. reentrant version

    - getgrnam_r(3)
    - getgrgid_r(3)

    .. iterate all entries

    - getgrent(3)
    - setgrent(3)
    - endgwent(3)

    .. reentrant version

    - getpwent_r(3)
    - fgetpwent_r(3)

  * shadow.h(3)
    - getspnam(3)
    - getspnam_r(3)

    - getspent(3)
    - getspent_r(3)
    - setspent(3)
    - endspent(3)

    - fgetspent(3)
    - fgetspent_r(3)
    - sgetspent(3)
    - sgetspent_r(3)

    - putspent(3)

    - lckpwdf(3)
    - ulckpwdf(3)

encryption
----------
- crypt.h

  * crypt(3)

math
----
- complex.h(0P), complex(7)

- math.h(0P)
  * pow(3), isnan(3), isinf(3), fabs(3), sqrt(3)

- tgmath.h(0P)

encryption
----------
- unistd.h(0P)
  * crypt(3)

- crypt.h
  * crypt_r(3)
  * crypt_data

algorithms
----------
- sorting

  * stdlib.h(0P)
    - qsort(3)

misc
----
- glibc

  * feature_test_macros(7)

  * attributes(7)

  * gnu/libc-version.h
    - gnu_get_libc_version(3)
    - gnu_get_libc_release(3)

- random number

  * stdlib.h(0P)
    - rand(3)
    - srand(3)
    - RAND_MAX

  * linux/random.h
    - urandom(4)
    - random(4)

- assertion
  * assert.h(0P)
    - assert(3)

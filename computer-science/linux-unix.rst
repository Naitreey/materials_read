Operating System Concepts
=========================
- Data buffer
  https://en.wikipedia.org/wiki/Data_buffer

Linux Overview
==============
- Learning the Unix Operating System (无笔记)
- Unix in a nutshell (在读)
- How Linux Works, 2nd Edition (在读)
- Fedora 22 System Administrator's Guide (在读)
- RHEL6 deployment guide (在读)

Distributions
=============

- identification

  * os-release(5)

- Arch Linux
  https://wiki.archlinux.org/index.php/Arch_Linux

  * Arch Linux FAQ
    https://wiki.archlinux.org/index.php/Frequently_asked_questions

  * Arch compared to other distributions
    https://wiki.archlinux.org/index.php/arch_compared_to_other_distributions

- Ubuntu

  * 17.10 Release Note
    https://wiki.ubuntu.com/ArtfulAardvark/ReleaseNotes

User System
===========
- sudo
  * https://help.ubuntu.com/community/RootSudo
  * https://help.ubuntu.com/community/Sudoers

System Components
=================
- Linux device mapper wiki
  https://en.wikipedia.org/wiki/Device_mapper
- Linux Logical Volume Manager (LVM) wiki
  https://en.wikipedia.org/wiki/Logical_Volume_Manager_(Linux)
- Power management/Suspend and hibernate wiki
  https://wiki.archlinux.org/index.php/Power_management/Suspend_and_hibernate
- upstart cookbook (obsolete, 作废)
- Debian and general Linux boot process
  https://wiki.debian.org/BootProcess
- 6 Stages of Linux Boot Process
  http://www.thegeekstuff.com/2011/02/linux-boot-process/
- systemd
  * http://0pointer.de/blog/projects/systemd-docs.html
  * systemd for Administrators:
    - http://0pointer.de/blog/projects/systemd-for-admins-1.html
    - http://0pointer.de/blog/projects/systemd-for-admins-2.html
    - http://0pointer.de/blog/projects/systemd-for-admins-3.html
    - http://0pointer.de/blog/projects/systemd-for-admins-4.html
    - http://0pointer.de/blog/projects/three-levels-of-off
    - http://0pointer.de/blog/projects/blame-game.html
    - http://0pointer.de/blog/projects/the-new-configuration-files
    - http://www.freedesktop.org/wiki/Software/systemd/
  * Predictable Network Interface Names
    - https://www.freedesktop.org/wiki/Software/systemd/PredictableNetworkInterfaceNames/
    - https://github.com/systemd/systemd/blob/master/src/udev/udev-builtin-net_id.c
- udev
  * udev wiki
    https://en.wikipedia.org/wiki/Udev
  * udev documentation
    https://www.kernel.org/pub/linux/utils/kernel/hotplug/udev/udev.html
  * Writing udev rules
    http://www.reactivated.net/writing_udev_rules.html
  * archlinux udev wiki
    https://wiki.archlinux.org/index.php/udev
  * /usr/lib/udev/rules.d 规则 (在读)
- D-Bus
  * wiki
    https://en.wikipedia.org/wiki/DBus
- syslog
  * logger(1), syslog(3), rsyslogd(8), journalctl(1) manpages
  * rsyslog documentation
    http://www.rsyslog.com/doc/master/index.html
  * syslog wiki
    https://en.wikipedia.org/wiki/Syslog
- scheduled tasks
  * at
  * cron
  * anacron
    - anacron wiki
      https://en.wikipedia.org/wiki/Anacron
    - anacron homepage
      http://anacron.sourceforge.net/
    - anacron(8)
    - /etc/anacrontab(8)
- SELinux
  * CentOS SELinux HowTo
    https://wiki.centos.org/HowTos/SELinux
- Pluggable Authentication Modules (PAM)
  * wiki
    https://en.wikipedia.org/wiki/Linux_PAM
  * pam(8) manpage
  * Understanding PAM Authentication and Security
    http://aplawrence.com/Basics/understandingpam.html
  * pam.d(5) manpage
  * pam_ftp(8) manpage
- initramfs, dracut
  * dracut wiki
    https://en.wikipedia.org/wiki/Dracut_(software)
  * dracut kernel wiki
    https://dracut.wiki.kernel.org/index.php/Main_Page
  * dracut kernel doc
    https://www.kernel.org/pub/linux/utils/boot/dracut/dracut.html
  * wwoods' notes on dracut: theory, operation, and good practice
    https://wwoods.fedorapeople.org/doc/dracut-notes.html
  * dracut source repo
- sysfs
  * The sysfs system by Patrick Mochel (在读, 涉及 kernel programming 的部分未读)
  * kernel sysfs documentation
    https://www.kernel.org/doc/Documentation/filesystems/sysfs.txt
- package management
  * DNF system upgrade
    https://fedoraproject.org/wiki/DNF_system_upgrade
  * How is it possible to do a live update while a program is running?
    http://unix.stackexchange.com/questions/138214/how-is-it-possible-to-do-a-live-update-while-a-program-is-running

Network Share and Printing
--------------------------
- Common Unix Printing System (CUPS)

  * mime database

    - mime.types(5)

Sound system
============
- PulseAudio

  * wiki
    https://en.wikipedia.org/wiki/PulseAudio

  * Why you should care about PulseAudio (and how to start doing it)
    https://www.linux.com/news/why-you-should-care-about-pulseaudio-and-how-start-doing-it

- Advanced Linux Sound Architecture (ALSA)

  * wiki
    https://en.wikipedia.org/wiki/Advanced_Linux_Sound_Architecture

System Programming
==================
- The Linux Programming Interface (在读)
- resource limit:
  http://serverfault.com/questions/356962/where-are-the-default-ulimit-values-set-linux-centos
- Upgrading: nuance about replacing executable
  http://unix.stackexchange.com/questions/138214/how-is-it-possible-to-do-a-live-update-while-a-program-is-running
- GNU C Library wiki
  https://en.wikipedia.org/wiki/GNU_C_Library
- The Linux Kernel Archives --- Active kernel releases
  https://www.kernel.org/category/releases.html
- Program memory segments wiki
  https://en.wikipedia.org/wiki/Data_segment#BSS
- Virtual memory wiki
  https://en.wikipedia.org/wiki/Virtual_memory

- Address space layout randomization (ASLR)
  https://en.wikipedia.org/wiki/Address_space_layout_randomization

Command Line
============
- Bash Reference Manual (已读)

- /dev/(tcp|udp)/ip/port as a weapon
  https://securityreliks.wordpress.com/2010/08/20/devtcp-as-a-weapon/

- Advanced Bash-Scripting Guide, by Mendel Cooper (在读)

- Learning the Bash Shell (在读)

- Bash CHANGES of each version
  https://tiswww.case.edu/php/chet/bash/CHANGES

- GNU Readline

  * move:
    - backward-char (C-b) (<Left>)
    - forward-char (C-f) (<Right>)
    - backward-word (M-b)
    - forward-word (M-f)
    - beginning-of-line (C-a)
    - end-of-line (C-e)
    - vi-fWord
    - vi-bWord (M-B)
    - character-search (C-])
    - character-search-backward (M-C-])

  * delete
    - C-h (<Backspace>)
    - delete-char (C-d) (<Del>)
    - backward-kill-word (M-<Backspace>)
    - kill-word (M-d)
    - kill-line (C-k)
    - unix-line-discard (C-u)
    - unix-word-rubout (C-w)

  * undo
    - undo (C-_, C-x C-u)

  * clear screen
    - clear-screen (C-l)

  * paste
    - C-y, M-y

  * accept line
    - accept-line (C-j) (C-m) (<Enter>)

  * search history
    - previous-history (C-p)
    - next-history (C-n)
    - reverse-search-history (C-r)
    - forward-search-history (C-s)
    - abort (C-g)

  * eof
    - end-of-file (C-d)

  * insert
    - quoted-insert (C-v)
    - self-insert
    - insert-comment (M-#)
    - shell-expand-line (M-C-e)
    - edit-and-execute-command (C-x C-e)

  * swap case
    - upcase-word (M-u)
    - downcase-word (M-l)
    - capitalize-word (M-c)

  * completion
    - complete (Tab)
    - menu-complete
    - complete-filename (M-/)
    - complete-username (M-~)
    - complete-variable (M-$)
    - complete-hostname (M-@)
    - complete-command (M-!)
    - complete-into-braces (M-{)

  * options
    - colored-stats
    - mark-directories
    - menu-complete-display-prefix
    - show-all-if-ambiguous
    - skip-completed-text

  * misc
   - re-read-init-file (C-x C-r)
   - prefix-meta (ESC)

  * cancel
   - ctrl-[ (ESC)

- cmdline utils:

  * shell: bash, sh

    - keywords and builtins::

      : . source printf echo cd pwd type umask
      exit if case select read trap exec eval
      dirs pushd popd ulimit hash [[ ]] test
      [ ] builtin command enable shopt set unset
      shift time times alias unalias until for
      while break continue coproc function return
      declare local readonly export getopts bind
      complete compgen compopt fc history caller
      help let logout mapfile readarray

    - history substituion::

      !n !-n !! !string !?string[?] :0 :n :^ :$
      :x-y :-y :* :x* :h :t :r :e :p :s/old/new/
      :gs/old/new/

    - job control::

      jobs fg bg kill wait disown suspend %n %%
      %string %?string suspend

  * system identification
    - uname(1)
    - hostnamectl(1)
    - machine-info(5)
    - machine-id(5)
    - screenfetch(1)

  * file access and manipulation

    - ls(1), stat(1), cat, tee(1), mv, less, vi,

    - chmod(1), chroot, chown, touch

    - head, tail, tr,

    - ln, readlink

    - dirname, mktemp

    - shred(1)

  * shell script cmdline parsing

    - getopt(1)

    - getopts(bash builtin)

  * file type

    - file(1)

  * mime type

    .. open by default mimetype-app association or update association

    - mimeopen(1)

    .. query mimetype via mime-info database

    - mimetype(1)

    .. update mime-info database cache

    - update-mime-database(1)

    .. update mimetype-app association cache

    - update-desktop-database(1)

  * xdg utils

    .. open by default DE app

    - xdg-open(1)

    .. query mimetype and default DE app, set default DE app, etc.

    - xdg-mime(1)

    .. (un)install xdg icon

    - xdg-icon-resource(1)

    .. DE settings

    - xdg-settings(1)

    .. directory settings

    - xdg-user-dir(1)

    - xdg-user-dirs-update(1)

  * KDE

    - kwin, kwin_x11

  * disk and filesystem

    - df, du, fdisk, gdisk, parted, gparted, mkfs.<type>, fsck.<type>, dumpe2fs, tune2fs, debugfs, mount, umount,
findmnt, blkid, lsblk, smartctl, smartd.conf, /etc/fstab (fstab(5)), /etc/mtab (mount(8)), /proc/mountinfo (proc(5)), sync,

    - mknod(1)

  * user account system

    - files:
      passwd(5), shadow(5), group(5), gshadow(5)

    - shadow conversion:
      pwconv(8), pwunconv(8), grpconv(8), grpunconv(8)

    - integrity check:
      pwck(8), grpck(8)

    - list membership:
      groups(1), lid(1), id(1)

    - make changes:
      useradd(8), usermod(8), passwd(1), chage(1), chsh(1)
      groupadd(8), groupmod(8), groupmemes(8), gpasswd(1)

    - edit manually:
      vipw(8), vigr(8)

    - login(1)

    - switch user/group:
      su(1), sg(1), newgrp(1)
      sudo(8), visudo(8)

  * calendar time, timezone
    - timedatectl(1)
    - date(1)
    - zdump(8)
    - zic(8)
    - time-sync.target

  * process time
    - time(1)

  * RTC
    - hwclock(8)
    - /etc/adjtime

  * locale
    - locale(1)
    - localectl(1)
    - locale.conf(5)
    - localedef(1)

  * font
    - setfont(8)

  * terminal

    - getty, chvt
    - script(1), scriptreplay(1)
    - wall(1)

  * package management

    - apt-get (install|update)
    - dnf (install|remove|erease|update|updateinfo)
    - yum
    - rpm

  * process and resource management

    - nice(1)


  * version control system

    - git

      * git (init|clone|branch|mv|status|remote|
        ls-remote|merge|mergetool|merge-base|
        merge-file|pull|fetch|push|commit|
        commit-tree|log|shortlog|checkout|
        show-branch|ls-files|ls-tree|read-tree|
        write-tree|hash-object|cat-file|rm|add|
        stash|config|var|diff|difftool|diff-tree|
        diff-index|apply|rebase|reset|revert|tag|
        show|instaweb|clean|cherry-pick|cherry|
        reflog|submodule|subtree|filter-branch|request-pull|
        format-patch|am|send-email|rev-parse|
        rev-list|rerere|describe|grep|blame|bisect|
        update-index|update-ref|symbolic-ref|
        archive|bundle|gc|prune|fsck|count-objects|
        help|credential|credential-cache|
        credential-cache--daemon|
        credential-gnome-keyring|credential-store|
        replace|update-server-info|send-pack|
        receive-pack|version)

      * git-shell, gitignore(5), gitrevisions(7),
        gitattributes(5), githooks(5), gitcredentials(7), gitmodules(5)

      * git annex (init|add|copy|move|describe|
        drop|dropunused|initremote|enableremote|
        numcopies|unused|)

    - svn

      * svn (commit|checkout|log)

  * backup tools

    - bup

      * bup(1)

      * bup init(1)

      * bup index(1)

      * bup save(1)

      * bup ls(1)

  * container

    - runc (start|spec|kill|list)

    - docker
      * docker pull(1)
      * docker images(1), docker image ls(1)
      * docker run(1)
      * docker start(1)
      * docker stop(1), docker container stop(1)
      * docker build(1)
      * docker tag(1), docker image tag(1)
      * docker rm(1), docker container rm(1)
      * docker rmi(1), docker image rm(1)
      * docker login(1)
      * docker logout(1)
      * docker push(1), docker image push(1)
      * docker port(1), docker container port(1)
      * docker events(1), docker system events(1)
      * docker info(1), docker system info(1)
      * docker ps(1), docker container ls(1)
      * docker volume create(1)
      * docker volume ls(1)
      * docker volume inspect(1)
      * docker-compose
      * docker-commit(1), docker container commit(1)
      * (create|rename|
      stop|kill|attach|export|logs|
      history|exec)

  * language tools
    - python
      * python2(1)
      * python3(1)
      * pip2
      * pip3 (install|download|uninstall|freeze|list|show|
              search|wheel|hash|completion|help)
      * wheel
      * 2to3
      * pyenv
      * ipython

    - ghc, stack, cabal, hoogle

  * computing

    - jupyter

  * unix manuals

    .. read

    - man(1), whatis(1), apropos(1), manpath(1)

    .. generate

    - mandb(8), catman(1), manconv(1)

    .. config

    - man_db.conf

  * searching files

    - locate(1), updatedb(8), updatedb.conf(5)

  * system limits and options
    - getconf(1P)

  * network management

    - firewall
      * iptables(8), iptables-extensions(8)

    - ipset(8)

    - hostname and FQDN
      * hostname(1), dnsdomainname(1)
      * hostname(5), hostname(7)
      * systemd-hostnamed(8), systemd-hostnamed.service(8)

    - DNS

      * dnsmasq(8)

  * scheduled tasks

    - periodic schedule
      * crontab(1)
      * crond(8)
      * run-parts/crontabs(4)
      * crontab(5)

    - fuzzy schedule
      * anacron(8)
      * /etc/anacrontab(8)

    - one-time schedule
      * at(1), atq(1), atrm(1), batch(1)
      * /etc/at.allow(5), /etc/at.deny(5)
      * atd(8)

  * kernel configuration

    - sysctl(8)

  * memory, cache, swap

    - fincore(1)

  * error code

    - perror(1)

  * hardware info

    - lsusb(1)

  * database tools

    - mysql(1), mycli, mysqld(8), mysqldump(1), mysqlimport(1)

    - sqlite3

    - psql

    - mongo, mongod, mongodump, mongorestore, mongoexport, mongoimport

  * systemd

    - systemctl (status|start|stop|restart|enable|disable|
      list-units|list-unit-files|list-jobs|poweroff|reboot|
      suspend)

    - systemd-analyze (blame|plot|dot)

    - systemd-cgls

    - systemd-udevd

    - journalctl, systemd-journald.service(8), systemd-journald.socket(8),
      systemd-journald-dev-log.socket(8), /usr/lib/systemd/systemd-journald(8)

    - logind.conf(5)

  * automation tools

    - salt

      * salt-key(1)

      * salt-call(1)

      * salt-run(1)

      * salt-ssh(1)

    \begin{enumerate}
        \item xinput, xclip,
        \item alternatives
        \item pwdx
        \item rm, unlink(1), mkdir, rmdir(1),
        \item locate,  env(1), printenv(1), which,
        \item dd, dmesg, lsof, printf
        \item w, who, whoami, uptime, tty, whois (jwhois),
        \item seq
        \item pgrep, pkill, kill, kill, killall, pidof, ps(1), top(1)
        \item grep, bzgrep, xzgrep, zgrep, zipgrep, find, xargs
        \item texdoc
        \item shutdown, poweroff, reboot
        \item column, uniq, sort
        \item dmidecode
        \item sed, awk, gawk, cut, expect
        \item tar, gzip, gunzip, zcat, bzip2, bunzip2, bzcat, xz, unxz, xzcat, 7z, 7za, zip, unzip,
        \item md5sum
        \item dos2unix, unix2dos
        \item userdel
        \item service, run-parts, telinit, lsscsi
        \item udev.conf(5), udevadm(8), udev(7), systemd-udevd.service(8)
        \item dracut(8), lsinitrd(1), mkinitrd(8), dracut.cmdline(7), dracut.conf(5), dracut.modules(7), dracut.bootup(7), dracut-cmdline.service(8),
        \item screen
        \item samba, free, mkswap, swapon, swapoff, dmsetup, lspci, ionice, iotop
        \item console_codes(4)
        \item grub2-install, grub2-mkconfig
        \item ssh, ssh-keygen, ssh-copy-id, sshpass sftp, ftp, scp, telnet, netcat (nc), wget, curl, rsync, nslookup, tcpdump
        \item ar(1), ranlib(1)
        \item ctags, cscope(1)
        \item make, diff, patch, ldd, strings, pmap, taskset
        \item gvim, vim, gvimdiff
        \item pydoc2, pydoc3
        \item node, npm
        \item java, javac
        \item ping
        \item arp, arping
        \item ip(8), ip (route|maddress|neighbour)
        \item traceroute(1)
        \item whois (jwhois)
        \item virsh (list|
                   create|start|shutdown|destroy|
                   dompmsuspend|dompmwakeup|
                   define|
                   capabilities)
        \item qemu-img (create|convert|info|snapshot)
        \item bluetoothctl
        \item vncviewer
        \item okular
        \item mail
        \item beanstalkd
        \item expressvpn,
        \item wdctl
        \item feature_test_macros(7)
    \end{enumerate}
\item bash init procedures:
    \begin{itemize}
        \item /etc/profile
    \end{itemize}
\item dd wiki \url{https://en.wikipedia.org/wiki/Dd_(Unix)}
\item benchmark disk with dd \url{https://romanrm.net/dd-benchmark}
\item docopt: Command-line interface description language \url{http://docopt.org/}
\item customize terminal prompt (无笔记)
\item description about p, x, etc. manpage sections: \url{http://unix.stackexchange.com/questions/204501/what-are-the-n-l-3pm-sections-of-the-manual-for}
\item background process, daemon, etc
    \begin{itemize}
        \item background process on shell exit: \url{http://stackoverflow.com/questions/32780706/does-linux-kill-background-processes-if-we-close-the-terminal-from-which-it-has}, \url{http://superuser.com/questions/662431/what-exactly-determines-if-a-backgrounded-job-is-killed-when-the-shell-is-exited}, \url{http://unix.stackexchange.com/questions/3886/difference-between-nohup-disown-and#}, \url{http://unix.stackexchange.com/questions/4004/how-can-i-close-a-terminal-without-killing-the-command-running-in-it}
    \end{itemize}
\item suid on interpreted programs: \url{http://unix.stackexchange.com/questions/364/allow-setuid-on-shell-scripts}
\item AWK programming
    \begin{enumerate}
        \item The AWK Programming Language (在读)
    \end{enumerate}

Bootloader
==========
- GRUB

  * Python without an operating system
    https://lwn.net/Articles/641244/

Kernel
======

pseudo-filesystem
-----------------

/dev
~~~~
- mem(4), kmem(4), port(4)

/proc
~~~~~
- proc(5)

graphics
--------
- Direct Rendering Manager (DRM)
  * DRM wiki https://en.wikipedia.org/wiki/Direct_Rendering_Manager
  * Kernel Mode Setting wiki https://en.wikipedia.org/wiki/Mode_setting
  * KMS archlinux wiki
    https://wiki.archlinux.org/index.php/Kernel_mode_setting#Forcing_modes_and_EDID

runtime configuration
---------------------
- sysctl
  * administrator
    - sysctl(8)
    - sysctl.conf(5)
  * bootup
    - systemd-sysctl(8)
    - systemd-sysctl.service(8)
    - sysctl.d(5)

misc
----
Magic SysRq key
~~~~~~~~~~~~~~~
- wiki
  https://en.wikipedia.org/wiki/Magic_SysRq_key

Networking
==========

DNS
---

- dnsmasq

  * wiki
    https://en.wikipedia.org/wiki/Dnsmasq

  * introduction on home page
    http://www.thekelleys.org.uk/dnsmasq/doc.html

  * manpage: dnsmasq(8)

ARP
---
- /etc/ethers(5)

Firewall & NAT
--------------
- netfilter

- iptables

  * iptables(8)

  * iptables-extensions(8)

- ipset

  * introduction on home page
    http://ipset.netfilter.org/

  * features
    http://ipset.netfilter.org/features.html

  * tips
    http://ipset.netfilter.org/tips.html

  * ipset(8)

  * Advanced Firewall Configuration with ipset
    http://www.linuxjournal.com/content/advanced-firewall-configurations-ipset

Desktop Environment
===================

GNOME, GTK
----------

GNOME
~~~~~
- gnome wiki
  https://en.wikipedia.org/wiki/GNOME
- gnome newcomers guide
  https://wiki.gnome.org/Newcomers/
- gnome project tour
  https://wiki.gnome.org/Newcomers/ProjectTour
- gnome IRC
  https://wiki.gnome.org/Community/GettingInTouch/IRC
- Tools and tricks for solving tasks in a GNOME project
  https://wiki.gnome.org/Newcomers/FindAndSolveTasks
- PDF viewer
  * evince wiki
    https://en.wikipedia.org/wiki/Evince
  * poppler wiki
    https://en.wikipedia.org/wiki/Poppler_(software)
- jhbuild
  * build gnome: Set up JHBuild
    https://wiki.gnome.org/Newcomers/BuildGnome
- Choose Application ID
  https://wiki.gnome.org/HowDoI/ChooseApplicationID
- Beautiful Buttons
  https://wiki.gnome.org/HowDoI/Buttons

GTK
~~~
- Compiling GTK+ Applications
  https://developer.gnome.org/gtk3/stable/gtk-compiling.html
- Getting Started with GTK+
  https://developer.gnome.org/gtk3/stable/gtk-getting-started.html
- GtkInspector
  https://wiki.gnome.org/Projects/GTK%2B/Inspector

KDE
---
- KDE Wallet

  * Arch Linux wiki
    https://wiki.archlinux.org/index.php/KDE_Wallet

font configuration
------------------

- Arch Linux 中文字体配置 wiki
  https://wiki.archlinux.org/index.php/Font_Configuration/Chinese_Font_Configurations_(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87)

IME
---
- Fcitx 小企鹅输入法

  * Arch Linux wiki
    https://wiki.archlinux.org/index.php/Fcitx_(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87)

Development Tools
=================

Build Systems
-------------

GNU Build System
~~~~~~~~~~~~~~~~
- GNU Make wiki
  https://en.wikipedia.org/wiki/Make_(software)
- Autotools: A Practitioner's Guide to GNU Autoconf, Automake, and Libtool (在读)
- m4 wiki
  https://en.wikipedia.org/wiki/M4_(computer_language)

Virtualization
==============

General Introductions
---------------------
- Hardware virtualization wiki
  https://en.wikipedia.org/wiki/Hardware_virtualization
- Virtual Linux: An overview of virtualization methods, architectures, and implementations
  https://web.archive.org/web/20080327111126/http://www-128.ibm.com/developerworks/linux/library/l-linuxvirt/?ca=dgr-lnxw01Virtual-Linux
- Fedora Virtualization intro
  https://fedoraproject.org/wiki/Virtualization?rd=Tools/Virtualization
- Fedora Getting started with virtualization
  https://fedoraproject.org/wiki/Getting_started_with_virtualization
- hardware emulation wiki
  https://en.wikipedia.org/wiki/Emulator
- full virtualization wiki
  https://en.wikipedia.org/wiki/Full_virtualization
- hardware-assisted virtualization wiki
  https://en.wikipedia.org/wiki/Hardware-assisted_virtualization
- paravirtualization wiki
  https://en.wikipedia.org/wiki/Full_virtualization
- operating-system-level virtualization
  https://en.wikipedia.org/wiki/Operating-system-level_virtualization
- hypervisor wiki
  https://en.wikipedia.org/wiki/Hypervisor

Management Tool: libvirt
------------------------
- libvirt wiki
  https://en.wikipedia.org/wiki/Libvirt
- Domain XML format
  http://libvirt.org/formatdomain.html
- Driver capabilities XML format
  http://libvirt.org/formatcaps.html

QEMU (hardware emulation, full virtualization)
----------------------------------------------
- QEMU wiki
  https://en.wikipedia.org/wiki/QEMU
- QEMU wikibook
  https://en.wikibooks.org/wiki/QEMU
- How to use qemu
  https://fedoraproject.org/wiki/How_to_use_qemu#Qemu_commands_since_F.3F.2B

KVM (hardware-assisted virtualization, paravirtualization)
----------------------------------------------------------
- Kernel-based Virtual Machine wiki
  https://en.wikipedia.org/wiki/Kernel-based_Virtual_Machine
- Difference between KVM and QEMU
  http://serverfault.com/questions/208693/difference-between-kvm-and-qemu
- windows virtio drivers
  https://fedoraproject.org/wiki/Windows_Virtio_Drivers#Direct_download
- QEMU/Windows guest
  https://wiki.gentoo.org/wiki/QEMU/Windows_guest
- Example using SPICE and QXL for improved Graphics experience in the guest
  http://www.linux-kvm.org/page/SPICE

chroot
------

open container, runC, docker (os-level virtualization)
------------------------------------------------------
- Open Container Specifications
  https://github.com/opencontainers/specs
- OCI FAQs
  https://www.opencontainers.org/faq

runC
~~~~

- runC homepage Getting Started
  https://runc.io/
- runC readme
  https://github.com/opencontainers/runc

docker
~~~~~~
- docker wiki
  https://en.wikipedia.org/wiki/Docker_(software)

- 8 Proven Real-World Ways to Use Docker
  https://www.airpair.com/docker/posts/8-proven-real-world-ways-to-use-docker

- docker documentation

  * Get started with Docker
    https://docs.docker.com/engine/getstarted/

  * Define and deploy your app
    https://docs.docker.com/engine/getstarted-voting-app/

  * Docker Engine

    - Overview
      https://docs.docker.com/engine/userguide/

    - Best practices for writing Dockerfiles
      https://docs.docker.com/engine/userguide/eng-image/dockerfile_best-practices/

  * Docker Compose

    - Overview of Docker Compose
      https://docs.docker.com/compose/overview/

    - Install Docker Compose
      https://docs.docker.com/compose/install/

    - Get started with Docker Compose
      https://docs.docker.com/compose/gettingstarted/

  * Docker Registry

    - Registry overview
      https://docs.docker.com/registry/

    - Understanding the registry
      https://docs.docker.com/registry/introduction/

    - Deploy a registry server
      https://docs.docker.com/registry/deploying/

    - Configuring a registry
      https://docs.docker.com/registry/configuration/

    - Working with notifications
      https://docs.docker.com/registry/notifications/

    - Recipes

      * Testing an insecure registry
        https://docs.docker.com/registry/insecure/

      * Registry as a pull through cache of docker hub
        https://docs.docker.com/registry/recipes/mirror/

Storage
=======

- HDD Advanced Format
  https://wiki.archlinux.org/index.php/Advanced_Format

File Systems
------------

Union mount, overlayfs
~~~~~~~~~~~~~~~~~~~~~~
- Union mount
  https://en.wikipedia.org/wiki/Union_mount
- OverlayFS
  https://en.wikipedia.org/wiki/OverlayFS
- kernel documentation
  https://www.kernel.org/doc/Documentation/filesystems/overlayfs.txt
- Arch linux overlayfs wiki
  https://wiki.archlinux.org/index.php/Overlay_filesystem

sparse file
~~~~~~~~~~~
- sparse file wiki
  https://en.wikipedia.org/wiki/Sparse_file

\subsubsection{Misc}
%
\begin{itemize}
    \item watchdog timer
        \begin{itemize}
            \item watchdog kernel documentation https://www.kernel.org/doc/Documentation/watchdog/watchdog-api.txt
        \end{itemize}
\end{itemize}
%
\subsubsection{History}
%
\begin{itemize}
    \item fedora wiki \url{https://en.wikipedia.org/wiki/Fedora_(operating_system)}
    \item RHEL wiki \url{https://en.wikipedia.org/wiki/Red_Hat_Enterprise_Linux}
    \item the relationship between Fedora and RHEL
        \begin{itemize}
            \item What is the relationship between Fedora and Red Hat Enterprise Linux? \url{https://www.redhat.com/en/technologies/linux-platforms/articles/relationship-between-fedora-and-rhel}
            \item fedora wiki: Red Hat Enterprise Linux {https://fedoraproject.org/wiki/Red_Hat_Enterprise_Linux}
            \item Red Hat Enterprise Linux derivatives \url{https://en.wikipedia.org/wiki/Red_Hat_Enterprise_Linux_derivatives}
        \end{itemize}
    \item Bell Labs \url{https://en.wikipedia.org/wiki/Bell_Labs}
    \item Computer Systems Research Group wiki \url{https://en.wikipedia.org/wiki/Computer_Systems_Research_Group}
    \item Andrew Tanenbaum \url{https://en.wikipedia.org/wiki/Andrew_S._Tanenbaum}
    \item Bill Joy \url{https://en.wikipedia.org/wiki/Bill_Joy}
    \item Novell \url{https://en.wikipedia.org/wiki/Novell}
    \item Unix System Laboratories \url{https://en.wikipedia.org/wiki/Unix_System_Laboratories}
\end{itemize}

FreeBSD
=======

Command line
------------
CPU
~~~

- sysctl kern.sched.topology_spec

- sysctl -n hw.model

- sysctl -n dev.cpu.N.freq

memory
~~~~~~

- sysctl -n hw.physmem

- swapinfo

disk
~~~~

- camcontrol devlist

- sysctl -n kern.disks

- diskinfo <name>

NIC
~~~

- ifconfig

PCIe
~~~~

- pciconf

All Unixes
==========

- Tools comparison for every Unix flavors:

  * A Sysadmin's Unixersal Translator (ROSETTA STONE)
    http://bhami.com/rosetta.html

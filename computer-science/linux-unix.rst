System Overview
===============
- Learning the Unix Operating System (无笔记)
- Unix in a nutshell (在读)
- How Linux Works, 2nd Edition (在读)
- Fedora 22 System Administrator's Guide (在读)
- RHEL6 deployment guide (在读)
- IPC wiki
  https://en.wikipedia.org/wiki/Inter-process_communication

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
    https://www.freedesktop.org/wiki/Software/systemd/PredictableNetworkInterfaceNames/
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
  * anacron wiki
    https://en.wikipedia.org/wiki/Anacron
- iptables
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
- PXE
  * Preboot Execution Environment wiki
    https://en.wikipedia.org/wiki/Preboot_Execution_Environment
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

Command Line
============
- Bash Reference Manual (已读)
- /dev/(tcp|udp)/ip/port as a weapon
  https://securityreliks.wordpress.com/2010/08/20/devtcp-as-a-weapon/
- Advanced Bash-Scripting Guide, by Mendel Cooper (在读)
- Learning the Bash Shell (在读)
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

  * file access and manipulation
    - ls, stat, cat, tee(1), mv, less, vi,
    - chmod(1), chroot, chown, touch, file,
    - head, tail, tr,
    - ln, readlink
    - dirname, mktemp,

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

  * terminal

    - getty, chvt
    - script(1), scriptreplay(1)
    - wall(1)

  * package management

    - apt-get (install|update)
    - dnf (install|remove|erease|update|updateinfo)
    - yum
    - rpm

  * disk and filesystem

df, du, fdisk, gdisk, parted, gparted, mkfs.<type>, fsck.<type>, dumpe2fs, tune2fs, debugfs, mount, umount,
findmnt, blkid, lsblk, smartctl, smartd.conf, /etc/fstab (fstab(5)), /etc/mtab (mount(8)), /proc/mounts (proc(5)), sync,

  * process and resource monitor


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
        reflog|submodule|filter-branch|request-pull|
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
        drop|dropunused|initremote|numcopies|unused|)

    - svn

      * svn (commit|checkout|log)

  * container

    - runc (start|spec|kill|list)
    - docker (build|run|images|create|commit|rename|
      rm|rmi|ps|start|stop|kill|attach|export|logs|
      port|history|exec)

    \begin{enumerate}
        \item mknod
        \item xinput, xclip,
        \item alternatives
        \item pwdx
        \item rm, unlink(1), mkdir, rmdir(1),
        \item locate,  env(1), printenv(1), which,
        \item uname, dd, dmesg, lsof, printf
        \item w, who, whoami, uptime, tty, whois (jwhois),
        \item seq
        \item pgrep, pkill, kill, kill, killall, pidof, nice, ps(1), top(1)
        \item grep, bzgrep, xzgrep, zgrep, zipgrep, locale, find, xargs
        \item date, hwclock (clock)
        \item man, apropos, mandb, info
        \item texdoc
        \item shutdown, poweroff, reboot
        \item column, uniq, sort
        \item dmidecode
        \item sed, awk, gawk, cut, expect
        \item tar, gzip, gunzip, zcat, bzip2, bunzip2, bzcat, xz, unxz, xzcat, 7z, 7za, zip, unzip,
        \item md5sum
        \item dos2unix, unix2dos
        \item userdel
        \item systemctl (status|start|stop|restart|enable|disable|list-units|list-unit-files|list-jobs|poweroff|reboot|suspend), systemd-analyze (blame|plot|dot), systemd-cgls, systemd-udevd, journalctl, logind.conf(5), systemd-journald.service(8), systemd-journald.socket(8), systemd-journald-dev-log.socket(8), /usr/lib/systemd/systemd-journald(8),
        \item service, run-parts, telinit, lsscsi, lsusb
        \item udev.conf(5), udevadm(8), udev(7), systemd-udevd.service(8)
        \item dracut(8), lsinitrd(1), mkinitrd(8), dracut.cmdline(7), dracut.conf(5), dracut.modules(7), dracut.bootup(7), dracut-cmdline.service(8),
        \item screen
        \item samba, free, mkswap, swapon, swapoff, dmsetup, lspci, ionice, iotop
        \item console_codes(4)
        \item proc(5)
        \item grub2-install, grub2-mkconfig
        \item ssh, ssh-keygen, ssh-copy-id, sshpass sftp, ftp, scp, telnet, netcat (nc), wget, curl, rsync, nslookup, tcpdump
        \item hostname
        \item ar(1), ranlib(1)
        \item ctags, cscope(1)
        \item make, diff, patch, ldd, strings, pmap, taskset, getopt(1)
        \item gvim, vim, gvimdiff
        \item python2, python3, pip2, pip3, pydoc2, pydoc3
        \item node, npm
        \item java, javac
        \item ping, iptables
        \item arp, arping
        \item ip (route|maddress|neighbour)
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
        \item sqlite3
        \item psql
        \item mongo, mongod, mongodump, mongorestore, mongoexport, mongoimport
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

Kernel
======
pseudo-filesystem
-----------------
/dev
~~~~
- mem(4), kmem(4), port(4)
%
\subsubsection{Networking}
%
\begin{itemize}
\end{itemize}
%
\subsubsection{Desktop environment}
%
\begin{itemize}
    \item GNOME
        \begin{itemize}
            \item gnome wiki \url{https://en.wikipedia.org/wiki/GNOME}
            \item gnome newcomers guide \url{https://wiki.gnome.org/Newcomers/}
            \item gnome project tour \url{https://wiki.gnome.org/Newcomers/ProjectTour}
            \item gnome IRC \url{https://wiki.gnome.org/Community/GettingInTouch/IRC}
            \item Tools and tricks for solving tasks in a GNOME project
                  \url{https://wiki.gnome.org/Newcomers/FindAndSolveTasks}
            \item evince
                \begin{itemize}
                    \item evince wiki \url{https://en.wikipedia.org/wiki/Evince}
                    \item poppler wiki \url{https://en.wikipedia.org/wiki/Poppler_(software)}
                \end{itemize}
            \item jhbuild
                \begin{itemize}
                    \item build gnome: Set up JHBuild \url{https://wiki.gnome.org/Newcomers/BuildGnome}
                \end{itemize}
            \item Choose Application ID
                  \url{https://wiki.gnome.org/HowDoI/ChooseApplicationID}
            \item Beautiful Buttons
                  \url{https://wiki.gnome.org/HowDoI/Buttons}
            \item Compiling GTK+ Applications
                  \url{https://developer.gnome.org/gtk3/stable/gtk-compiling.html}
        \end{itemize}
    \item GTK
        \begin{itemize}
            \item Getting Started with GTK+
                  \url{https://developer.gnome.org/gtk3/stable/gtk-getting-started.html}
            \item GtkInspector \url{https://wiki.gnome.org/Projects/GTK\%2B/Inspector}
        \end{itemize}
\end{itemize}
%
\subsubsection{Development Tools}
%
\begin{itemize}
    \item build systems
        \begin{itemize}
            \item GNU build system
                \begin{itemize}
                    \item GNU Make wiki \url{https://en.wikipedia.org/wiki/Make_(software)}
                    \item Autotools: A Practitioner's Guide to GNU Autoconf, Automake, and Libtool (在读)
                    \item m4 wiki \url{https://en.wikipedia.org/wiki/M4_(computer_language)}
                \end{itemize}
        \end{itemize}
\end{itemize}
%
\subsubsection{Virtualization}
%
\begin{itemize}
    \item general introduction
        \begin{itemize}
            \item Hardware virtualization wiki \url{https://en.wikipedia.org/wiki/Hardware_virtualization}
            \item Virtual Linux: An overview of virtualization methods, architectures, and implementations \url{https://web.archive.org/web/20080327111126/http://www-128.ibm.com/developerworks/linux/library/l-linuxvirt/?ca=dgr-lnxw01Virtual-Linux}
            \item Fedora Virtualization intro \url{https://fedoraproject.org/wiki/Virtualization?rd=Tools/Virtualization}
            \item Fedora Getting started with virtualization \url{https://fedoraproject.org/wiki/Getting_started_with_virtualization}
            \item hardware emulation wiki \url{https://en.wikipedia.org/wiki/Emulator},
                  full virtualization wiki \url{https://en.wikipedia.org/wiki/Full_virtualization},
                  hardware-assisted virtualization wiki \url{https://en.wikipedia.org/wiki/Hardware-assisted_virtualization},
                  paravirtualization wiki \url{https://en.wikipedia.org/wiki/Full_virtualization},
                  operating-system-level virtualization \url{https://en.wikipedia.org/wiki/Operating-system-level_virtualization}
            \item hypervisor wiki \url{https://en.wikipedia.org/wiki/Hypervisor}
        \end{itemize}
    \item management tool: libvirt
        \begin{itemize}
            \item libvirt wiki \url{https://en.wikipedia.org/wiki/Libvirt}
            \item Domain XML format \url{http://libvirt.org/formatdomain.html}
            \item Driver capabilities XML format \url{http://libvirt.org/formatcaps.html}
        \end{itemize}
    \item QEMU (hardware emulation, full virtualization)
        \begin{itemize}
            \item QEMU wiki \url{https://en.wikipedia.org/wiki/QEMU}
            \item QEMU wikibook \url{https://en.wikibooks.org/wiki/QEMU}
            \item How to use qemu \url{https://fedoraproject.org/wiki/How_to_use_qemu#Qemu_commands_since_F.3F.2B}
        \end{itemize}
    \item KVM (hardware-assisted virtualization, paravirtualization)
        \begin{itemize}
            \item Kernel-based Virtual Machine wiki \url{https://en.wikipedia.org/wiki/Kernel-based_Virtual_Machine}
            \item Difference between KVM and QEMU \url{http://serverfault.com/questions/208693/difference-between-kvm-and-qemu}
            \item windows virtio drivers \url{https://fedoraproject.org/wiki/Windows_Virtio_Drivers#Direct_download}
            \item QEMU/Windows guest \url{https://wiki.gentoo.org/wiki/QEMU/Windows_guest}
            \item Example using SPICE and QXL for improved Graphics experience in the guest \url{http://www.linux-kvm.org/page/SPICE}
        \end{itemize}
    \item chroot
    \item open container, runC, docker (os-level virtualization)
        \begin{itemize}
            \item Open Container Specifications \url{https://github.com/opencontainers/specs}
            \item OCI FAQs \url{https://www.opencontainers.org/faq}
            \item runC homepage Getting Started \url{https://runc.io/}
            \item runC readme \url{https://github.com/opencontainers/runc}
            \item docker wiki \url{https://en.wikipedia.org/wiki/Docker_(software)}
            \item docker documentation: Get Started with Docker Engine for Linux https://docs.docker.com/linux/
            \item docker documentation: Understand the architecture \url{https://docs.docker.com/engine/understanding-docker/}
            \item docker documentation: Quickstart Docker Engine \url{https://docs.docker.com/engine/quickstart/}
        \end{itemize}
\end{itemize}
%
\subsubsection{File Systems}
%
\begin{itemize}
    \item Union mount, overlayfs
        \begin{itemize}
            \item Union mount https://en.wikipedia.org/wiki/Union_mount
            \item OverlayFS https://en.wikipedia.org/wiki/OverlayFS
            \item kernel documentation https://www.kernel.org/doc/Documentation/filesystems/overlayfs.txt
            \item Arch linux overlayfs wiki https://wiki.archlinux.org/index.php/Overlay_filesystem
        \end{itemize}
    \item sparse file wiki \url{https://en.wikipedia.org/wiki/Sparse_file}
\end{itemize}
\subsubsection{Regular Expression}
\begin{enumerate}
    \item Mastering Regular Expression (在读)
\end{enumerate}
%
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

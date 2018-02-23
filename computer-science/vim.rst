Overview
========
- Vim tutor

- Practical Vim, by Drew Neil (在读)

- Vim documentations

  * usr_40.txt (在读)

  * if_cscop.txt (cscope)

commands
========

\item movement
    h, j, k, l, w, W, e, E, ^, $, gg, G, {n}G, /{char}, ?{char}, n, N, ``*``,
    <C-o>, <C-i>, f, F, t, T, ;, ``,``, zz,
\item editing
    \begin{itemize}
        \item cmdline mode
            :w, :wa, :wq, :wqa, <C-p>, <C-n>, \%, :h, :sort
        \item normal mode
            a, A, I, i, x, d, dd, D, gU, gu, u, <C-r>, r, R, c, C, s, S,
            v, V, <C-v>, o, O, y, yy, Y, >, >>, <, <<, ., <C-a>, <C-x>
        \item insert mode
            <C-k>, <C-v>, <ESC>,
    \end{itemize}
\item info
    <C-g>, ga,
\item session
    <C-z>
\item tab
    \begin{itemize}
        \item cmdline mode
            :tabnew, :tabclose
            :tabfirst, :tablast, :tabnext, :tabprevious
        \item normal mode
            gt, gT
    \end{itemize}
\item working directory
    :lcd, :cd
\item buffer
    :buffer,

Plugins
=======

Vim-LaTeX
---------
- Vim-LaTeX reference (剩下后面需要理解 vimscript 的部分)

- Vim-LaTeX reference card
  
powerline
---------

- powerline documentation
  https://powerline.readthedocs.io/en/latest/

  * overview
    https://powerline.readthedocs.io/en/latest/overview.html

  * installation on linux
    https://powerline.readthedocs.io/en/latest/installation/linux.html

    - Application-specific requirements
      https://powerline.readthedocs.io/en/latest/usage.html

    - shell prompt
      https://powerline.readthedocs.io/en/latest/usage/shell-prompts.html


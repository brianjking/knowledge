Windows 10 Bash (WSL)
========================

See `Windows 10 Bash wiki <https://github.com/bootstraponline/meta/wiki/Windows_10_Bash>`_ for more info.

Using ZSH as Default $SHELL
-------------------------------

* Add the following to .bash_profile or .bashrc (to the top)

    if [[ $- == *i* ]]; then
        export SHELL=zsh
        exec zsh -l
    fi

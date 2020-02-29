# 🐈 configs
🐈 Meow, meow-meow-meow, meow-meow, meow.

1. `cd ~`
2. `git clone git@github.com:psyanite/configs.git .meow-configs`
3. `cd .meow-configs`
4. `cp .bashrc ../.bashrc`
5. `cp .gitconfig ../.gitconfig`
6. `cp git-prompt.sh  /c/Program\ Files/Git/etc/profile.d/git-prompt.sh`
7. `cp ssh/config ../.ssh/config`


### Add history commands for up down arrows
Add the following text to  `~/.inputrc`
```
"\e[A": history-search-backward
"\e[B": history-search-forward
```

# .dotfiles
Config files for various utilities

Built by following along with [these docs](https://www.electricmonk.nl/log/2015/06/22/keep-your-home-dir-in-git-with-a-detached-working-directory/).

## Deploying to a new machine

```
git clone git@github.com:NapsterInBlue/.dotfiles.git
alias dgit='git --git-dir ~/.dotfiles/.git --work-tree=$HOME'
dgit reset --hard
```

## Updating

Same workflow, but with `dgit` instead of `git`. Adding new files will require an `-f` tag to any `git add` commands.

## Getting `make` on Windows

https://gist.github.com/evanwill/0207876c3243bbb6863e65ec5dc3f058#make

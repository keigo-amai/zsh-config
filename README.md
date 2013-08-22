## install

* Make Directory which install this repository
* git clone this repository

```
$ mkdir ~/my-config
$ cp ~/my-config
$ git clone git@github.com:shingo-nakanishi/zsh-config.git
```

### Edit ~/.zshrc
Edit `~/.zshrc`.  

Be careful This mean your `~/.zshrc` is deleted.

```
ZDOTDIR=$HOME/my-config/zsh-config

export ZDOTDIR

. $ZDOTDIR/zshrc.sh
```

## Option
This zsh-config use [olivierverdier/zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
But This part is comment outed.
If you want to [olivierverdier/zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt),
install [olivierverdier/zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt),
and Edit `lib/z-z-prompt.sh`

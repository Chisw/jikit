# jikit


## Basic setting

```
open ~/.bash_profile
export PATH=/Users/Chisw/WSJ/jikit:$PATH
source ~/.bash_profile
```

or `zsh`

```
open ~/.zsh
export PATH=/Users/Chisw/WSJ/jikit:$PATH
source ~/.zsh
```

Append to the end of `.zshrc`

```
if [ -f ~/.bash_profile ]; then
  . ~/.bash_profile
fi
```
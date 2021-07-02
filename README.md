## JIKIT

A tiny shell tool

### Installation

- Clone repository:

```sh
git clone https://github.com/Chisw/jikit.git
```


- Open or create `~/.zsh`, paste the following code and save:

```sh
export PATH=/Users/USER_NAME/PROJECTS_DIR/jikit:$PATH
```

- Source `~/.zsh` to the end of `~/.zshrc` for global use

```sh
if [ -f ~/.zsh ]; then
  . ~/.zsh
fi
```

### Commands

#### `jk cp [snippet file name]`

Copy a common code

You have to prepare the corresponding code file in advance and store it in the folder like:

```
jikit
- commands
- source
  - copy
    - demo.txt
```

```sh
jk cp demo.txt
```

The text in `demo.txt` will be copied into your clipboard.

#### `jk ls`

Generate names of all folders and files in current directory into a .txt file created on the Desktop.

#### `jk mp4`

Batch convert any format of video to mp4 with `ffmpeg`, install it before use:

```sh
brew install ffmpeg
```
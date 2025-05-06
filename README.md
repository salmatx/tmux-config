# Overview

Quick fix if standard keymap of tmux is not working. There is missing vi-style navigation.

# Usage

Add file `.tmux.conf` in this repo into user's home directory.

## Alternatively

1. Clone this repo into `~/.config`

```sh
git clone https://github.com/salmatx/tmux-config.git ~/.config/tmux-config
```

2. Create symlink

```sh
ln -s ~/.config/tmux-config/.tmux.conf ~/.tmux.conf
```

If you have already opened tmux session and don't want to close it you can just reload configuration file using

```sh
tmux source-file ~/.tmux.conf
```

This step isn't needed if not tmux session is opened. Tmux automatically load config file when starting new session.

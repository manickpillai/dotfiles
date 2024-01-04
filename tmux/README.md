## Pre-requiste for installing and configuring tmux

Info on [Tmux](https://github.com/tmux/tmux/wiki)

- Brew install tmux (mac)

```Shell
brew install tmux
```

- For Ubuntu linux

```Shell
apt-get update sudo && apt-get install -y tmux
```

- Git clone the below repo

```Shell
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

- Copy the file `.tmux.conf` from this repo to the home directory `cd ~`

- Create a new session and reload tmux

```Shell
Ctrl + a r then
Shift + i
```

or inside a tmux session do

```Shell
:source-file ~/.tmux.conf
```

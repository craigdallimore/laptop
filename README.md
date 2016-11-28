Very much inspired by [oh-my-laptop](https://github.com/xiaohanyu/oh-my-laptop).

```
ansible-playbook -i localhost -K laptop.yml
```

General Prep
------------

### Set up github public key

Instructions [here](https://gist.github.com/craigdallimore/228a17b9fa73f637d673a9b93626a28a#set-up-a-public-key)

### Get dotfiles

```
cd ~
git init
git remote add origin git@github.com:craigdallimore/dotfiles.git
git pull

### Get documents


MacOS Prep
------------

## Annoyances

### Remap Capslock to ESC

System Preferences, choose Keyboard, then the Keyboard Tab (first tab), and click Modifier Keys.

### Speed up sierra animations

```
defaults write com.apple.dock expose-animation-duration -float 0.1
killall Dock
```

### Speed up keyboard

System Preferences -> Keyboard -> Keyboard Tab -> Keyboard Repeat
(Fastest)
System Preferences -> Keyboard -> Keyboard Tab -> Delay Until Repeat
(Shortest)

### Unbind ctrl-down

System Preferences -> Keyboard -> Shortcuts Tab -> Mission control -> Uncheck "Application Windows"


## Also

[ ] American keyboard
[ ] Title bar black


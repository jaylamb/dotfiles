# dotfiles
My dotfiles.

## Description
A repository of my dotfiles, and a script to install them on a new machine.

### Included files
Currently supported dotfiles:
* .config/i3/config - i3 configuration
* .bashrc - bash configuration
* .fehbg - a script that sets the wallpaper
* .gitconfig - git settings
* .vimrc - vim settings
* compton.conf - Compton compositor settings (visual effects)
* $HOME/pictures directory - a couple of wallpapers

## Installation 
To install the dotfiles:
1. Logon to a system using i3
2. From the home directory, clone [this repository](https://github.com/jaylamb/dotfiles.git)
3. To install all dotfiles, run:
```bash
./install --all
```
	* To install a subset of files, or for additional options run:
```bash
./install --help
```
4. Restart i3 

## Contributing
Before working on changes to this repository, install the git hooks:
```bash
./git/hooks/install
```

### Author
Jay Lamb

### License
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)

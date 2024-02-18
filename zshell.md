# All related to zshell
## Install zshell
`sudo dnf install zsh`

## Make zshell my default shell
- Edit /etc/passwd
- Navigate to the line containing the user name, and replace: /usr/bin/<bash> to zsh, it will look like /usr/bin/zsh

## Change to default path of the .zshrc
The default path to the .zshrc is ~/.zshrc, but I want to change it to ~/.config/zsh/, in order to do so:
- Edit the file /etc/zshenv and append:
`ZDOTDIR=~/.config/zsh`

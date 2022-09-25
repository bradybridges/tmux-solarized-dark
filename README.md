# Tmux Solarized Dark Theme

Solarized dark theme for tmux.

## Screenshot
![Screen Shot 2022-09-25 at 2 05 51 PM](https://user-images.githubusercontent.com/25031031/192163052-578249ba-eb9d-4402-bfe0-ec2ee35a367e.png)

## Setup
- Place the solarized-dark.conf file in the desired directory
- Source the theme file in tmux.conf
- Reload tmux for the changes to take affect

## Example tmux.conf
```
bind r source-file ~/.tmux.conf

source-file ~/solarized-dark.conf
```

# Tmux Config pretty basic but I like so far!

### This tmux configuration file provides a setup optimized for users familiar with Vim keybindings and offers a visually appealing experience with the Dracula theme.

## Features:

- Vim-like Navigation:
Use h, j, k, and l keys to navigate between panes like in Vim.
Resizing Panes: Easily resize panes using arrow keys with modifier (-r).
Dracula Theme: Enjoy a beautiful and customizable Dracula theme for your tmux session.
Plugin Support: The configuration includes the tmux-plugins/tpm plugin manager, allowing for easy installation and management of additional tmux plugins.
Status Bar: The status bar displays information like CPU usage, RAM usage, battery level (if applicable), and date.


## Installation:

Copy the content of this file to your ~/.tmux.conf file.s

*I  think it can live in .config/tmux/.tmux.conf as read on arch wiki but above works!!*

(I think you can use prefix [ctrl + s] + i    to install plugin )

install the tmux plugin manager
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Restart your terminal or source the configuration file: source-file ~/.tmux.conf


## Customization:

This configuration provides a basic setup. You can further customize it by referring to the official documentation of tmux and the dracula/tmux plugin.
You can adjust the resizing amount in the resize-pane commands.

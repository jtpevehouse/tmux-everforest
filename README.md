# Everforest color theme configuration for Tmux

Theme with 'retro groove' flavor for [Tmux][github-tmux], based on Pavel Pertsev's [everforest colorscheme][github-everforest]

> Screenshots made from macOS builtin terminal with xterm-256color and [Hack font][github-hack].

| Dark theme                                                                                                                                        | Light theme                                                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://i.imgur.com/STohAcp.png" title="Tmux everforest dark colorscheme" style="width: 100%; max-width: 600px; text-align: center;" /> | <img src="https://i.imgur.com/zQZEFtU.png" title="Tmux everforest light colorscheme" style="width: 100%; max-width: 600px; text-align: center;" /> |

## Installation

### Install manually

The simplest way is just:

> HINT: Always make a backup of your config files before any action.

```bash
cat tmux-everforest.conf >> ~/.tmux.conf
```

### Install through [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

Add plugin to the list of TPM plugins in `.tmux.conf` and select desired theme

```bash
set -g @plugin 'jtpevehouse/tmux-everforest'
```

Hit `prefix + I` to fetch the plugin and source it. Your Tmux should be updated with the theme at this point.

## License

GPLv3 - Josh Pevehouse

[github-tmux]: https://github.com/tmux/tmux
[github-everforest]: https://github.com/sainnhe/everforest
[github-hack]: https://github.com/chrissimpkins/Hack
[tmux-color-solarized]: https://github.com/seebi/tmux-colors-solarized

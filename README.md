tmux-solarized
=========

A Solarized Light Tmux Theme. Fork from mkoga/tmux-solarized, I customized it to adapte to tmux > 2.9, and add status change when tmux prefix click.

# Installing

### Manual Installation

1.  Clone the repository

    ``` sh
    $ git clone https://github.com/seven-linglx/tmux-solarized ~/.tmux/plugins/
    ```

2.  Add this line to the bottom of `.tmux.conf`

    ``` tmux
    source-file ~/.tmux/plugins/tmux-solarized/solarized-light-powerline.sh
    ```

3.  Reload the `tmux` environment

    ``` sh
    # type this inside tmux
    $ tmux kill-server
    $ tmux
    ```

The theme should now be active.

### Preview


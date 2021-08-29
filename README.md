# Configuration files repository

This repository contains my personal configuation files.
I use [yadm](https://yadm.io/) to manage my dotfiles and automatically setup my development environment the way I want it to be on any new machine.

## Configuring a new machine

1. Install `yadm` using the instructions on [this page](https://yadm.io/docs/install)
2. Clone the remote config onto the local machine

    ```bash
    yadm clone https://github.com/bilelomrani1/dotfiles.git
    ```

## Syncing changes in configuration

- Commit a changed dotfile
    
    ```bash
    yadm add <dotfile>
    yadm commit <dotfile> -m "Your commit message"
    yadm push
    ```

- Pulling remote changes

    ```bash
    yadm pull
    ```

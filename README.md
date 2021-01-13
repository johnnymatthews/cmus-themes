# CMUS themes

A (potentially comprehensive) list of themes and color schemes for CMUS, along with basic install instructions.

## Install a theme

Installing a theme is pretty simple. All you have to do is copy the theme file to your `~/.config/cmus` folder and set `:colorscheme` to the name of the theme in CMUS. You can download all the themes in this repo by using the `tar` files in the [Releases section](https://github.com/johnnymatthews/cmus-themes/releases/tag/v1.0.0): 

1. Move into your CMUS config folder:

    ```bash
    cd ~/.config/cmus
    ```

1. Download the latest `tar` using wget`:

    ```bash
    wget https://github.com/johnnymatthews/cmus-themes/releases/download/v1.0.0/cmus-themes-v1-0-0.tar.gz
    ```

1. Decompress the `tar.gz` file:

    ```bash
    tar xvzf cmus-themes-v1-0-0.tar.gz
    ```

1. Open CMUS and select a theme:

    ```bash
    cmus
    ```

1. Select a theme by pressing `esc`, typing `:colorscheme` and entering the theme name you want to use:

    ```bash
    :colorscheme dracula
    ``` 

    You can also set your color scheme by adding `colorscheme dracula` to your CMUS config file:

    ```bash
    echo "colorscheme dracula" >> ~/.config/cmus/rc
    ```

## Licence

This project is for use under the MIT License.

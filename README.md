# CMUS themes

A (potentially comprehensive) list of themes and color schemes for CMUS, along with basic install instructions.

## Install a theme

Installing a theme is pretty simple. All you have to do is copy this repo, move the contents of the `themes` directory into to your `~/.config/cmus` folder and set `:colorscheme` to the name of the theme in CMUS. 

1. Clone this repo:

    ```shell
    git clone https://github.com/johnnymatthews/cmus-themes
    ```

1. Copy the contents of the `themes` directory into your `~/.config/cmus` directory:

    ```shell
    cp ./cmus-themes/themes/* ~/.config/cmus/
    ```

1. Open CMUS and select a theme:

    ```shell
    cmus
    ```

1. Select a theme by pressing `esc`, typing `:colorscheme` and entering the theme name you want to use:

    ```shell
    :colorscheme dracula
    ``` 

    You can also set your color scheme by adding `colorscheme dracula` to your CMUS config file:

    ```bash
    echo "colorscheme dracula" >> ~/.config/cmus/rc
    ```

## Screenshots

Here are all the themes in a nice, easy to view, table:

| Theme name | Screenshot |
| --- | --- |
| Cyan | ![](./screenshots/cyan.png) |
| Default | ![](./screenshots/default.png) |
| Dracula | ![](./screenshots/dracula.png) |
| Gray 88 | ![](./screenshots/gray-88.png) |
| Green Mono 88 | ![](./screenshots/green-mono-88.png) |
| Green | ![](./screenshots/green.png) |
| Groove Grove | ![](./screenshots/groove_grove.png) |
| Gruvbox Night | ![](./screenshots/gruvbox-night.png) |
| Gruvbox Refux | ![](./screenshots/gruvbox-redux.png) |
| Gruvbox | ![](./screenshots/gruvbox.png) |
| Gruvbox Alt | ![](./screenshots/gruvbox-alt.png) |
| Illyria Dark | ![](./screenshots/illyria-dark.png) |
| Illyria Light | ![](./screenshots/illyria-light.png) |
| Jellybeans | ![](./screenshots/jellybeans.png) |
| Night | ![](./screenshots/night.png) |
| Solarized Dark | ![](./screenshots/solarized-dark.png) |
| Solarized Light | ![](./screenshots/solarized-light.png) |
| Srcery | ![](./screenshots/srcery.png) |
| Tokyo Night | ![](./screenshots/tokyo-night.png) |
| Xterm White | ![](./screenshots/xterm-white.png) |
| Zenburn | ![](./screenshots/zenburn.png) |

## Licence

This project is for use under the MIT License.

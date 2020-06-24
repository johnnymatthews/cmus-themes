# cmus-themes
A list of themes and color schemes for CMUS.

## Install a theme

Installing a theme is pretty simple. All you have to do is copy the theme file to your `~/.config/cmus` folder and set `:colorscheme` to the name of the theme in CMUS. As an example, here's how to set CMUS to the _Dracula_ theme:

1. Click `dracula.theme` and select *Raw*.
1. Copy the URL of that file.
1. In a terminal, run `wget <THEME URL>`:

  ```bash
  wget https://raw.githubusercontent.com/johnnymatthews/cmus-themes/master/data/dracula.theme
  ```
  
1. Open CMUS and run `:colorscheme <THEME NAME>`:

  ```bash
  :colorscheme dracula
  ```
  
1. You're theme should now have changed!

# Contributing a theme

Cheers for wanting to add a theme to this repo. Here's what you need to do to get it merged in.

## Before you start

Have a look through the `themes` folder first. If your favourite scheme is already in there under a different name, there's no point in a duplicate. If it's genuinely missing, carry on.

## Creating your theme file

Cmus themes just are plain text files full of `set` commands, one theme per file, saved with a `.theme` extension.

1. Copy an existing file from `themes/` as your starting point rather than building one from scratch.
1. Rename it to match your theme, all lowercase, dashes instead of spaces, for example `gruvbox-dark.theme`.
1. Set the colours using cmus's own colour options, `set color_win_fg`, `set color_win_bg`, and so on.
1. Add a comment at the top of the file with the theme's name, and a link to where it came from if you're porting it over from another app or terminal.

## Testing it locally

Don't submit a theme you haven't actually run.

1. Copy your new file into `~/.config/cmus`.
1. Open cmus and run the following in command mode, swapping in your theme's name.

    ```shell
    :colorscheme your-theme-name
    ```

1. Sit with it for a bit. Load your library, check the playlist view, the search box, and anything with a highlight or selected state. Themes that look fine on one screen sometimes fall apart on another.

## Submitting a pull request

1. Fork the repo.
1. Create a branch, something like `add-gruvbox-dark`.
1. Add your `.theme` file to the `themes` folder.
1. Open a pull request with a short description of the theme, and a note on where it came from if it's an adaptation.
1. Drop a screenshot in the PR if you can. It saves a lot of back and forth.

That's it. If you get stuck anywhere along the way, open an issue and I'll sort it out.

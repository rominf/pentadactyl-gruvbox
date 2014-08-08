# Pentadactyl Gruvbox Theme

This is a color scheme for the [Pentadactyl](http://5digits.org/pentadactyl/) add-on
for [Firefox](https://www.mozilla.org/en-US/firefox/fx/). It uses the color palette [Gruvbox](https://github.com/morhetz/gruvbox),
designed by Pavel Pertsev and based on the color palette for Pentadactyl [Solarized](https://github.com/claytron/pentadactyl-solarized).

This theme clears out all highlighting settings before applying its own
in order to avoid bleed over from other themes.

If you have a suggestion or find any bugs with the current
implementation, please enter an issue in the tracker:

https://github.com/rominf/pentadactyl-gruvbox/issues

## Install

To install this color scheme, copy it into your `~/.pentadactyl/colors`
folder, creating it if it doesn't exist:

    $ mkdir -p ~/.pentadactyl/colors
    $ cp gruvbox-*.penta ~/.pentadactyl/colors/.

Then change your default theme by adding the following to your
`~/.pentadactylrc`

    colorscheme gruvbox-dark

Then re-source your `.pentadactylrc`, or restart your browser to see the
changes go into effect.

    :source ~/.pentadactylrc

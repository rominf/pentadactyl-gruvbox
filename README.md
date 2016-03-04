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
	" Light variant
    "colorscheme gruvbox-light

Then re-source your `.pentadactylrc`, or restart your browser to see the
changes go into effect.

    :source ~/.pentadactylrc

# Screenshoots

See color palette for Pentadactyl [Solarized](https://github.com/claytron/pentadactyl-solarized). Here I list only differences.

## Hints
![hits-dark](https://cloud.githubusercontent.com/assets/3449635/3859443/a8b753f2-1f18-11e4-807b-31ae2b6daa4a.png)

## Completions
![completions-dark](https://cloud.githubusercontent.com/assets/3449635/3859271/9992ab1c-1f16-11e4-82d1-8e9264264ea0.png)

## Buffers
![buffers-dark](https://cloud.githubusercontent.com/assets/3449635/3859441/a8b16e6a-1f18-11e4-86eb-050a9c77da62.png)

## Help
![help-dark](https://cloud.githubusercontent.com/assets/3449635/3859442/a8b1b29e-1f18-11e4-84a1-646efb536676.png)

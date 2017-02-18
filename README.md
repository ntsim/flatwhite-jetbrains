# Flatwhite Theme Jetbrains

This is a port of the lovely [Flatwhite](https://github.com/biletskyy/flatwhite-syntax) syntax theme
for Jetbrains products e.g. IntelliJ, PhpStorm, etc. Big thanks to [Dmitry Biletskyy](https://github.com/biletskyy)
for his efforts in coming up with this clean colour palette!

## Installation

Copy `Flatwhite.icls` into your Jetbrains product's `config/colours` directory. Usually this is in
your home directory.

## Notes

I have tried to stay as true to the original as possible, however, not everything translates across, and it is
not always clear what colours should be used in every context. I have tried my best...

The following languages appear to look fine:

- PHP
- Javascript
- Java
- Markdown
- CSS
- Sass/SCSS
- Less

Your mileage may vary for languages outside of this set. I believe most of the base colours are present.
Implicitly, any other languages should look pretty okay if it inherits the base colours correctly.

Thankfully, it's generally not too difficult to remedy these issues by playing around with the colour settings
in your Jetbrains product. Hopefully, this gets you at least 50% of the way!

Not everything will be perfect, if there are any tweaks you want to make, feel free to submit a
pull request or file an issue. Getting more concrete coverage across other langugages is welcome.

# U.S. Custom Keyboard Layout

This is a homebrew tap containing a cask for the [U.S. custom keyboard layout](http://uscustom.sourceforge.net), which maps the `§` symbol to the [compose key](https://en.wikipedia.org/wiki/Compose_key).    
The compose key is very useful to _compose_ e.g. accented letters without having a dedicated key for each of them. 

**Here's some examples**:    
 * `<compose_key> + ' + e` maps to `é`
 * ``<compose_key> + ` + e`` maps to `è`
 * `<compose_key> + a + e` maps to `æ`
 
This custom layout is very useful in combination with [Karabiner Elements](https://github.com/pqrs-org/Karabiner-Elements), which allows to remap any key to the `§` symbol (named `non_us_backslash` inside Karabiner Elements).

## How do I install these formulae?

`brew install dvdblg/us-custom-keyboard-layout/<formula>`

Or `brew tap dvdblg/us-custom-keyboard-layout` and then `brew install <formula>`.

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).


## Credits
All credit goes to J. ‘Mach’ Wust, who created this very useful macOS keyboard layout. I just packaged it in the form of a Homebrew Cask.

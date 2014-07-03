Homebrew Formula Syntax
=======================

TextMate Syntax for Homebrew formulae (supporting the embedded diff)

Homebrew (http://brew.sh) formulae support inlined diffs after an
`__END__` keyword. Now, this Syntax desccription you see here, named
"Homebrew Formula.tmLanguage", merges `source.ruby` with `source.diff` and
if you have a [decent color theme](https://github.com/samueljohn/decent) that knows how to highlight diffs, it will make Homebrew formulae more beautiful.

Ruby (.rb) files beginning with `require 'formula'` are automatically
detected.

This tmLanguange here is simple enough - I wrote it directly in xml.

### Installation
-   Clone this repo directly in TextMate 2's Bundles directory like this:
```
cd ~/Library/Application\ Support/Avian/Pristine Copy/Bundles
git clone git@github.com:mcdado/Homebrew-Formula-Syntax.tmbundle.git "Homebrew Formula Syntax.tmbundle"
```

### Note
-   Updates to either source.ruby or source.diff are automatically
    used by this Syntax, too, because they are just included.
-   I copy/pasted (start|stop)foldingStopMarker from
    Ruby.tmLanguage.

### Author
-   Original for SublimeText: Samuel John (www.SamuelJohn.de)
    https://github.com/samueljohn/Homebrew-formula-syntax
-   TextMate 2 fork: David Gasperoni (http://david.gasperoni.org)
	https://github.com/mcdado/Homebrew-Formula-Syntax.tmbundle

### License:
Public Domain. I don't care. Have fun.

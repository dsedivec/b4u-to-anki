This program converts [Before You Know It](http://www.byki.com/) .b4u
files to tab-delimited files suitable for importing into Anki.

This program is based on
[grantcox/b4u_reader](https://github.com/grantcox/b4u_reader).
grantcox did the heavy lifting of actually interpreting the b4u file
format.  Thanks!

This requires Python 2.7.  Try `python read.py --help` for hints on
how to use it, or try running `python read.py your_deck.b4u`.
**BEWARE** that command will create an `output` directory under your
current directory, or if that directory already exists then this
program will happily overwrite any files in it!

This is a very quick hack for a friend, but if you find bugs or would
like other features, feel free to get in touch or open an issue and I
may oblige.

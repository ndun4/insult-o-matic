# insult-o-matic
A random insult generator for the modern masochist.

## Version: 0.1

##Features

*Pulls insulting words from associated text files
*Randomly generates a (pretty lame) insult

##Configuration

### Interpreter Path

Make sure the shebang at the top of the file is the *actual* path to your interpreter.
I began this little script to test/debug a module in a venv for a bottle app, so that's
why my shebang has a non-standard path. I will probably fix that later.

### Insult Source Files

Select your adjective and noun source files by replacing `source.txt` with whatever your source is.

	ADJ_SOURCE = 'source.txt'
	NOUN_SOURCE = 'source.txt'

The defaults are `insults-adj.txt` and `insults-nouns.txt`, respectively.

## Goals for Version 0.2

*Add insults to the insult source pages with command line arguments
*More configuration options
*A little bit of clean up

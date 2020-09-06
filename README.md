# LC-900/LC-2200 Sublime Text Syntax Highlighting

This repo contains a file named `lc2200.sublime-syntax`, which is a YAML-based Sublime Text Syntax file defining Syntax highlighting for the ISA specified by the LC-900.

Although the LC-2200 and LC-900 are very similar, *technically* this repository is based on the LC-900 ISA, and specifically the one used during the Fall 2020 semester in the Georgia Tech CS 2200 course.  This is significant because the LC-2200 does not have any skip instructions, whereas the LC-900 does not have a `beq` instruction.

To use the syntax highlighting on a Windows Machine with Sublime Text 3 installed, create any folder you'd like in `"%appdata%\Sublime Text 3\Packages\User`.  Then, add `lc2200.sublime-syntax` to this folder and you are done!

On an OS X machine, I believe the directory is `"$HOME/Library/Application Support/Sublime Text 3/Packages/User"` but as I do not own a Mac I cannot verify this.

I heavily referenced [this link](https://www.sublimetext.com/docs/3/syntax.html) and [this link](https://www.sublimetext.com/docs/3/scope_naming.html) when creating this Syntax highlighting file.  If you have any suggested improvements, please feel free to fork this repo and make a pull request.

Additionally, Sublime Syntax files are based on a Regex Engine called the Oniguruma Regex Engine, and there is some documentation available on that engine [here](https://github.com/kkos/oniguruma/blob/master/doc/SYNTAX.md).

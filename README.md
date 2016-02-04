# FreeSpace 2 support in TextMate (and Sublime Text)

Syntax highlighting for FreeSpace 2 mission and table files.

Supported file types:
- .fs2
- .fc2
- .tbl
- .tbm

##Installation

###TextMate

1. Download the zip file of the source code.
2. Unzip it.
3. Rename the resulting folder to `freespace2.tmbundle`.
4. Double-click `freespace2.tmbundle` to have TextMate install it.

###SublimeText

1. Complete steps 1 through 3 in the TextMate installation instructions.
2. Use Sublime Text's "Browse Packages..." menu option to open its packages folder. 
3. Drag freespace2.tmbundle into that folder
4. Restart Sublime Text.

## Changelog

### 0.3.0
* Redefines some language elements (again) for better cross-compatibility with Atom's default themes
* Fine tunes a couple of the regular expressions

### 0.2.1
* Adjusts SEXP detection to work around a bug in Sublime Text

### 0.2.0
* Restructures SEXP handling to be much more robust
* Better differentiates some language elements

### 0.1.0
* Initial release
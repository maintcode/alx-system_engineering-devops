# System engineering & DevOps - Bash

* What is the shell
* What is the difference between a terminal and a shell
* What is the shell prompt
* How to use the history (the basics)

## EMACS

* Ctrl and Meta Keys
* Emacs uses special key sequences for recognizing command or action statements
* Entering text, including code, is verbatim, until a command statement is encountered
* Command statements begin with either one of the two action keys: the Ctrl or Meta keys
* Ctrl (abbreviated as 'C' in some emacs documentation) is the 'Ctrl' (short for "Control") key on your keyboard
* Meta (abbreviated as 'M' in some emacs documentation) is either the 'Esc' ("Escape") or 'Alt' ("Alternate") key on your keyboard, depending on how you set up your local emacs configuration
* Some people recommend using Alt as your meta key. Some like Esc.
* To issue a command or action sequence hold down the action key (if Ctrl or Alt) and press the other key, or if you are using Esc for M, hit the Esc key, release it, and then hit the other key.
### Examples:
* C-x :  Means hold down 'Ctrl' and press 'x' then release both
* C-X : Means hold down 'Ctrl' and press 'X' ('Shift' + 'x') then release both
*  M-l  : may means hold down 'Alt' and press 'l' then release both, or if you are using 'Esc', press 'Esc', release it, and then press 'l'.
*  C-x C-s : Means hold down 'Ctrl' and press 'x' then release both, then hold down 'Ctrl' and press 's' and release both.
* M-x t : Means do the right thing for M-x, as described above, and then press and release 't'


### Builtin Emacs Help
* tutorial: "C-h t"
* or "M-x help-with-tutorial"
* searching for info about commands: "M-x apropos"
* (prompts for string to search for commands)
* full on-line documentation: "M-x info"
* (then scan down the page to find the sections on emacs)
to get out of emacs: "C-x C-c"
## A Few Frequently Used Emacs Commands
### Basic Commands
* C-x C-s	Save file to disk
* C-x C-c	Exit emacs
* C-e	Move to the end of the line
* C-a	Move to the beginning of the line
* C-x C-f	Load a file from disk into emacs
* C-i	Insert file at cursor
* C-x k	Kill/delete buffer (Current is default)
* C-v	Page Down
* M-v	Page Up
* C-k	Cut from cursor to end of line
* C-y	Paste at cursor
* C-_	Undo
### Advanced Commands
* C-SPACE	Set mark
* C-w	Cut from mark to cursor
* C-2	Splits screen into two sub screens horizontally
* C-1	Reduces sub screens to only 1 
* C-o	Switch between sub screens
* C-s	Search for word (forward)
* C-r	Search for word (backward)
* M-%	Query Replace
* C-c C-g	Goto Line
* C-c i	Ispell (spell check) word
* C-c C-i	Ispell (spell check) buffer

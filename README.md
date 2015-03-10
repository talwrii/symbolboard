# Motivation

The normal keyboard layout is good for typing text, this is what is designed for.
Symbol characters and operation keys (like HOME, END etc) were an afterthought
(they weren't used very much of typewriters!) so have been distributed around
the easy to press keys in a random fashion.

Certain activities (like computer programming) make heavy use of symbols, and
the mechanical difficult in pressing some symbol keys can be a problem.
This can:

1. Cause typos (which take time to be found and debugged)
1. Bore and frustrate
1. Require hand contortions
1. Generally slow text entry

It would, therefore, seem to make sense to make symbol characters easier to 
press, but how to do this, there are only so any keys that can be close
to one's fingers. One way to do this, is to add another modifier key
 (like shift) and use this for symbol characters.

# Quickstart

1. Prepare a command to reset your keyboard (setxkbmap us) :)
1. xmodmap symbols.xmodmap
1. Add this to your xprofile file or similar

# Features (Caveats avoided)

Motions and other keys (home, end, baskspace, enter) are similar to bash / emacs

The modifiers are mirrored.

The layout should work for both ansi and ISO keyboards

# Caveats

* Ghosting can be problematic (and may vary from keyboard to keyboard). Gaming keyboard exist that guarantee things like being able to press any three keys simultaneously. However this can be problematic with laptops (where one specifically wants to avoid carrying a keyboard around)
  
* This mapping is somewhat arbitrary, chosen kind of at random to avoid 
   ghosting on my laptop keyboard, and be consistent to bash (emacs) motions.

* The use of the apostrophe key as a modifier is rather unfortunate since
I would class an apostrophe as nearly as important as a letter. However
we need to put a mirror 

* Using space for the apostrophe symbol may be a mistake (I seem to press it occasionally when typing in all caps)

# Justifications

### Hard to use:

I have found anecdotally learned that quite complicated 
key combinations can be learned for use with editors and command line 
interfaces, and can be internalised. I don't why this laybout
would be more difficult 

### A person can only know one keyboard: 

I have been able to use multiple
keyboards on different machines at the same time without too many
problems. This might be an issue if this is the *only* keyboard
map you are using.

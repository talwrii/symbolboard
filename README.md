# Warnings

1. This only works with linux and X windows
1. This keyboard layout is not fixed and subject to change, though hopefully not radical change
1. I've had linux machines occasionally forget my keybindings.
1. This might package might force you to restart X
1. You should be prepared to do a little tinkering if you use this.
1. See caveats

# Motivation

The normal keyboard layout is good for typing text: this is what is designed for.
Symbol characters and operation keys (like HOME, END etc) were an afterthought
(since they weren't used very much on typewriters! ) and so have been distributed
around they keyboard at random at places that aren't very easy to press.

Certain activities (like computer programming) make heavy use of symbols, and
the mechanical difficultly in pressing some symbol keys can be a problem.

This can:

1. Cause typos (which take time to be found and debugged)
1. Bore and frustrate
1. Require hand contortions
1. Generally slow down text entry

It would, therefore, seem to make sense to make symbol characters easier to
press. But how can we make these easier to press: there are only so many keys
that can be close to one's ten fingers.

One way is to add additional modifier keys (analogous to shift) and use
these to create modify the easy to press letters - turning them
into symbol keys.

# Quickstart

1. Prepare a command to reset your keyboard like `setxkbmap gb` :)
1. `xmodmap symbols.xmodmap; xmodmap number-mods.xmodmap`
1. Add this to your xprofile file or similar

# Features

* Two modifiers are added: a symbol modifier (on `CAPSLOCK` and `QUOTE`), and a number / diacritic / language modifier on (`TAB` and `[`)
* Motions and other keys (HOME, END, BASKSPACE, ENTER) are similar to bash and emacs bindings (e.g `CAPSLOCK+J` is return, `CAPSLOCK+H` is backspace)
* All modifiers are mirrors.
* This layout works for both ISO and ANSI keyboard. Keys are not used if they different between the two keyboard.

# Caveats

* Ghosting can be problematic (and may vary from keyboard to keyboard). Gaming keyboard exist that guarantee things like being able to press any three keys simultaneously. However this is not a good solution for laptops.

* These mapping are arbitrary and socially driven.

* The use of the apostrophe key as a modifier is rather unfortunate: I would class an apostrophe as nearly as important as a letter. However
it important to have mirrors modifiers.

* Using space for the apostrophe symbol may be a mistake (I seem to press it occasionally when typing in all caps)

# Justifications

### But this is impossible to learn

People learn and internalize very complicated sets of keybindings when using IDEs, this is not particularly different.

### A person can only know one keyboard:

I have been able to use multiple keyboards on different machines at the same time without too many problems. Though this might be an issue if this is the *only* keyboard map you are using.


# Alternatives

* Buy a snazzy keyboard with mirrors modifiers and weird key positions. Whether this is a good idea depends on time, money, and your use of laptops.

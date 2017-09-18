# Wide Colemak

An xkb language file for gb, with the addition of a widecolemak
layout, the same as colemak with right hand keys shifted one space to
the right. 

This is *not* a simple widecolemak with every row shifted equally; the
number row is not shifted, except that square and curly brackets are
shifted to some number keys and the dollar/pound signs moved to the
middle of the keyboard. 

To change the layout, use something like:

    setxkbmap -model pc104 -layout widecolemak -variant widecolemak -option ctrl:nocaps

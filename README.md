# Star-Wars-Imperial-March-Arduino-Due

Hello! If you're here you likely had trouble finding the 
Star Wars Imperial March theme source code or "sketch" 
that you could just copy straight onto your Arduino Due.
At least, that's what I spent the better part of a week doing.
The tone() function isn't supported on the Due, so to copypasta
music source code for the musicaly inept (me), it doesnt work
because they're all for the other boards utilizing tone(). I 
took the source code from the most popular one you can find on google,
it had the notes and some custom called beep() that then called tone()
so I wrote down all the frequency and duration settings and then 
got the "NewToneLib.h" and from https://github.com/YordanYordanovGIT/NewToneLib 
and used the example tone to recreate the Imperial March theme.

TLDR; I modified some other people's work and now you can copy and paste Star Wars Imperial March for Arduino Due.

I hope this helps someone!

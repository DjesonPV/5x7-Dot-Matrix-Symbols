# Five-by-Seven DOT Matrix's unicode symbols

This project originated from a simple idea for a sports event display.
The goal was to replicate the **French L11 font** use on highways' information displays.

But then I asked myself : do other countries have similar displays?

As for all good thing to become a great thing it needs to be universal ; I'm trying to write most of the unicode for 5x7 dot matrix displays.

To represent the sport competitor nationalites, I also did special 10x7 RGB dot matrix for flags !

## What's relevant
The usefull information is in the two .json files.
* the unicode symbol are registered by hex string,
* the flags use ISO 3166 as a base; French and Netherlands which have there own code have their own flags (there is no need to have duplicates),
* The flags are coded using only 10 colors:
    * -1 : ▢ no color,
    * 0 : <span style="color:#333">■</span> black,
    * 1 : <span style="color:#812">■</span> brown,
    * 2 : <span style="color:#f03">■</span> red,
    * 3 : <span style="color:#f60">■</span> orange,
    * 4 : <span style="color:#fb0">■</span> yellow,
    * 5 : <span style="color:#190">■</span> green,
    * 6 : <span style="color:#0af">■</span> light blue,
    * 7 : <span style="color:#02d">■</span> dark blue,
    * 8 : <span style="color:#888">■</span> gray,
    * 9 : <span style="color:#fff">■</span> white.

## Disclaimers
* I only know how to read English, French, Spanish, and some latin-based writings.
* I gave my best try for Greek and Cyrillic; trying to preserve their identity.
* For Arabic, I currently only did the base encoding symbols (it needs string interpretation and Presentation Forms) ; I tried to make verstile symbols useable for now.

* For Japanese I have stumble across a scientifc paper for Hiragana, but I found that proposed symbols are unreadble in my opinion (so that's a work in progress)
> W. L. Goh and K. T. Lau, "A microprocessor-based dot matrix display system for Japanese Hiragana syllables," in *IEEE Transactions on Consumer Electronics*, vol. 35, no. 1, pp. 32-36, Feb. 1989, doi: 10.1109/30.24651.

* Obviously Braille isn't for vision-based displays but as it is trivial to implement; it simply *is*.

* I tend to not encode religion-based symbols.

* In the familly ranges, I currently put aside CJK tables and Korean Hangul; as this too much work and may not be possible in 5x7, I might try as 10x7; but not before other alphabets.

* I put many flags of the world; kindly be human.

## Currently supported alphabets
- Latin and latin-based
- Greek
- Cyrillic
- Armenian
- Arabic (partially)
- Hebrew (modern only, without vowel diacritics)
- IPA Extensions

## Can I use your work?
Yes, simply cite me when possible.

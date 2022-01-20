# Why Vim is my best editor.

Vim is such a real pleasure to use, all those things you can do to help editing, and just by remembering a few
keystrokes. There's an `APL` feeling to it, maybe even `J`, but the difference is that those keystrokes are not meant to
be read by someone else, because otherwise they would rapidly look like noise.

Vim marries well with Cone, because contrary to widespread misconception, complexity can be elegant and accrue
performance and expressiveness, but that understanding requires perseverance and focused abstract thinking which few
people are ready to accept.

Of material importance, Vim's memory footprint is astonishingly tiny compared to those other shiny editors : I used
`Clion` a bit and it rapidly goes to GB of memory, with a single file opened, and just updating it took like 15GB of
temporary storage, which consequently failed on my old stuffed to the brim mac.

In comparison, Vim takes like a few tens of MB, depending on the number of files opened. So it fits well on old laptops.

Last but not least, CO2-wise, Vim is a clear winner among general purpose editors. Vim is clearly a better fit for the
minimalistic requirements of the coming future. A somewhat more extreme position is that of Arthur Whitney who only uses
`notepad` for his `k` and `q` programming on windows, like just a step above using pen and paper :wink:

Sigh... I don't know if people using other editors than Vim really know what they miss :

<https://freshman.tech/from-vscode-to-vim/>

Look at J. Blow writing in his editor, in his Jai videos, he spends so much time just pounding on his keyboard for
nothing, it's embarrassing, that's because he doesn't have normal mode and probably doesn't care but that's because he
doesn't know, has never seen the difference. If he just did a cost/benefit analysis with regards to time spent doing
nothing on his keyboard, and time necessary to learn Vim, he would necessarily switch.

When time is of the essence, Vim is necessary.

And Vim makes the act of editing feel like programming ! You don't feel good after pressing backspace 10 times, but you
do after pressing `10X` or `diw`

A very important parameter is the fact that every question you have about doing something in Vim is just right there
once you google it, just everything. So you learn very fast. Vim users are proud of their tool, and like sharing their
knowledge. Real craftsmanship.

Ok, so here's a little example : I have this type in Cone which for some buggy reason I need to delete. So the type is
`[3,3;f32]` : people who use an editor like they would a door handle, i.e. not care, would just click at the right of
the last square bracket and press backspace 8 times. In vim, you go anywhere in that square bracket -- there's easy ways
but that's not the point here -- and press

`da]`

which means "delete `d` what's inside that delimiter `]` and the delimiters too `a`".

Isn't that beautiful ? Like a keystroke haiku. That's why using Vim puts a smile on your face.

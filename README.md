This gives you vim-like cursor controls on a Mac:

- Caps Lock is mapped to Esc when tapped alone.
    - This is especially great if you have a Touch Bar.
- Caps Lock is a modifier for cursor controls:
    - H/J/K/L: left/down/up/right
    - D/U: page down/up
    - 0/4: home/end (the 4 is a bit like $ but without shift)
    - F/G: command-home/end (in some apps this goes to top and bottom of document)

I call the new Caps "Hyper", but that's not quite right. Hyper is technically
all four modifiers (shift, alt, ctrl, and command), but if I do that then it's
easy to trigger sysdiagnose (which is all four plus period). And it's hard
to disable that with Karabiner because you can press the period key first, which
happens often at the end of a sentence line in vi.

So I instead map to some other unlikely combination of four control keys. If this
clashes with some program, we'll have to try another combo.

To install:

- Install [Karabiner](https://karabiner-elements.pqrs.org/).
- Copy `vim-everywhere.json` to `$HOME/.config/karabiner/assets/complex_modifications`
- In the Karabiner UI, go to Complex modifications tab, click Add rule, and enable both rules.

I also mapped Caps Lock to "No Action" in the System Preferences, but I'm not
sure if that's necessary.


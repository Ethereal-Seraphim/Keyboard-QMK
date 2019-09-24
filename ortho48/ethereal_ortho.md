~/Downloads/ortho48/ethereal_ortho*.json

For the ortho keyboard I have a few ideas in mind, and I want to try and docmuent them all here so I know what I was thinking later.
https://www.smittey.co.uk/the-planck-key-theory/ "This guy had ideas similar to me, I'm copying him extensively
http://thedarnedestthing.com/planck%20constant "Sdothum has some whacko ideas and drastic changes
http://www.keyboard-layout-editor.com/#/gists/c6c0ac051b2b118a34ef84ebadab54c7 "Reddit user trying to maintain 'normality' in 40%

First layer (layer 0) has a few interesing features.
Capslock key is rebound to a dual ctrl-esc key for vimcraft.
I'm still pretty torn on whether or not my MO layer swaps should be on the outermost edge.
The arrow keys on the layer are suspect, as I'd rather just use the gui/nav layer.
Tried adding Ins and Del on this layer, as I believe them to be used sometimes. The arrow keys just weren't going to be used.
I've been kicking around tap dance home row modifiers, but I realized I hold the vim nav keys a lot.

Layer 1 is my symbol layer.
The idea is entirley taken from:
https://configure.ergodox-ez.com/ergodox-ez/layouts/ZqR6/latest/1
https://www.smittey.co.uk/the-planck-key-theory/
The first option seems like it has every symbol needed on the board, and familiarity/comfort with the layer could prove incredibly useful.
There's a blank spot in the middle of the board over the left paren, that will be Ae when I figure out how to make it so.
The second option is much cleaner, and based on the colemak mentality of home row advantage.
However, he seems to be missing a few symbols, and quite frankly, I'm not sure putting numrow symbols where they usually go is a good idea.
Symbol row will continue to be workshopped.

Layer 2 is my hexadecimal numpad layer.
A good chunk of the layout is based off of this:
https://i.imgur.com/dREx6cK.png
The design is largely inspired by the ipv6 buddy. I tried to implement everything you'd need for working heavily with numbers.
Primarily it looks like a number pad on the right side, with a bunch of symbols jammed where they fit logically.
Then there's the symbols jammed there that make 0 sense, but you have to work with the confines of the board.
The letters let you input hexcodes if that's something you want to do. I also added a colon for ip/mac addresses and stuff like that.
I'm actually pretty happy with how this one turned out, there's only one key left to map.
There's a chance that there may be a conflict because 0 on the numpad is located where the symbol layer is normally. If this continues to be a conflict. I'll move the 0 one key to the right, and relocate the comma to the blank space.

Nav Layer
Incorporated vim style hjkl keybinds
home, page up, page down, and end placed below their "counterparts" on the vim row
Still unsure if I want to add gui/mouse controls here
Macros that work i3wm are also a total possibility here
Media controls go right above the vim layer with up/down/seek/play/pause

Function Layer
Decided to jam all my F keys onto this layer
It'll also pull double duty as the "firmware layer"
Things like LED controls, and Layout swaps will be hosted here

Alternate Layouts
I decided to make an exact copy of my base row (Layer 0) but with qwerty and dvorak.
This is probably a terrible idea since I suspect literally no one will ever want to use my board, but it doesn't hurt to be thorough.
Also, I have yet to meet a single person that uses dvorak in the wild.
These layer swaps will be hosted on Layer 4 "function layer"

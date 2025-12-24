by Blake!

In this demo I'll be designing and fabricating my first microfluidic chip. 

Here is an awesome resource to use btw!
https://www.youtube.com/@dk-hu3er/videos

Things to do:
- Make the mask
- fabricate the channels on the slide
- punch input and output ports

## Design

The design of my chip is very simple. I wanted to do a quick y-channel mix with followed by a serpentine channel and then the outake. The y-junction combines the two liquids and the serpentine track aids in mixing. This should hopefully be a simple first build.

## Process for Creating the Chip

1) Make the mask
2) ...


### 1) Make the mask

For making the mask, I used onshape to develop the channel 

![[Screenshot 2025-12-24 at 12.21.49 PM.png]]

Then I loaded it into the klayout MEMS software to scale and export the mask file format. In klayout, it looks like this: 

![[Screenshot 2025-12-24 at 12.35.40 PM.png]]

This is a relatively simple design so I don't have to worry about a lot of typical things you need to worry about for the mask design. These issues include worrying about layers and the cell hierarchy for reusable components. 

BTW - klayout is a horribly confusing piece of software at first use. I recommend doing some reading as it took me over a day to fully know how to do some basic operations with it. Although to be fair I could be slow.

##### Ports

Ports are weird. You need them for the chip to function.
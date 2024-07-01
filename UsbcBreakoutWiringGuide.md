# Ali Express USBC combo port wiring guide

![Pictured: What a finished port should look like on it's "top" side if you follow this guide](imgs/port-wiring-guide-1.jpeg)
*Pictured: What a finished port should look like on it's "top" side if you follow this guide*

If you're wondering why anyone would use these ports, it's because they can fit in layered 3mm acrylic design snugly and are cheaply available on Ali Express world wide. Sellers change frequently, so I can't post a link to one in particular and be confident it'll still be active in the future.

When preparing your port, you will want to choose which side is going to be the pretty one and which will be the back side. On a clear build, having the top facing the button panel is absolutely preferable, but on some builds you might have art or some other design that means the viewing angle of the port is from the underside of the build.

**IMPORTANT NOTE:** DO NOT cut your wires off at the port; you will want to thread them through as per the wiring guide that follows, and then cut them to length required to your microcontroller/solder points. It's not the end of the world if you cut them off, but keeping each of the steps continuous means you only need one wire for the entire bridging and connection process.

**ALSO:** This port cannot support USBC-USBC cables; if that matters to you, you should order a port from folks in the community such as the Model U, Model UD, Model Bird, Model BirdD, HTUB, etc. These can all be found in the Crane's Lab discord via the #vendors channel.

![Pictured: Another port prepared in the same way.](imgs/port-wiring-guide-2.jpeg)
*Pictured: Another port prepared in the same way.*

Each step will be shown bottom view then top view before moving to the next step. the direction you do it in doesn't matter TOO much, there's room for flexibility especially on the bottom side for the order/arrangement. I'd recommend making sure your top side matches closely though, and don't have more than 3 wires stacked to prevent them getting too thick to fit into your 3mm acrylic layers.

Let's begin.

## Step 1

![Bottom: Ground.](imgs/port-wiring-guide-3.jpeg)
*Bottom: Ground*

Note the arrows showing the direction the wires go in/out from each pins. Route the connection between sides in such a way that it doesn't interfere with access to other pins and your room to solder.

Leave slack as you weave it through, then start from the end point and pull one or two joints tight from that spot to prepare for soldering it in. Depending on the sheathing of your wire and the quality of your solder, you might be able to simply melt the plastic away to make your joint. To avoid the risk of melting the sheathing off completely, I use a craft knife to cut notches into the sheathing at the location of the joint to make getting a connection more consistent.

**IMPORTANT NOTE:** Do all your soldering from the bottom side! It keeps the top clean.

![Top: What your runs should look like on top](imgs/port-wiring-guide-4.jpeg)
*Top: What your runs should look like on top*

## Step 2

![Bottom: USB data lines. D- or D+ first makes no difference, but do them both at this point.](imgs/port-wiring-guide-5.jpeg)
*Bottom: USB data lines. D- or D+ first makes no difference, but do them both at this point.*

![Top: Data -](imgs/port-wiring-guide-6.jpeg)
*Top: Data -*

## Step 3

![Bottom: Data +](imgs/port-wiring-guide-7.jpeg)
*Bottom: Data +*

![Top: Data +](imgs/port-wiring-guide-8.jpeg)
*Top: Data +*

## Step 4

![Bottom: VSYS / 3.3V](imgs/port-wiring-guide-9.jpeg)
*Bottom: VSYS / 3.3V*

**NOTE:** This is the wire your diode is part of. I mention this because I always forget and have to dig up the reference diagrams :P

![Top: VSYS / 3.3V](imgs/port-wiring-guide-10.jpeg)
*Top: VSYS / 3.3V*

## Step 5

![Bottom: 3VD (GCC data line)](imgs/port-wiring-guide-11.jpeg)
*Bottom: 3VD (GCC data line)*

![Top: 3V D (GCC data line)](imgs/port-wiring-guide-12.jpeg)
*Top: 3V D (GCC data line)*

**Note:** pay attention to the wire routing here specifically; the next and final step will make this make sense. If you're not sure what the relationship is here, refer back to the first two example images at the top of this post and look closely.

## Step 6

![Bottom: VCC / 5V](imgs/port-wiring-guide-13.jpeg)
*Bottom: VCC / 5V*

![Top: VCC / 5V](imgs/port-wiring-guide-14.jpeg)
*Top: VCC / 5V*

**Note:** Use your 5v wires to pin the wires from steps 4 and 5 into place. Again, if you're unsure of what this means from image alone, please refer to the example images at the top of this post.

## Questions?

If you have any Qs, ask me in Crane's Lab!

- RMZC

![P.S.: Here's the result in a build :)](imgs/port-wiring-guide-15.jpeg)
*P.S.: Here's the result in a build :)*

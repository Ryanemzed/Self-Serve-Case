# Buttons Matter
I started my journey building rectangles by trying to make a controller for my brother that didn't suck, and a big part of that was realizing that what the folks in the US were doing with keyboard switches was just not at all accessible to me in Canada before services like SendCutSend opened up affordable shipping recently.

I've spent the past two years tinkering with buttons of various types trying to figure out ways to make the most of what I had access to, and in all of my work I feel like arcade buttons still have a place in the current scene. Of course, a big factor behind that is that the OBSF-24 buttons from Sanwa remain a popular option in the FGC at large, but more specifically because they don't require the specific design consideration of having a switchplate for the keyboard switches.

Enter the files in this GitHub.

# A Flexible Set of Files
The design language is heavily lifted from the builds I do by commission, the Chocwa Bar & Chocwa Bar Mini, using curved channels to guide the wiring from the button clusters to the microcontroller and maintaining as much material infill as possible to preserve rigidity when using materials such as acrylic.

There is much work to be done in writing out explanations for how to make adjustments to what thicknesses of material to order for what buttons you're planning to use, how to do you usbc ports, potential hurdles with tolerances, recommendations for good materials to use and potential services you can use to get these files cut.

For now, know that my primary objective is to provide a platform for people to build something that is sleek while reducing the case footprint as much as possible using more widely accessible processes and materials.

# How To Use These Files
The way to make sense of this is to think of it as a top to bottom set of slices. You will always need a Button Panel that's 3mm thick, then you'll want 6mm worth of Under Panel (either one 6mm layer or two 3mm), and then your port/cable layer also 3mm. Where the most variability will come from is in the Wiring layers underneath, as that's where all of your wiring spaghetti lives. And then of course, you'll need a bottom panel.

As an example of a configration one would use, for my builds using my modded Sanwas I use a total of 5 or 7 layers depending on my materials:

1 x 3mm Button Panel
1 x 6mm Under Panel (or 2 x 3mm as needed)
1 x 3mm USBC Panel
1 x 6mm Wiring Panel (or 2 x 3mm as needed)
1 x 3mm Bottom Panel

This gets me a total case thickness of about 21mm with just enough room for my wires to and from the buttons and the microcontroller. Now, someone else using stock sanwas, or MX modded sanwas, or perhaps even a mod similar to my own Chocwa builds or using my Bao Button mods, each of them will need to potentially use a slightly different configuration.

Lastly, there are multiple remixes of each layer, which are meant to address variables such as the types of bolts & nuts or the usbc breakout board intended to be used. These will all be explained in due time, as I'll provide detailed instructions for the different arrangements you should choose depending on which of those variables are relevant to you.

So, please, accept my apologies for how slow I'll be at fleshing this out.

# The Files
For now, please find all of the files I've developed so far at my Google Drive link here: https://drive.google.com/drive/folders/1H953CQpRPNNaVaf_rjKbYQHJYwPd4CnC?usp=sharing

# Example Builds
So far, I've had two people use the files here to make their own controllers, and I'm super thankful to both of them for trusting my work to make themselves something they can use to enjoy the beautiful game of Melee.

V_Rin's build:
![20220529_171948](https://user-images.githubusercontent.com/96904158/172110219-6992ccf4-28b1-4ffd-af29-d767a16048a9.jpg)
![20220529_171959](https://user-images.githubusercontent.com/96904158/172110230-bbd521be-f9b2-44f8-be28-6f12efea2cee.jpg)
Her build used Baolians I MX modded for her, and she was able to get a case depth of 30mm

Zedy's build:
![20220520_230127](https://user-images.githubusercontent.com/96904158/172110406-d9111ce7-9ed6-4ae8-9acb-895c235af5e3.jpg)
![20220520_211841](https://user-images.githubusercontent.com/96904158/172110808-9f27545b-ee6e-4aff-8e41-41ca70cdf214.jpg)
His build reused components from his DIY build he had done using a Hammond steel case and stock sanwas, and with a little cruelty he was able to make things work. The issue here was that we needed to add one more layer of material to the wiring channels to account for tolerances in the acrylic, so he didn't have quite enough room for his button terminals and had to solder his ground loop on rather than using the existing QDC terminals. That said, he was able to accomplish a build totaling 33mm case depth, reducing the physical bulk and heft he was unhappy with coming from the Hammond case significantly.

# Questions
If you'd like to ask any questions, please feel free to @ me in Crane's discord (https://discord.gg/S3qgZWD), where I am active and spend a lot of time discussing builds and work to help others accomplish their own builds in between joking around :)

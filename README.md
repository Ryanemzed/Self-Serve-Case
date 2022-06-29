# Buttons Matter
I started my journey building rectangles by trying to make a controller for my brother that didn't suck, and a big part of that was realizing that what the folks in the US were doing with keyboard switches was just not at all accessible to me in Canada before services like SendCutSend opened up affordable shipping recently.

I've spent the past two years tinkering with buttons of various types trying to figure out ways to make the most of what I had access to, and in all of my work I feel like arcade buttons still have a place in the current scene. Of course, a big factor behind that is that the OBSF-24 buttons from Sanwa remain a popular option in the FGC at large, but more specifically because they don't require the specific design consideration of having a switchplate for the keyboard switches.

Enter the files in this GitHub.

# A Flexible Set of Files
The design language is heavily lifted from the builds I do by commission, the Chocwa Bar & Chocwa Bar Mini, using curved channels to guide the wiring from the button clusters to the microcontroller and maintaining as much material infill as possible to preserve rigidity when using materials such as acrylic.  

You're going to need to do some investigating to figure out how to make these files work for you, but you can come to Crane's discord to ask me questions about how to plan a build that will work for your needs. Things like tolerances, your comfort level with soldering, and even the materials you're hoping to use can throw some curve balls that take some work to figure out.  

For now, know that my primary objective is to provide a platform for people to build something that is sleek while reducing the case footprint as much as possible using more widely accessible processes and materials.

# How To Use These Files
The way to make sense of this is to think of it as a top to bottom set of slices. You will always need a Button Panel that's 3mm thick, then you'll want 6mm worth of Under Panel (either one 6mm layer or two 3mm), and then your port/cable layer also 3mm. Where the most variability will come from is in the Wiring layers underneath, as that's where all of your wiring spaghetti lives. And then of course, you'll need a bottom panel.

As an example, let's imagine you're building with stock Sanwas, want a USBC combo port, and are planning to use quick disconnect terminals. Let's look at the layers we'll need:

1 x 3mm Button Panel  
2 x 3mm Under Panel (or 1 x 6mm)  
1 x 3mm USBC Panel  
7 x 3mm Wiring Panel (or 3 x 6mm + 1 x 3mm)  
1 x 3mm Bottom Panel  

This provides us the amount of space we need to just fit in stock Sanwas and their connectors with a bit of elbow grease, with a total case depth top to bottom of 36mm. This leaves an internal working space with the wiring layers of 21mm, which should be plenty of room for activities with a wire range of microcontrollers and with soldering or even screw terminals.  

In general, you're going to adjust your layer selection based on the buttons you're intending to use, accounting for the types of connectors they use and how much room you need to get them connected up. Modding the buttons in different ways can allow for a lot of savings in overall depth and fewer layers required, such as in the mods I perform as seen in my other GitHub repositories.  

Lastly, there are multiple remixes of each layer, which are meant to address variables such as the types of bolts & nuts or the usbc breakout board intended to be used. To start, all of the designs presuppose you will be using sets of M6 bolts [such as these](https://www.amazon.com/uxcell-Binding-Leather-Fastener-M6x20mm/dp/B07QB68F9K/), which can be found on amazon all around the world as well as places like [AliExpress](https://www.aliexpress.com/item/1005001560902304.html) in a variety of lengths to match the final case design you settle on.

# The Files
For now, please find all of the files I've developed so far at my Google Drive link here: https://drive.google.com/drive/folders/1H953CQpRPNNaVaf_rjKbYQHJYwPd4CnC?usp=sharing

They are split into 5 panel types:

<u>Panel 1 - Button Plates</u> (3mm)  
This is the layer of acrylic your 24mm buttons will snap into. It's important that this layer is 3mm to hold the buttons properly.  

<u>Panel 2 - Underplates</u> (6mm)  
This is what goes directly underneath your button plate, helping to keep your buttons and their panel supported and making your build as sturdy as possible.  

<u>Panel 3 - USBC</u> (3mm)  
This layer is what sandwiches your USBC breakout board into place. It relies on you doing some hand wiring to use cheap and commmonly available breakout boards from [AliExpress](https://www.aliexpress.com/item/1005001300974530.html), or ordering specially designed breakouts that simplify the wiring greatly [as found in Hadoe's GitHub](https://github.com/HTangl/HTUB)  
There are versions of this layer adapted for each type of breakout board and are labelled accordingly, or you can opt to do a permanently connected cable instead.  

<u>Panel 4 - Wiring Routing</u> (???mm)  
As I said above, this layer is where it's most important for you to know what you need. Here is where you make more room for buttons and connectors that are taller, or can save on bulk if you're using something shorter like a Bao Button found in my [GitHub](https://github.com/Ryanemzed/Bao-Button-Mods) on the mod.  

<u>Panel 5 - Bottom Cover</u> (3mm)  
Thankfully, there's nothing special here to worry about: its only job is to close things up :)  


Some handy tips to keep in mind:  
- 3mm clear acrylic is always cheapest
- Ordering more than one of a layer makes the layers cheaper
- 6mm clear acrylic is a nice option to make things easier to handle while building
- MDF is a viable material option if it's cheap enough
- Some places will offer wood, which can have a nice look to it when stained  

As a tip, I like to do a clear acrylic button panel and then a cool type of material underneath like stained wood which protects it from wear and tear. Another idea is a clear acrylic top layer, and then printing out a piece of art you like to go under that panel and spare you from having to see all of your wiring spaghetti under it ;)

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

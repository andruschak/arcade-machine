# Building... and rebuilding an arcade machine

This is a chronicle of a project that took to life in 2011 and is still evolving today. I am taking the time to put this together online because of a recent tragedy - around 6 months ago the motherboard in the PC died.

Some of the original information is gone but I will endeavour to try and find as much of the original plans as I can.

Bit of disclaimer - do this at your own risk and understand the laws when utilizing emulation.

## A brief history

I love video games. That's it, there is no denying it. I am and always will be a gamer.

Like most kids in the 80's I was bit by the Atari/Nintendo bug early on. Growing up I had a multitude of game systems and spent more time than I care to admit playing them. I can remember renting a copy of Megaman, waking up at 5am to play, so I could sneak in time before my mom booted me outside.

It didn't stop at console games. It branched out to early PC (we're talking 486dx66 until today) and of course in my pre/teen years the Arcade.

Being a maker at heart it only made sense to build my own machine.

# Cabinet & electronics

## Build criteria

A few of the things I wanted in the build (in no particular order):

- [x] Full sized cabinet (modelled after street fighter/mortal kombat dimensions)
- [x] Perfect height for two 6' adults to stand without bumping into each other
- [x] Moderately priced
- [x] Powerful enough to play games like Mortal Kombat 2, Killer Instinct, etc.
- [x] Detachable control panel
- [x] Light up transparent marquee
- [x] Could hold either a CRT or LCD monitor
- [x] Front panel could be removed to allow for resizing
- [x] Fit a standard ATX midtower
- [x] Adjustable speakers mounted a head height
- [x] Genuine arcade joysticks and 8 buttons per player
- [ ] Themed decals for the sides, marquee and control panel
- [ ] External USB connections
- [ ] Coin slots
- [ ] Track/Roller ball
- [ ] Lightgun support


## The cabinet

I had the pleasure of working with an at the time co-worker on this piece (he has since retired). Together we modified some rough plans we found on the internet and went about construction. As with any first go-around there are parts we could have done better but overall the results were fantastic.

The cabinet is "bomb-proof". Overall it stands approximately 6 and a 3/4 feet tall and probably weighs over 100lbs. Plywood was used instead of MDF or press-board and the cabinet was assembled using dowel joints and wood glue. It is seperated into upper and lower sections held together with 6 long bolts making it easier to move if required.

The front panel is removable by undoing a couple screws. This was done in the off chance a larger monitor was acquired and the hole needed to be resized.

Behind the cabinet there is a detachable wooden door held on by 2 spring roller catches. Inside there is ample room for a display and pc.

There are 2 holes drilled at the top for speakers and the marquee has a removable plexiglass cover with a light behind.

The outside is finished in a textured gray and black paint. At the time I was unable to find anywhere that would do a custom decal for the sides for under $1000. An additional compromise was not using trim around the edges and instead opting to have the wood rounded.

Another recommendation I would have would be to install external usb ports (like you would see in your vehicle). This would allow for quicker connection of a keyboard/usb stick during troubleshooting or maintenance.

## Build pictures

##### The side panel, stenciled and being cut

![side panel on the table saw](https://github.com/andruschak/arcade-machine/blob/master/images/side-precut.png)

##### Cutouts of the front panel and the paper stencil of the joystick and button layout
![front panel and paper stencil](https://github.com/andruschak/arcade-machine/blob/master/images/front-panel-preassemble.png)

##### The lower part of the cabinet assembled
![lower assembly](https://github.com/andruschak/arcade-machine/blob/master/images/lower-assembly-one.png)

##### The upper part of the cabinet during final assembly
![upper assembly](https://github.com/andruschak/arcade-machine/blob/master/images/upper-assembly-one.png)

##### The upper part complete and primed
![upper assembly primed](https://github.com/andruschak/arcade-machine/blob/master/images/upper-assembly-two.png)

##### Both the upper and lower componants before assembly
![upper and lower](https://github.com/andruschak/arcade-machine/blob/master/images/upper-and-lower.png)

## Control Panel

This was probably the most challenging part of the build. In the end it works but there are a few changes I would make if I had to do it again. Here are a few comments and reflections on the build.

The control panel is removable and held on by the same spring roller catches as the back panel. This has been a bit of a life saver as I've had to get in there a few times. It would have been great to put it on hinges. The top of it is covered in plexiglass to make it easier to clean. As part of the finishing I would have liked to put a custom decal or black poster paper to cover up the joystick mounts.

You're going to need a huge amount of room to put in 2 players + trackball. This is what ultimately lead me to leave it unchecked in the requirements list.

As noted in the requirements I wanted to build a panel that would allow two 6' adults to stand side-by-side comfortably. In premise that sounds good but in order to do it we needed to slightly slant the controls for each player. It works but I found it can make certain joystick moves harder to pull off because the stick isnt exactly center. When you've got years and years of muscle memory to pull of a Ryu's hadouken its sucks being off by 10 degrees. My next build will have the joysticks straight up and down and parallel to each other.

All of the parts were ordered from [ultimarc](https://www.ultimarc.com/). The price was quite reasonable coming out at ~$200 with shipping (Nov 2011).

#### Parts list:

| Hardware                      | Price         | Count  | Total  |
| :-----------------------------|--------------:| ------:|-------:|
| I-PAC 2 Interface. USB Cable  | 43.00         | 1      | 43.00  |
| Mag-Stik Plus Red             | 33.00         | 2      | 66.00  |
| Classic Pushbuttons. Black    | 1.95          | 2      | 7.80   |
| Classic Pushbuttons. Blue     | 1.95          | 2      | 7.80   |
| Classic Pushbuttons. Green    | 1.95          | 2      | 7.80   |
| Classic Pushbuttons. Red      | 1.95          | 2      | 7.80   |
| Start Logo Pushbut. Start 1   | 2.90          | 1      | 2.90   |
| Start Logo Pushbut. Start 2   | 2.90          | 1      | 2.90   |
| Wiring Kit                    | 22.00         | 1      | 22.00  |

##### I-PAC 2:

Picking a solid usb-controller to make button mapping WAY easier. A controller specifically designed for arcade input also helps with being able to read a bunch of inputs being pressed at once. For this I went with the I-PAC 2. The modern day versions support a few additional buttons which help with alternate controls such as pause, shuffle, menu, back, etc... I would utilizing these. My I-PAC lets you access these commands via "shift" functions - that is, you hold down Player1Start and press specific buttons for specific actions.

The [I-PAC2 control sheet](https://www.ultimarc.com/ipac2.html)
 

##### Joysticks:

I wanted the absolute best option I could find here. It is important that these can take a beating. I ended up going with the Mag-stik and have been very happy with them. A cool feature is the ability to lift and twist the stick to move from 8-way to 4-way controls. This is great for old school games like PACMAN that only support 4 way controls.

##### Buttons:

As with the joysticks, I wanted the closest thing to real as possible. I am very happy with how the classic pushbuttons worked out. Unfortunately at the time there wasn't an option for LED buttons. This would be a cool feature as you can light them up ingame based on whether or not they're active!

Ensure to make space for wiring and button placement. There is a lot going on in there so leave room.

As mentioned above, there is support for a variety of other buttons. At the very minimum it is advised to have buttons for player 1 and player 2 start and coin add.

##### Wiring:

This was a lot of a fun. There were a lot of wires to be cut, stripped and crimped to put this together. Overall it works well and didnt require soldering. I used common ground for the buttons but isolated everything else. 

I have had a wire come loose on occasion. It definitely helps to have easy access to the underside of the panel.

##### Display

The display was a bit of a challenge. There are a few things to take into consideration when building an arcade machine.

Ask yourself, do you want to CRT (big but lightgun friendly and more try to original) and LED (small, light, aspect ratio, resolution)? Originally I had an old TV in mind for using with this but during testing it was obvious it wouldnt work (lines and discolouration as I tested it) so I ended up having to go with LED. Luckily I had a 19inch 4:3 LG monitor that would work. The only bummer really is its size. I would have liked to go larger but it was really challenging to find anything in a 4:3 that was larger than 19inch (some $5000 medical monitors at 24 popped up... but a little more expensive than I was willing to pay).

Since 2011 there have been a lot of advances in the emulators and how they handle wide screen monitors. If I can find the time I would like to resize the front display holder to accomodate a 22 or 24 inch wide screen. Some more of this in the What's next section at the end of this write up.

The screen orientation could depend on what types of games you enjoy playing. You could mount vertically if you're big into vertically scrolling shoot 'em ups (like the 19xx series). I havent tried this but have heard mention of it on various forums.

##### Sound

For the sound system in this build I used a pair of old Dell desktop speakers. Once disassembled they mounted nicely in the wooden frame at the top of the box. 2 small holes are cut in the cabinet below the marquee. In hindsight it would have been cool to make them slotted but it still came out ok.

Because they were desktop speakers there is a physical volume control knob and standard 3.5mm headphone jack making it easy to connect to the computer inside.

It doesnt produce a lot of bass but they work well in this application. It would be nice to get the physical volume controls easily accessible from the outside but not a hard requirement. You can utilize an input shortcut on the I-PAC2 to adjust the volume using player1start+up/down on the joystick.


## Build Pics

##### Mag-stik close up
![mag-stik](https://github.com/andruschak/arcade-machine/blob/master/images/joystick.png)

##### Panel during build
![holes cut](https://github.com/andruschak/arcade-machine/blob/master/images/control-panel-one.png)

##### Wiring the controls
![holes cut](https://github.com/andruschak/arcade-machine/blob/master/images/control-panel-wiring.png)

##### Finished panel
![finished panel](https://github.com/andruschak/arcade-machine/blob/master/images/control-panel-finished.png)

##### Finished cabinet and loading of the first game!
![assembled](https://github.com/andruschak/arcade-machine/blob/master/images/assembled-firstplay.png)


# Computer hardware 

Choice of computer hardware is absolutely critical to the success of this build. In this section I will cover the history, testing and overall choices I made when building this out. 

Emulation can be quite demanding on hardware. Many arcade platforms were built on proprietary electronics using design choices that dont always align well with modern cpu architectures. This results in a wide set of results and experiences depending on what you're trying to play. Mortal Kombat II for example utilizes a discrete graphic and sound processors which have to be properly synced and emulated on a single core of a modern cpu. This can push the limits of weak hardware. 

The emulator performance is only one aspect of the experience. You also need to make sure the system is able to handle the operating system and frontend software (depending on how sophisticated you want to go). 

## The original PC

The original PC that I used for this project was one of my previous desktop machines.

- Core2Duo @ 3.0Ghz (e8400)
- 4gb memory 
- 230gb HD 
- Nvidia 9800GT (not heavily utilized in MAME)

It proved to be more than adequate horsepower for the games I was looking to play (pre 2000).

I left it in the ATX case I had originally built it in which fits in the case but isnt the best use of space. 

For the operating system I ran Windows 7 Professional 64bit (though 32bit Home would probably work). 

## The return of PC

Since 2011 there has been a revolution in the amount of horsepower available in a small form factor. In 2012 the original Raspberry Pi was released ushering in a new era a mini computers.

At the time of this writing, the latest RPI is a model 3b+. 

The PI has some advantages over a full blown PC:
- Price
- Form factor
- Low power consumption
- Fully configured system images can be found online (be careful with these)

However, in my experience the PI isn't powerful enough to handle some of the more demanding arcade roms. I do make use of this board in another emulation project (will do a write up for later). 

As luck would have it, I was able to get my hands on an old Intel NUC which appears to be able to handle all of the games thrown at it.

- Intel NUC (NUC6CAYH)
- Dual Core Celeron @ 2.3Ghz
- 4GB Memory
- 120 Corsair RED SSD
- Built in WiFi and Bluetooth is a bonus
- Tiny footprint compared to an ATX midtower

My only gripe with the system is the CPU. I'm not typically like Celerons and it is definitley the bottleneck in this machine. It appears to run games fine but there is the odd framedrop while running Hyperspin. Nothing terrible but occasionally noticable.

Because of Hyperspin the system needs to be running Windows (in this case - Win 10 64bit). I would recommend checking out some tips and tricks for improving performance such as disabling rich themes and search indexing.


### Software



### Front end

### ROMs

## What's next?
# Building... and rebuilding an arcade machine

This is a chronicle of a project that took to life in 2011 and is still evolving today. I am taking the time to put this together online because of a recent tragedy - around 6 months ago the motherboard in the PC died.

Some of the original information is gone but I will endeavour to try and find as much of the original plans as I can.

Bit of disclaimer - do this at your own risk and understand the laws when utilizing emulation.

## A brief history

I love video games. That's it, there is no denying it. I am and always will be a gamer.

Like most kids in the 80's I was bit by the Atari/Nintendo bug early on. Growing up I had a multitude of game systems and spent more time than I care to admit playing them. I can remember renting a copy of Megaman, waking up at 5am to play, so I could sneak in time before my mom booted me outside.

It didn't stop at console games. It branched out to early PC (we're talking 486dx66 until today) and of course in my pre/teen years the Arcade.

Being a maker at heart it only made sense to build my own machine.

## Build criteria

A few of the things I wanted in the build (in no particular order):

- [x] Full sized cabinet (modelled after street fighter/mortal combat dimensions)
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

Parts list:

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

I-PAC 2:

Picking a solid usb-controller to make button mapping WAY easier. A controller specifically designed for arcade input also helps with being able to read a bunch of inputs being pressed at once. For this I went with the I-PAC 2. The modern day versions support a few additional buttons which help with alternate controls such as pause, shuffle, menu, back, etc... I would utilizing these. My I-PAC lets you access these commands via "shift" functions - that is, you hold down Start-P1 and press specific buttons for specific actions.

Joysticks:

I wanted the absolute best option I could find here. It is important that these can take a beating. I ended up going with the Mag-stik and have been very happy with them. A cool feature is the ability to lift and twist the stick to move from 8-way to 4-way controls. This is great for old school games like PACMAN that only support 4 way controls.

Buttons:

As with the joysticks, I wanted the closest thing to real as possible. I am very happy with how the classic pushbuttons worked out. Unfortunately at the time there wasn't an option for LED buttons. This would be a cool feature as you can light them up ingame based on whether or not they're active!

Ensure to make space for wiring and button placement. There is a lot going on in there so leave room.

As mentioned above, there is support for a variety of other buttons. At the very minimum it is advised to have buttons for player 1 and player 2 start and coin add.

Wiring:

This was a lot of a fun. There were a lot of wires to be cut, stripped and crimped to put this together. Overall it works well and didnt require soldering.

## Build Pics

##### Mag-stik close up
![mag-stik](https://github.com/andruschak/arcade-machine/blob/master/images/joystick.png)

##### Panel during build
![holes cut](https://github.com/andruschak/arcade-machine/blob/master/images/control-panel-one.png)

##### Finished panel
![finished panel](https://github.com/andruschak/arcade-machine/blob/master/images/control-panel-finished.png)

 
## Display


## Sound


## The PC

The original PC that I used for this project was a Core2Duo e8400, 4gb ram and a 230gb hd. It proved to be more than adequate horsepower for the games I was looking to play (pre 2000).


## The return of PC
 

### Software

### Front end

### ROMS

## What's next?
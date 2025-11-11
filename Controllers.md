If you are planning to spend considerable amount of time on the OoT Randomizer, your controller will be your new best friend. But even if you're only planning to play on occasion and/or very casually, the choice of controller matters greatly.

Even if you're a casual player, at some point you will want to learn some tricks nontheless, some more difficult than others and most requiring precise inputs and movement patterns that are not usually required when casually playing games. See [[Basic Movement Theory]] for more information on the topic.

It is advised, not to ask for "the best controller" on any of the community discords. Within 20 minutes you will most probably heard every possible manufacturer on the market and be none the wiser for it. 

Some pointers on choosing the right controller for your purpose:

### Wired or Wireless

With most controllers and platforms nowadays we are free to chose between wired (often USB) or wireless (usually 2.4Ghz or Bluetooth).

Some people believe that wireless controllers have significant disadvantage compared to wired controllers. This, however, also depends on your choice of playstyle. While wired controllers are in fact faster in terms of latency (usually about 1ms) compared to wireless controllers (8-12ms) - and while you _might_ not be the best player in history with using a wireless controller because of it - let's put this into perspective:

One millisecond is one thousandth of a second. Ocarina of Time was designed to run with 20FPS - twenty frames (rendered image units) per second. Modern emulators will usually port this to 60FPS - the common frequency of most computer monitors - basically by playing every frame 3 times. so the game interacts with us at 20 frames per second. This means that each frame has a duration of 50ms in which it interacts with us. So even the response time of a wireless controller leaves plenty of time to interact with even the most frame-perfect inputs for the most complex of tricks. 

With this information at hand I will state an unpopular and debatable opinion: It simply doesn't matter. Play with whatever you're more comfortable with. 

### Button Layout

There are, of course, modern USB or wireless rebuilds of the original N64 controller if you want the most nostalgic feeling. Since they often provide very basic protocols their calibration properties and reliability tends to be severely limited.

Several controllers out there have a more modern or common shape but  emulate the layout of the N64 by providing the yellow C-buttons for example. One common example is the so called "Brawler 64".

If you prefer using a common modern gamepad like Xbox or PlayStation controllers you will need to re-map the buttons to match the required inputs for the N64 in your emulator. This basically means, that since there are no yellow C-buttons present, you will need to find a place to make them sit on other buttons instead. See below for more considerations on this.

### Controller Size & Shape

The arguably most important thing about choosing a controller that is right for you is that it is _right for you_.  A bad controller will always ruin your game experience and the best controller on the market can be wrong for you if you have specific needs.

This basically means that 

- Its size and shape should fit the size of your hands
- Its weight should feel comfortable and stable but not too heavy 
- Control sticks should have the right height for your finger length
- Control stick tops should have the right shape and should be controllable for you - meaning that you don't accidentally slip and have good control over the stick.  (Although this can be easily adjusted by rubber covers sold in all shapes and colors everywhere on the internet.)
- Control sticks should have - or be adjustable to - your desired level of pressure needed to incite movement in the game. (This can only be fixed by calibration to a limited amount.)

If you have disabilities or other problems with your motor skills, fingers or hand movement, exceptionally large or small hands or anything else, this can be a difficult task. Don't hesitate to go to a store and test out a whole shelf of controllers until you feel one that is right _for you_.

### Octagonal Gates

Most older gamepads - like N64 or GameCube controllers - did not have round holes around their control sticks, but instead had notches in the 8 cardinal directions. That had something to do with the way angles and movements were calculated with what was possible on the controllers and consoles and games back then with very limited space and power for calculations and stuff. 
Nowadays controllers compute directions on a much more precise level. That is why a completely circular cutout around the control sticks is the norm for Xbox, PlayStation or Nintendo controllers. 

When playing a game that was designed for it and especially when aiming for tricks at some point that require precise movement in the cardinal directions, these notches can be a huge help. As such, many people prefer using tailored retro-gaming controllers, which still come with these notches. However, there are lots of models for 3D printers or even very cheap manufactured replacement parts on the internet, that allow you to retro-fit (pun intended) your modern controller with a ring around the control stick that has these notches. The completely intuitive and totally logical (???) search keyword for this is "Octagonal Gate".

### Calibration & Deadzone

Some people plug in the controller they bought or had like forever and it just works for them right away. These are the lucky ones or already so used to playing with (this) controller that they don't face problems at all. But what if you're not one of the lucky ones or have to accommodate your disability, bad motor skills or lack of controller gaming experience?

Getting your controller to behave can be a daunting experience, especially if you use a very modern gamepad that comes with a multitude of possible options. Getting this to fit you specifically can be an experience with significant reward, though.

More often than not, if you are struggling with precise inputs, people will advise you to "increase your deadzone". Unpopular opinion: This is almost never the answer. 

So what does deadzone do? Because control sticks are moving parts and sensors always have some kind of measurement tolerance, all emulators and input calibration tools have the option of setting a deadzone. This describes the zone in which the control stick is assumed to be "at rest". Within this radius, all control stick movement will be ignored and treated as zero. If you increase the deadzone, you basically increase the area within its movement circle, where no input is registered. That means, you have to move the stick farther to the side to produce movement. 
This is a tool for avoiding unintentional and false movements and nothing else.

So what do you do if you feel you lack control over your movement? 

If your controller doesn't come with a calibration tool then your possibilities are in fact limited. You can try and adjust this by routing the signal through an abstraction layer like Steam and introduce additional configuration options regarding the curves. They usually come with other trade-offs and bring their own problems to the table.

If you are struggling with movements I sincerely suggest to invest in a controller that can be calibrated to your needs and comfort level. Adjusting curves to more aggressive or more relaxed ones that not simply restrict the available movement like deadzone does, but ramp them up or down on a curve providing for slower responses in the lighter movements and better control over slow movement. Most modern controllers can also store profiles locally so you can switch them with a single button. Let them laugh because they think you're overcomplicating things if you need separate controller profiles for doing tricks or doing shooting galleries and welcome to the club. If it works for you then it's the right thing to do.

Additional info on controller calibration for certain platforms and controllers can also be found in the [[https://wiki.ootrandomizer.com/index.php?title=Controller_Setup|ootrandomizer.com Wiki]].
### Button Mapping for Emulators

I stressed make it right _for you_ before already but I will stress it even more here: Make your emulator behave in a way that fits you personally.

Most gamepads do not come with the C-buttons the N64 had. So they have to be re-mapped somewhere on your controller. There are some common patterns that many people use, but the most important thing is that it fits you. If your brain expects a certain thing to be somewhere - map it there and please don't spend hours or weeks trying to re-wire your brain to expect differently.

Many people map the C-buttons to the right control stick since it is not used for camera movement in OoT. Other people map the C-buttons to the D-Pad and re-map the D-Pad to the right control stick. I think these are the most common patterns. 

But there are many more possibilities. While the N64 only had right and left shoulder buttons and OoT didn't make use of the left one because your hand was usually in the middle moving and targeting with Z, you have 2 of 4 shoulder buttons most modern controllers possess at your disposal. Use them as D-Pad for boots or as C-buttons. You played to much Horizon and expect your bow to always be on right shoulder? Then by all means, map whatever C-button you usually put your bow on there. Be creative. If you press a button all the time because your brain expects a certain item or functionality there, then _put it there_. It is a freedom emulators provide we should make maximum use of to accommodate ourself and make the gameplay experience as enjoyable as possible.
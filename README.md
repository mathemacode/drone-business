# drone-business
 A picture book story of how I found a niche in the world of radio controlled aircraft
 and ended up creating my own online gig at 13 years old custom building and selling unmanned aircraft 
 electronic systems.
 
### Contents
[Foundations](#the-beginning-science-fair-2011)  
[Research](#research-2012)   
[First few years](#business-2013---2014)   
[My finest work](#my-finest-work-2015---2016)   
[Personal UAS Setups](#my-personal-setups)

![workshop](./pics/workshop1.jpg)
![ground2](./pics/wing_field_station.jpg)
![highq](./pics/case_setup_full.jpg)


# The Beginning: Science Fair 2011
![science-fair](./pics/sciencefair.JPG)

I convinced my parents I needed an RC jet for a science fair project on UAVs as a display item during 
the presentation of this project at my middle school's science fair.  And so it happened, that I had a 
SkyFun jet from HobbyKing and a cheapo 72mhz radio control.  I promptly tried to fly it and crashed, even 
before the science fair itself.  I repaired it and still displayed it on the table with my giant poster board 
above.  Later on in life, I used this poster board to create a shipping box large enough for a RMRC Penguin 
aircraft frame after I was done flying it and had moved on to other projects.

# Research: 2012
I obviously had no money at 13 years old to buy any drone technology, but I basically researched as much as I could. 
This was during the time of YouTubers like Team Blacksheep (Raphael Pirker), muni86, and Crashz9, who were all pioneers of 
the world of FPV (First Person View) radio control piloting.  Raphael was of course, popular for his flight over New 
York City, which blew up the RC internet for some time about the dangers associated with FPV flying.

FPV in 2012 was hacking, soldering, and custom wiring looms everywhere.  There was no DJI Phantom to fly, and 
very little (read: zero) ready-to-fly FPV aircraft.  As I read RCGroups and FPVLab on a daily basis, I started to 
realize that there was a significant market for this sort of electronics setup service in the FPV hobby.  If you knew 
what parts to buy and how to wire the stuff, it was a breeze.  But with many folks still getting used to touch screen 
phones, this was a significant challenge.

And thus, the idea was born: I can learn how to set these wireless video link systems up for RC aircraft and sell them!

# Business: 2013 - 2014
I made a couple hundred dollars my first few years, but this was basically like being a millionaire for 
my age.  Here are some of the setups that I was building - simple, clean systems with cameras, 
transmitter/receiver combinations, antennas and video monitors, all with the right battery plugs, filters, and adapters to 
make it ready to go for the customer.  I even had a few OSD setups in there (On Screen Display of flight 
and aircraft characteristics).

### Popular Monitor Setup Example
- 1.3 GHz Video Transmitter & Receiver
- Notch Filter on vTX to decrease interference on 2.4 GHz control bands
- Set of circularly polarized antennas for best all-around performance flying around ground station
- Deans "tap" adapter for 3S LiPo main aircraft battery power to video system
- Filtering on power input side too on vTX to eliminate lines in video
- Phillips 9'' monitor
- GoPro plug on vTX for live video feed straight from recording camera

This is a classic system which I built on many different video frequencies for either GoPro live feeds, 
or a stand alone FPV (normally a small 1/3'' CCD security type) camera.  These were popular systems due 
to simplicity: just plug the tap adapter between the ESC & battery of your aircraft, mount the vTX, 
and hook up a 3S to the RX with the monitor on a tripod, and you are ready to go.

![1.3monitor](./pics/1.3_setup_monitor.jpg)

### Longer Range 2.4 GHz Example
- 2.4 GHz LawMate Transmitter & Receiver
- 2.4 GHz Patch Antenna (8dbi) (this was a longer range system)
- ImmersionRC EzOSD (On Screen Display - see monitor pic for it in action)
- Voltage regulator (12v to 5v) from amp sensor on EzOSD for LawMate vTX
- RMRC 700TVL FPV Camera (12v)   

This system was tricky because of the LawMate running 5v and camera on 12v.  The EzOSD was a breeze to set up
though, and some of the features it has far outweighed the price back 1/2 a decade - speed, distance, altitude,
direction to fly back to yourself, and of course power details and other features.  With a 500mw 2.4 GHz connection 
and this patch antenna, I've seen folks fly out roughly 10 miles and back without a hitch.  The LawMate brand fell 
out of style shortly after ImmersionRC, ReadyMadeRC, and HobbyWireless (and GetFPV, later) came onto the FPV scene 
and marketed their products much better to the hobbyist crowd and not the security / law enforcement crowd.

![ezosd](./pics/EZOSD_setup_full.jpg)
![OSD](./pics/HW_monitor_camera.jpg)


### Custom Wiring Looms ready for specific aircraft setups
- Cyclops NOVA Custom OSD wiring
- Deans current sensor, wired ready for camera, TX, and RC control RX output for RTH (Return to Home) 
functionality

I had a few requests simply to make integration of a certain electronic part plug-and-play for the user.  
This one below was an OSD designed to also connect in-line with the servos of the aircraft so that it could be
programmed to fly back towards home, for example, in the even of a radio link failure.

![OSD_wiring](./pics/OSD_setup.jpg)

# My Finest Work: 2015 - 2016
In these years I really fine-tuned my art, for customers and personal use alike, before leaving this amazing 
hobby of mine to fly down to university, with the intention of studying UAS at Embry-Riddle Aeronautical 
University.

#### Encased Repeater Ground Station type setups
- 1.3 GHz Transmitter/Receiver (with ComTech tuner)
- 1.3 GHz 8dbi Patch antenna in case top, linear whip antenna on vTX
- CYCLOPS On Screen Display
- Headtracking pan and tilt setup with accelerometers in goggles and 2 servos on camera mount
- 5.8 GHz ImmersionRC vTX in the case (top of 1.3 RX) to repeat signal for goggles
- RMRC 700TVL FPV Camera
- FatShark Dominator Goggles w/built-in 5.8 GHz module (WIRELESS long range due to repeater!)
- Backup/spectator 7'' monitor
- 3S LiPos, note independence from UAS power system (no risk of interference from ESC, best for high voltage UAS)
- Also made a custom wiring schematic for this one due to complexity
- DragonLink UHF system for aircraft control also set up - not pictured - ready for head tracking 

Case setups in general were always my favorite simply because I'm a very neat and organized person who likes 
things nicely put together and ready to operate as they are stored.  This case had everything needed - and even repeated 
the signal over to a pair of wireless video goggles (FatShark Dominators - the #1 goggles at the time), so the pilot 
could walk around while flying, or even just taking off, without having to deal with wires going to his or her head.

This pilot requested it all - from an On Screen Display, to Return to Home functionality, to head tracking and even 
a DragonLink UHF system so he/she could fly out long distances without worrying about the radio control link.  There was 
also a backup 7'' display monitor built into the case so that if the battery on the goggles' end died, 
you could swiftly run over to the case and pilot from the monitor built in (with the design that the sun would be 
blocked by the cover, which would be propped up by a small rod to aim it towards the general direction of flight).  This was a 
great idea from the pilot and something I hadn't considered before as a backup "safety net" for redundancy.  Also, spectators 
could take a gander at what was going on while the pilot was focused in his/her goggles.

The CYCLOPS TORNADO OSD is an incredibly powerful device - as you can see in the 3rd picture where I am holding the monitor, 
this OSD had it all, including the heading spot in the middle and bars on the right, left, and top to aid in maintaining 
level flight for long periods of time (or watching how fast you're descending//ascending).  With the box being powered by a 
giant 8,000 mAH 3S LiPo, this case was good for multiple hours of operation.  I also specifically chose a lower power output 
5.8 GHz repeater transmitter so that it would not burn out without as much airflow as one could expect on an aircraft.

All said and done, I was jealous when I shipped this system out, and am extraordinarily proud of the end result.  The pilot 
loved it as well!

![highq](./pics/case_setup_full.jpg)
![wiring](./pics/Wiring.jpg)
Here is a pic before encasing the system:
![before-case](./pics/complete_setup_complex.jpg)

#### Diversity Repeater System with Recording DVR of Live Feed
- DUAL 1.3 GHz Video Receivers
- Stock whip antenna on one, Video Aerial Systems antenna on the other
- All mounted on back of VAS antenna
- Eagle Eyes diversity system 
- DVR also wired in to record live feed from aircraft
- 25mw 5.8 GHz vTX to repeat signal to video glasses

Diversity is a useful function if the pilot desires to fly out long distances in one direction, but also for example, wants to 
take off in the opposite direction so he would be flying BEHIND a patch antenna and then out front for the duration of the 
mission.  The EagleEyes unit takes two inputs for receival of the video signal and chooses which one is strongest.  Another valid 
option is antenna tracking, which automatically points the antenna towards the aircraft while it's flying, 
but those systems are few and far in betweeen, and generally antiquated now with diversity and circularly polarized 
antennas making a huge mark in the market.

![diversity](./pics/diversity_setup_back.JPG)
![diversity2](./pics/diversity_setup_antenna.JPG)


# My Personal Setups
Over the years of course, I built many setups for myself, here are just a few that I am proud of that I 
set up on different frequencies for different purposes.

#### [1.3 GHz] Finwing Penguin by ReadyMadeRC
Purpose: long range.  Easily flew out a few miles and back with this over the country, and also did some altitude 
flights.
![penguin](./pics/RMRC_Pelican_field.jpg)

Here's me on the sticks testing flying LOS (line of sight) with my Taranis hooked to DragonLink & SR771 antenna.
![flying](./pics/me_flying.png)

#### [2.3 GHz] Custom "Wicked Wing" Sloper Conversion to powered
Purpose: sport.  2.3 GHz had just been approved by the FCC due to RMRC's diligence helping the FPV community,
and I wanted to see how well it performed.
![wing](./pics/wing_field_station.jpg)

#### [900 MHz] CrashTestHobby Flying Wing
Purpose: Sport, and testing horizontal antennas onboard.
![groundstation](./pics/ground_station_CTH.jpg)

#### CF Hexacopter for Aerial Photography
Purpose: honestly just wanted something to lift my DSLR in the air and I wanted to build a hex because they look cool.
![hex](./pics/hexfly2.png)

## ... and I still fly (fairly) regularly!
![goblin](./pics/goblin.jpg)
![launch](./pics/handlaunch.png)
![logo](./pics/logo500.jpg)









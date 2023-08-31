# Build Log

    My build log for IQUNIX ZX-1 SFF PC.

# Table of Contents

## Foreword

- The main reason I decided to write this is because someone else made a [Reddit Post](https://www.reddit.com/r/sffpc/comments/zu25f9/first_sff_iqunix_zx1_evga_3080_ftw3_13700k_pics/?utm_source=share&utm_medium=android_app&utm_name=androidcss&utm_term=1&utm_content=share_button) logging their ZX-1 build process which I found to be incredibly helpful when I was building my own especially since I also griefed over the EK Nucleus Cooler not fitting in my case.
- Plus I kind of just liked the concept of documenting the experience.
- It's really unlikely that many people will be building in the ZX-1 much in the future as a result of parts being kinda difficult to find as well as the growing market of decent SFF cases at cheaper prices.
  - Not only that but I imagine IQUNIX may release a new version of the case to accomodate all the beefier (larger) new gen CPU Coolers.

## Notes

- This case will really only accomodate a SFF-catered Power Supply Unit so make sure of that.
- Additionally, this case will need a Mini-ITX Motherboard since no other form factor will fit.
- Keep in mind that you need to do things in a very specific order when building in the ZX-1 and probably all SFF builds due to the small amount of space you are working with.
- Another thing about the ZX-1 in particular is that the finish will get scratched up if you aren't careful, so be careful when flipping it around during assembly and maybe place it on a soft surface (like the bag it comes in).
  - Just make sure the soft surface you use won't shock/fry your build components I guess, which is why I used the bag it came in along with being very gentle with placing it when I was flipping it on its side and vice versa.
- Make sure the Liquid Cooler you use has a pump that is no taller than 55mm since otherwise, it will not fit the case.
  - Learned the hard way that there are basically like no Liquid Coolers on the market anymore with a pump that is shorter than 55mm.
  - I guess the new gen stuff requires beefier hardware.
  - I ended up using an EK Elite 240 AIO Liquid Cooler from my old build.
  - Which reminds me, make sure your radiator is of 240mm in size since thats the only size the IQUNIX ZX-1 will accomodate (unless you go smaller with a 120mm for some odd reason or another).
    - Although I guess the shortage of AIO Liquid Coolers with pumps smaller than 55mm might force you into making a choice like this...
    - Why did EK have to discontinue the Elite series...
- I've heard that Intel CPUs run hotter than AMD CPUs so I might suggest going for AMD for this build just because it's a smaller case and so heat management is a bit trickier due to how cramped everything is.
  - I am Team Orange though so I might be a bit biased.
  - I also went AMD for this build because in the words of Linus Torvalds himself: _"Fuck NVIDIA."_
- I recommend checking out my [Post-Build Checklist](https://github.com/emaanr/posts/blob/main/post-build-checklist.md) since I go over some undervolting stuff (among other things) that will help with CPU and GPU temps.
  - Sources cited of course but do your own research as well since I'm just a noob with too much free time and money to waste apparently.

## Parts

## Log

### Remove Case Panels

- Removed all four case panel components:
  - Top Bracket
  - Front Bracket
  - Back Bracket
  - Bottom Bracket

### Assembling Motherboard

- Got the _stuff_ on the motherboard.

#### CPU

- Lined up the triangle symbol on the socket with the identical symbol on the chip itself.
- Held my breath and placed the CPU into the motherboard socket, praying I didn't screw up the pins (I didn't).

#### Storage

- Installed storage into the NVME M.2 slot on the back of the motherboard.
  - Chose the back since it'll be much harder to get to without disassembling build to some extent if I want to add more storage in the future.
- Inserted RAM, which only goes in one way (lined up the ridges) and made a very satisfying _click_ sound once in place.

### Mount PSU

- Mounted the Power Supply Unit on the top most screw placement because I was determined to make space for a bottom fan.
- I also plugged in the included PSU Extender cable provided with the ZX-1 which I would later learn I missed an important step with (didn't route it properly oops).

### Mount the Motherboard

> **Note:** The Motherboard mounts upside down in this case.

- I decided to mount the PSU first because I know that is the location I want it in to make space for the bottom fan, after which I went ahead to mount the Motherboard to the case.
- I also went ahead and connected the provided PSU CPU Power Cable since it is located in a corner of the Motherboard that will be very annoying to get to later.

### Connect PCIE 4.0 Riser Cable

- The IQUNIX ZX-1 comes with a PCIE 3.0 Riser Cable for some reason so I bought a PCIE 4.0 Riser Cable to use to mount the GPU on the backside of the case.
- Trust me when I say you definitely don't want to forget to do this right now...I did on a previous build and didn't realize until I was completely finished with the build at which point it was nearly impossible to get it on there without doing some disassembly.
  - Major headache that caused me a lot of grief for sure.

### Connect Front Panel Wiring to Top Bracket

- The IQUNIX ZX-1 case came with the front panel wires disconnected for people to selectively plug in.
  - I decided to just use them all even though I _probably_ didn't really _need_ the HD Audio capability, however my perfectionism got the best of me.
- At this point I kinda just connected them to the front panel IO and then route them through the left side of the PSU until I was ready to plug them into the Motherboard.

### Mount Liquid Cooler to Top Bracket

> **Note:** I didn't mount the pump block to the socket at this point. This is in fact one of the last things I did to make sure I have plenty of room to work and connect other things in the build. I wanted to make sure I cable management was as good as possible since I want the clearance at the bottom of the case to accomodate an additional Noctua fan in a pull configuration to pull cold air into the PC and ideally replace/push out the hot air being pulled out by the top fans.

- Placed Noctua Fans on the case bracket in a push configuration (pushing hot air out of the PC) and then route the pump block through the opening before placing the radiator on top of the fans.
  - Ran the screws through the bracket mounts, through the fan holes, into the radiator with the provided radiator screws.

> **Note:** Make sure to use the provided radiator screws or you risk other screws screwing too far and damaging the actual radiator.

- This part was quite annoying, so I first focused on getting all the screws actually screwed through and into the radiator after which I was able to slide the radiator + fans onto the position I wanted on the bracket before fully tightening the screws.

### Connect PSU Cables

- The PSU truly has so many cables.

#### CPU Cable

#### PSU Cable

#### VGA/GPU Cable

#### SATA Cable

- Did this later/at the end sorta.

### Connected Wires to Motherboard

- Mostly just Front Panel wires:
  - Preinstalled LED Wires
    - Which was a real pain to fit given the small separated connectors and little clearance due to the Cooler Pumps.
  - USB-A
  - Forgot the name of the last one
- All the other wires I'd had to connect were the PSU Cables which I already talked about.

### Mounted Pump Block to CPU

- Tucked the RGB Fan connector away because screw RGB.
- Connected the power connector to the CPU fan header.

### Connecting PSU SATA Cable and PSU Extender

#### PSU Extender

- The ZX-1 comes with a PSU extender and despite it being the first step in the manual I foolishly did not route it though the outer socket on the case...So I had to unscrew the Top Bracket with the Cooler on it to make space to unplug the extender and route it through the case first oops.

#### PSU SATA Cable

- On the bright side, unscrewing the Top Bracket allowed more clearance to route the PSU SATA Cable to the back of the case.
- This was not the last time I had to unscrew the Top Bracket...

### Zip Tied Cables

- After routing the PSU cables to be kind of smushed out of the way I zip tied some of the PSU cables to ensure proper clearance before mounting the bottom fan.

### Mount Bottom Fan

> **Note:** Make sure the fans are not obstructed by wires at all. That is, the wires shouldnt be touching the fan blades. They should be able to spin with no interference. Although all of this probably goes without saying it was helpful to keep in mind since other people had this issue.

### Remove Motherboard Shield

- My Motherboard in particular has a chonky shield covering one of the NVME M.2 storage slots that also somewhat obstructs the Fan Headers.
  - So I decided to remove it to make it easier to connect all the fans to the Fan Headers.

#### Connect Fan Headers

> **Note:** For whatever reason, my Motherboard has Fan Headers with non-traditional connectors. That is, it's not the standard 4-Pin connector. This resulted in a decent amount of confusion on my end as well as slight panic/grief. However after doing some googling I realized the Motherboard provided a proprietary fan splitter and proprietary adaptor of sorts to actually connect my fans. So after some searching through boxes I finally found them (thank god).

- I used the provided proprietary fan splitter for the top two fans and then plugged that into one of the Headers.
- Then I used the provided proprietary "4-Pin Fan Connecter to whatever the heck my Motherboard was using for its Fan Header ports" to connect my bottom fan to the other header.

#### Connect HD Audio

- The connecter for this was also located in the same general region so this got plugged in at this point as well.
- Though I already made sure to route it how I wanted to before getting to this step in the process.

### Connect SATA Cables

### Install GPU on Riser Cable

- Had to unscrew the Top Bracket again here to make space to install the GPU in a way that wasn't cancerous.

> **Note:** I ended up having the unscrew the Top Bracket again later when I realized I had guillotined the SATA Cable wires when I screwed it in after installing the GPU...Luckily that was the last time.

## Post-Build

Refer to my [Post-Build Checklist](https://github.com/emaanr/posts/blob/main/post-build-checklist.md) for this.

<img width="3905" height="447" alt="gameboy_enhance" src="https://github.com/user-attachments/assets/824b6be6-7496-42c1-b8b1-e3ef20e5aa76" />

# Game Boy Enhance (AGBM)

The Game Boy Advance was the very first system I ever purchased with my own money way back in 2002. It has a special place in my heart! Now, after spending so much time doing Game Boy Color projects over the past few years, I decided to get to work on the GBA to see what I could do with it to modernize and improve it a bit. Luckily, I was able to complete this by the 25th anniversary of the GBA's release in North America to celebrate!

<img width="3982" height="2900" alt="agbm11_front" src="https://github.com/user-attachments/assets/45f4c4b2-f8e7-4b51-b522-dd91a46b12d3" />

<img width="3982" height="2900" alt="agbm11_back" src="https://github.com/user-attachments/assets/285afe47-ba86-495d-8823-06498b6e0c9a" />

There's not a whole lot that needs to be "fixed" with modded GBAs - you can get away with a pretty great modern system by simply throwing in a screen kit on an original console. But as you probably well know, there are a *ton* of really damaged and crusty systems out there that are doomed for landfills (or for the closets of sickos like me). So at least for that reason, this fully open source GBA recreation only requires the original CPU and RAM - every single other part is **brand new** or has easily-sourced replacements available.

Other than that, you might be asking yourself - what separates this from a regular modded system, or one of those fancy Funnyplaying GBA boards? Well, here's a quick run-down:
- The audio on the AGBM is crystal clear, not dependent on whatever screen kit is being used, and has **stereo** output on the headphone jack (unlike the FP GBA) - <a href="https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/Audio-Recordings">listen to the audio samples in the Wiki</a>
- The AGBM draws ~150mW less than the FP GBA (even with the fancy LEDs off) depending on the AGBM model - this equates to anywhere between 1 to 4 hours **more** playtime depending on the power draw based on your settings (like brightness level) - <a href="https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/Power-Draw-and-Battery-Curves">check out the battery curves page in the Wiki</a>
- The AGBM is *also* more efficient than using an original GBA board with a screen kit installed in almost all situations (again, see the Wiki for more info)
- Other than the CPU and RAM, the AGBM uses **all brand-new components** - even the power switch and audio jack
  - The AGBM-02 has space for a new RAM chip, if your old one is damaged or missing!
- The AGBM has offerings for powering through AA batteries (AGBM-0X models), or native LiPo support (AGBM-1X models)
- The AGBM includes some user-configurable hotkey features, like a soft reset button combination, or for replacing touch controls on screen kits
- The AGBM has built-in tactile switch support if you like the SP-style clicky buttons
- The power LED now flashes when the battery is within minutes of dying, like the SP did
- The original locations of button test points have been retained on the AGBM for easy compatibility with existing mods, like Nataliethenerd's ARC GBA or insideGadgets' ClockxControl - <a href="https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/Mod-Compatibility">see this page on the Wiki for mod compatibility</a>

This project is a labor of love, built on the backs of the greats (noted in the Acknowledgements below). I have made it **fully open source** with all the design files available and even included some <a href="https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/Schematic-Explanation">technical explanations</a> to spread the love across the retro gaming community.

**If you find any errors or inconsistencies in this repository, let me know and you'll receive one (1) internet point.**

## Board Variants

Here's a quick table summarizing the differences between the board numbers. Boards that are numbered with 0X use AA batteries, and those with 1X use lithium-ion batteries.

| Board Number                                                                                           | Battery Type | Main Converter | Typical Battery Life | Donor RAM Required? |
| ------------------------------------------------------------------------------------------------------ | ------------ | -------------- | -------------------- | ------------------- |
| [AGBM-CPU-01](https://github.com/MouseBiteLabs/Game-Boy-Enhance/tree/main/AGBM-01%20(AA%20Batteries))  | AA           | LTC3527        | 5h20m to 15h30m      | Yes                 |
| [AGBM-CPU-02](https://github.com/MouseBiteLabs/Game-Boy-Enhance/tree/main/AGBM-02%20(AA%20Batteries))  | AA           | TPS63802       | 5h20m to 15h30m      | No                  |
| [AGBM-CPU-11](https://github.com/MouseBiteLabs/Game-Boy-Enhance/tree/main/AGBM-11%20(Lithium-ion))     | Lithium-ion  | LTC3527        | 5h to 13h30m         | Yes                 |
| AGBM-CPU-12                                                                                            | Lithium-ion  | TPS63802       | Not tested yet       | No                  |

## Important Things Before You Start

1) This project requires you remove some components from an original Game Boy Advance. This will require a hot air rework station, or a lot of low melt solder - a hot plate is not recommended because the board is two-sided.
2) The rest of the project will require extensive soldering capabilities, including leadless packages (QFN) - **do not attempt this project if you do not have sufficient soldering experience.**
3) **FOLLOW THE GUIDE IN THE WIKI FOR ASSEMBLY AND TESTING.** It is laid out so you can test as you assemble to help you find problems before you're too far into the project. If you ask me why something doesn't work, I'm going to ask what step of the guide you are on.
4) If you are making a design that uses a lithium ion battery, please understand the risks you are undertaking and read the guide extensively - lithium ion batteries can *explode*, especially if they are no-name brand ones from AliExpress. I personally recommend *against* making the lipo version and sticking with the AA version for safety, versatility, and for longer battery life.
5) I am not responsible for any damage you do to your self or your property. Attempt this project at your own risk. (See previous note for warning about lithium ion batteries)
6) I do not guarantee design compatibility. You may encounter issues with certain games. There is also a chance I have made an error in the design or the BOM - if this is the case, I will do everything I can to address the problem as quickly as possible.

## Ok, so how do I start?

**<a href="https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/How-to-Use-this-Wiki">I break down the process of making an AGBM in the wiki - please read it thoroughly and follow all the steps!</a>**

Enjoy :)

## Acknowledgements

- Thanks to the awesome members of [my discord](https://discord.gg/Y5aDvCcpbX) and the <a href="https://moddedgameboy.club/">Modded Gameboy Club</a> for their feedback and support during the project development. (Special shoutout to White for the suggestion of the name "Game Boy Enhance.")
- Thank you Redherring32 for starting the [OpenGBA](https://github.com/Redherring32/OpenTendo-AGB) project and allowing me to finish it up. He measured out the board and placed the ports and saved me a *ton* of time.
- Special thanks to lidnariq from gbdev for helping me realize the best possible audio quality out of this thing.
- Thank you to Riggles and White from the r/Gameboy discord server for their shell polishing tips!
- Thanks Badwen from discord for supplying me a Funnyplaying GBA for comparison purposes.
- Thanks Zekfoo for providing inspiration with his [AGZ](https://github.com/Zekfoo/AGZ/tree/main) project (specifically giving me a great idea of where to put the USB-C and JST connector for the LiPo version).

## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. You are able to copy and redistribute the material in any medium or format, as well as remix, transform, or build upon the material for any purpose (even commercial) - but you **must** give appropriate credit, provide a link to the license, and indicate if any changes were made.

This project is the culmination of over a full year of research, development, and testing. I have made this project completely open-source, and have put hundreds of hours of work (and dollars!) into it, so that many people can enjoy it. **Please** give me appropriate credit where credit is due.

©MouseBiteLabs 2026

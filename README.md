# Game Boy Enhance (AGBM) - Work in Progress

The Game Boy Advance was the very first system I ever purchased with my own money way back in 2002. It has a special place in my heart! Now, after spending so much time doing Game Boy Color projects over the past few years, I decided to get to work on the GBA to see what I could do with it to modernize and improve it a bit. Luckily, I was able to complete this by the 25th anniversary of the GBA's release in North America to celebrate!

<img width="2364" height="1308" alt="image" src="https://github.com/user-attachments/assets/c8fe37ab-c9ca-49e4-b1c4-b6464e1a34fe" />

<img width="2364" height="1308" alt="image" src="https://github.com/user-attachments/assets/efcdfb47-093b-4c6f-9c5e-1ee475ac6f77" />

There's not a *ton* that needs to be "fixed" with modded GBAs - you can get away with a pretty great modern system by simply throwing in a screen kit on an original console. But as you probably well know, there are a *ton* of really damaged and crusty systems out there that are doomed for landfills (or for the closets of sickos like me). So at least for that reason, this fully open source GBA recreation only requires the original CPU and RAM - every single other part is **brand new** or has easily-sourced replacements available.

Other than that, you might be asking yourself - what separates this from a regular modded system, or one of those fancy Funnyplaying GBA boards? Well, here's a quick run-down:
- The audio on the AGBM is crystal clear, separate from whatever screen kit is being used, and has **stereo** output on the headphone jack (unlike the FP GBA) - <a href="https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/Audio-Recordings">listen to the audio samples in the Wiki</a>
- Ignoring the screen kit, the AGBM draws ~56% less power than the FP GBA (with the fancy LEDs off) - this equates to roughly 45 minutes **more** playtime at max volume/brightness - <a href="https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/Battery-Curves">check out the battery curves page in the Wiki</a>
- The AGBM has offerings for powering through AA batteries (AGBM-0X models), or native LiPo support (AGBM-1X models)
- The AGBM includes some user-configurable hotkey features, like a soft reset button combination, or for replacing touch controls on screen kits
- The AGBM has built-in tactile switch support if you like the SP-style clicky buttons
- The original locations of button test points have been retained on the AGBM for easy compatibility with existing mods, like Nataliethenerd's ARC GBA or insideGadgets' Embedded Rumble - <a href="https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/Mod-Compatibility">see this page on the Wiki for mod compatibility</a>

This project is a labor of love, built on the backs of the greats (noted in the Acknowledgements below). I have made it **fully open source** with all the design files and technical explanations to spread the love across the retro gaming community.

## How do I Start?

<a href="https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/How-to-Use-this-Wiki">I break down the process of making an AGBM in the wiki - please read it thoroughly and follow all the steps!</a>

Enjoy :)

## Acknowledgements

- Thanks to the awesome members of the <a href="https://moddedgameboy.club/">Modded Gameboy Club</a> for their feedback and support during the project development. (Special shoutout to White for the suggestion of the name "Game Boy Enhance.")
- Thank you Redherring32 for starting the [OpenGBA](https://github.com/Redherring32/OpenTendo-AGB) project and allowing me to finish it up. He measured out the board and placed the ports and saved me a *ton* of time.
- Special thanks to lidnariq from gbdev for helping me realize the best possible audio quality possible out of this thing.
- Thanks Zekfoo for providing inspiration with his [AGZ](https://github.com/Zekfoo/AGZ/tree/main) project (specifically giving me a great idea of where to put the USB-C and JST connector for the LiPo version).

## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. You are able to copy and redistribute the material in any medium or format, as well as remix, transform, or build upon the material for any purpose (even commercial) - but you **must** give appropriate credit, provide a link to the license, and indicate if any changes were made.

This project is the culmination of over a full year of research, development, and testing. I have made this project completely open-source, and have put hundreds of hours of work (and dollars!) into it, so that many people can enjoy it. **Please** give me appropriate credit where credit is due.

©MouseBiteLabs 2026

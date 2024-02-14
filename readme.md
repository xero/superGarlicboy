# super garlicboy

a garlic os theme for the rg35xx handheld emulation console based on the dmg gameboy color pallet that's trying to capture that retro-futurist portable arcade aesthetic we were promised.

# dmg inspired color pallet

`#1b2a09`
`#1f1f1f`
`#0e450b`
`#496b22`
`#4d533c`
`#8b956d`
`#9a9e3f`
`#c4cfa1`


# download

https://github.com/xero/supergarlicboy

# install

this theme is for garlic os. so it assumes you have already installed it. [follow the guide here](https://www.patreon.com/posts/garlicos-for-76561333).

## theme

copy the contents of the `skin` folder to your `ROMS` partition under `/CFW/skin/`

## retroarch colors

copy the `retroarch/garlic.cfg` file to your `ROMS` partition under `/CFW/retroarch/.retroarch/assets/rgui`

to enable it: launch retro arch's setting, then select `User Interface` -> `Appearance` -> `Menu Color Theme` -> `Custom`. Then under `Custom Menu Theme` select `garlic`

## boot logo

copy the `boot/boot_logo.bmp.gz` file to the root of your `MISC` partition

# setup

my theme should already be good to go at this point. this section of the guide i will suggest further optional device setup.

## bios

think of bios files are retroarch's implementation of the retro console's firmware. [download the newest bios files](https://archive.org/details/bios_RG353) for all compatible consoles and put them in your `ROMS` partition under `BIOS`

## roms

roms are the contents of the game cartridge's memory, containing all the actual game data. if you're lazy you can grab the "tiny best set go" and it's extra's to get a ton of good working games up and running quickly.
* [base set w/ most home consoles](https://archive.org/details/tiny-best-set-go)
* [expanstion with ps1](https://archive.org/details/tiny-best-set-go-extra-unofficial)
* [arcade expanstion](https://archive.org/details/tiny-best-set-go-arcade-update_202305)

but a better idea is to search the full console sets, and just grab the individual games you want. here's a list of known good "no intro" set's for most of the major consoles. these are the roms i personally use.
* [arcade](https://archive.org/details/MAME2003_Reference_Set_MAME0.78_ROMs_CHDs_Samples)
* [dreamcast vmu](https://archive.org/details/segavmu)
* [game gear](https://archive.org/details/nointro.gg)
* [gameboy advance](https://archive.org/details/nointro.gba)
* [gameboy color](https://archive.org/details/nointro.gbc-1)
* [gameboy](https://archive.org/details/nointro.gb)
* [nintendo nes](https://archive.org/details/nointro.nes)
* [pico 8](https://archive.org/details/picowesome-v1.3)
* [sega genesis](https://archive.org/details/nointro.ms-mkiii)
* [sega megadrive](https://archive.org/details/nointro.md)
* [super nintendo](https://archive.org/details/nointro.snes)

# meta

## origin story

i love customizing my stuff. after creating my dmg colorscheme for retroarch, i wanted to use it all over my retro console. the [onionboy hd theme](https://rg35xx.com/en/customization/garlicos-themes/) i was already using was pretty awesome, but much of the pixel art was catered to the miyoo mini. i started making small edits. changing onions to garlic and "mini" to "double x", all while subtly adjusting the colors. after a bit, i started hating the text on the main menu. so i resized and positioned all the images and removed the names. the game console icon set is one of the most popular you find in retroarch packs, because it's awesome. it's been curated by many talented artists. i updated pico 8 to the proper fantasy console artwork from the manual and did some other hatchet work to make them fit my theme's highlighting and personal taste. then created some more icons for the file manager, rom seach, and terminal apps i use. next i updated the gradient overlays to a dithered pixilated style and colors. and updated the d-pad navigation icon to look more nintendo-esque. finding the perfect wallpaper to match the vibe was a challenge. but i eventually typed "outrun pixel" into big-g and found a real gem. [the image](https://64.media.tumblr.com/8fc2f0787a39cfa8032c98986578fa78/tumblr_p8f7umWoYS1tlcqgyo1_1280.png) was freely released so i demixed it, lowering the color count and adjusting it to my dmg pallet, adding new dithering effects, and a few subtle layout tweaks. the author ever said she dug it [on x](https://x.com/mentalpoppixels/status/1755033910285611313?)! finally, to round the whole thing off, a custom garlic boot logo.

## credits

super garlicboy theme by xero
* https://0w.nz
* https://x-e.ro
* https://xero.style

_but it's based on lots of other peoples amazing work!_

main menu icons based off onionboy hd by jeltron
* https://pocketpixels.club/@Jeltron
* https://github.com/OnionUI/Themes/tree/main/themes/Onionboy%20HD%20by%20Jeltron

wallpaper is a demix of outrun pixel by mentalpoppixels
* https://twitter.com/mentalpoppixels
* https://tmblr.co/Z3iLXm2XnqbAH

icons are a modified version of the set by vidnez:
* https://github.com/Vidnez/retro-systems-icons-for-GarlicOS
which is based on the ruckage snes mini set
* https://github.com/ruckage/es-theme-snes-mini
which was later expanded by mahare
* https://retropie.org.uk/forum/topic/12583/snes-mini-theme/899u
* https://reddit.com/r/EmulationOnAndroid/comments/fxd2w9/dig_front_end_theme_minimix_10/

## license

*CC0 1.0 Universal / Public Domain*

since all of this is made from community freeware, i release mine in the spirit of kopimi as well!

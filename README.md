# Unclovered Lunarium

_A lightweight approach to removing Clover's services dependency_

<img src="lunarium.PNG" align="center" />

Important note: this is __NOT A REAL HACKING TOOLKIT__! This has been made, works and will work only in the game called Grey Hack!


## Objectives

Unclovered Lunarium aims to make Clover's Lunar accessible to everyone without any potential or actual risks for the user


## What has changed comparing to original Lunar?

There is a list of things that are changed so far:

    1. Removed intruder detection system(also known as "fstab" rshell)
    2. Removed hardcoded apt repository
    3. Lunarium launches in local mode ONLY. You can still use all of the CLI flags, though
    4. Removed all commands that are relying on servers to work
    5. Did some rebranding and applied more neutral theme
	

## Known Bugs

- escalate command does escalating on user's libraries even if user is connected to the remote host
- You tell me


## Installation Guide

- Download the sources and get them into the game
- Move __foxlib.src__, __lunariumcmd.src__ and __lunarium.src__ into your __/root__ folder
- Compile __lunarium.src__
- Launch compiled binary. Type __help__ to see all available commands


## Thanks and Credits

- [Grey Hack](https://store.steampowered.com/app/605230/Grey_Hack/)
- [Joe Strout](https://github.com/JoeStrout) - for creating [MiniScript](https://github.com/JoeStrout/miniscript)
- [Clover](https://github.com/cloverrfoxx) - for creating and open sourcing Lunar and [other scripts](https://github.com/cloverrfoxx/greyhack)
- Guest([fmaks](https://mstdn.social/@fmmaks)) and [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium) - for giving me naming idea

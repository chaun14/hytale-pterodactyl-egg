# hytale-pterodactyl-egg
Hytale server egg for pterodactyl / pelican panel

## The egg
Since it is quite early, this egg comes with a few limitations:
- To avoid having the updater re-downloading the game on each start, to update the game you have to tick the "Allow Update" variable on the startup tab
- For the server to be used, you need to authenticate though `/auth login device` on each restart

## Known issues
- Updates aren't applied automatically
- Unable to enable auth persistence due to an issue with the game getting the hardware UUID from the docker container

## A problem
You can contact me on my [discord server](https://discord.gg/hzBMbcQdCp)

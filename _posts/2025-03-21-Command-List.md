---
title: Command List
Date: 2025-03-21 12:00:00 - 500
categories: [commands, cheatsheet]
tags: [otto,commands]
---

# Below is an exhaustive list of Otto's commands and how to use them 




## Audio Player Commands

```yml
/play `link` # Provided with a youtube link, Otto will join the channel and being to play audio

/queue `link` # Provided with a youtube link, Otto will add the audio to queue

/pause # Otto will pause the current audio

/resume # Otto will resume the current audio

/clear_queue # Otto will clear all audios in queue

/stop # Otto will clear all audios in queue, then leave the channel
```

## CAIN/TTRPG Commands

```yml
/register_exorcist # Will bring up a series of 8 modals, provide the relevant information for your Exorcist. At the end you will be issued an ID and CID which Otto will send to your DM's. Do not lose your CID

/view_id `cid` # Provided with a valid CID, Otto will post your ID to the server

/view_sheet `cid` # Provided with a valid CID, Otto will send your Character Sheet to your Dms. Use the buttons provided to interact with the embed

/dice_roller `dice_amount` `dice_value` # Provided with an amount and value (3d6), Otto will roll those dice for you and post the results in the current channel (temporary message) and the #otto-speaks channel (permanent message)

/dice_roller_gui # Will send sets of buttons, the first set being value and the second being amount. Click the desired value (d4) then the desired amount (x8) and Otto will post the results in the current chnanel (temporary message) and the #otto_speaks channel (permanent message)
```

## Gambling Commands

```yml
/polymarket `url` # Provided with a valid Polymarket.com url to an open event, Otto will parse the list of available markets and create embeds for each one. Simply click either the `Buy Yes` or `Buy No` buttons to open a modal to bet on either one.
```
## Groove Grove Commands
```yml
/spin `names` # provided with a list of comma separated values, Otto will generate a gif of a spinning wheel which will decide on a winner then post both the gif and the winner's name in the channel
/nomination # sends a modal to create your music nomination. Asks for album, artist, and (spotify) link
/reup # provides your nomination with a new datestamp, allowing it to be pulled for the current week
```
## Misc Commands
```yml
/stats # Otto will post an embed of your stats within the server including xp,level, total messages, BetterBuck Balance and currently active bets filtered by resolve date
/leaderboard # Otto will post a paginated embed showing all users ranked by highest level and most xp
/ping # Mainly a test command, displays Otto's current ping
/export_level_stats # Creates a CSV of the user table within level.db
/export_betterbucks_data # Creates a CSV of the transactions table within polymarket.db
/help # Otto responds with the link to this site, likely how you got here in the first place.
/pointdiffs # Otto will post an embed showing the ten closest differences in server xp points from closest to furthest

```
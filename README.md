# Custom Jellyfin Discord webhooks

## Installation

To use these templates you will need to have the jellyfin discord webhooks plugin installed.

## How to enable notifications

- Navigate to the system notifications in the Jellyfin dashboard for the template you want to use
- Enable the notification and set it to only send to one admin account (otherwise you may get double notifications)
- Setup a discord webhook in the webhooks plugin

### Notification Type Key

For each of the templates these are the Notifications Types they support.

- playback-start = Playback Start
- playback-ended = Playback Stop
- item-added = Item Added

### EmbedColor isnt working

Due to the way Discord set up their api you send color in its Decimal value [(convert)](https://www.spycolor.com). The plugin doesnt use this so I have it hardcoded into the template, which you are free to change

## Preview

### item-added
![New movie webhook preview](https://user-images.githubusercontent.com/57121175/215383785-c3a9fccc-cc88-489d-aa65-e762bd1bed75.png)
### playback-started
![Playback started webhook preview](https://user-images.githubusercontent.com/57121175/215386632-3de7f7b1-da9d-43d6-923b-5cc725736bb0.png)
### playback-ended
![Playback ended webhook preview](https://user-images.githubusercontent.com/57121175/215386699-26e2d956-e074-4cfe-a445-b9c49ecb4e8f.png)

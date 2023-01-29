# Custom Jellyfin Discord webhooks

## Installation

To use these templates you will need to have the jellyfin discord webhooks plugin installed.

## How to enable notification

- Navigate to the system notifications in the Jellyfin dashboard for the template you want to use
- Enable the notification and set it to only send to one admin account (otherwise you may get double notifications)
- Setup a discord webhook in the webhooks plugin

### Notification Type Key

For each of the templates these are the Notifications Types they support.

- playback-start = Playback Start
- playback-ended = Playback Stop
- item-added = Item Added

### Color isnt working

Due to the way Discord set up their api you send color in its Decimal value [(convert)](https://www.spycolor.com). The plugin doesnt use this so I have it hardcoded into the template, which you are free to change

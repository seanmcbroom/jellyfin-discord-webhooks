# Custom Jellyfin Discord webhooks

## Installation

### Webhook Plugin

To use these templates you will need to have the Jellyfin webhooks plugin installed.

### How to enable a notification

- Navigate to the system notifications in the Jellyfin dashboard
- Enable the notifications for the webhooks you want to use, and set it to only send to one admin account (otherwise you may get double notifications)

### Create a new webhook

In the plugins tab, click on the webhooks plugin and create a new Discord webhook. Copy the template into the template section, don't forget to add the Server URL and other information. You will need to create a new webhook for each notification.

### Notification Type Key

For each of the templates these are the Notifications Types they support.

- playback-start = Playback Start
- playback-stop = Playback Stop
- item-added = Item Added

## Help

### EmbedColor isnt working

Due to the way Discord set up their api you send color in its decimal value. The plugin doesnt use this so I have it hardcoded into the template, which you are free to change. [convert here](https://www.spycolor.com)

## Preview

### item-added
![New movie webhook preview](https://user-images.githubusercontent.com/57121175/216639661-a43b8137-178a-4f2f-b36e-436989aaa7d5.png)
### playback-started
![Playback started webhook preview](https://user-images.githubusercontent.com/57121175/216639514-90945376-fb06-4446-b861-018be614cb9b.png)
### playback-stopped
![Playback stopped webhook preview](https://user-images.githubusercontent.com/57121175/216639570-1848cf78-3daf-4995-a3ac-037673190d06.png)
![Playback completed webhook preview](https://user-images.githubusercontent.com/57121175/216639615-25825104-31ff-4140-aade-82471e1081c5.png)

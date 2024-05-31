# Custom Jellyfin Discord webhooks

## Installation

### Webhook Plugin

To use these templates you will need to have the Jellyfin webhooks plugin installed.

### Create a new webhook

In the plugins tab, click on the webhooks plugin and create a new Discord webhook. Select the notification type (look below), then copy the template into the template section. Don't forget to add your Server URL and other information.
Repeat for each webhook you'd like to add.

### Notification Type Key

For each of the templates these are the Notification Types they support.

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
### User Locked Out
![User locked out webhook preview](https://user-images.githubusercontent.com/57121175/217963191-0b7a00ff-93bb-4746-8512-58a470b4afcc.png)


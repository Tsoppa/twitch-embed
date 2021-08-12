# Twitch Embed
## Livestream
[Embed Parameters & Example](https://dev.twitch.tv/docs/embed/everything)
## Chat
[Embedding Chat](https://dev.twitch.tv/docs/embed/chat)
## Video & Clips
[Embedding Video on demand(VOD) & Clips](https://dev.twitch.tv/docs/embed/video-and-clips)
## Direct from Twitch
![twitchiframe](https://user-images.githubusercontent.com/61386363/129261841-99048960-f287-4d6e-97ed-3218ae34ae40.jpg)
## Example
```
<script src= "https://player.twitch.tv/js/embed/v1.js"></script>
<div id="SamplePlayerDivID"></div>
<script type="text/javascript">
  var options = {
    width: "100%",
    height: "100%",
    channel: "<channel name>",
    parent: ["<website url>"],
    autoplay: false,
    controls: false,
    allowfullscreen: false
  };
  var player = new Twitch.Player("SamplePlayerDivID", options);
  player.setVolume(0.5);
</script>
```
[Full Code](https://codepen.io/tsoppa/pen/GRrVOXM)
## Requirements
[Embedded Experiences Requirements](https://dev.twitch.tv/docs/embed)

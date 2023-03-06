# LimiterFader - by Cussa Mitre ([@TheRuneloreSage](https://twitch.tv/TheRuneloreSage))

## Problem
You have a source with some kind of music that is playing in one volume/level in a scene.

You want that when you change to some specifics scenes, the volume fade out/in.

## Possible Solutions
There are some codes created by the community that allows you change a volume from a source. However, these solutions change the values from `start` to `end` in a single change operation, giving a bad user experience.

## What does this solution does?
You are able to configure which scenes you want to fade out the volume of the source, and how many seconds do you the change to take. This gives the source a nice fade behaviour when changing the scenes.

## How to configure?
1. In all scenes that you want the music playing, add the source.
2. Import the code below:

```
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
```

3. Configure the values in the Sub-Action

```cs
var scenesToFadeOut = new[]{"Main", "Game"};
var seconds = 3;
var minValue = -25;
var maxValue = 0;
var sourceName = "VLC Video Source";
var limiterName = "Limiter";
var interval = 100;
```

| Command | Description |
| --- | --- |
| `sceneToFadeOut` | List all scenes where the Limiter will use the `minValue`. The condition validates that the current scene starts with one of the defined values. You can add any number of values that you would like. |
| `seconds` | The fade duration |
| `minValue` | The minimum value for the Limiter |
| `maxValue` | The minimum value for the Limiter |
| `sourceName` | The source that has the Limiter |
| `limiterName` | The Limiter filter name |
| `interval` | How many milliseconds between changes in the Limiter value. Bigger values will make it go smoother. |

4. Make sure your OBS is connected and create a new event as below:

![image](https://user-images.githubusercontent.com/912710/223066811-64b3dc02-e728-4908-8c7e-3a92fe7cf51a.png)

5. Start to use it!

## Version history

- `v1.0.0` (2023-03-06): innital version.

# OBS Plugins (Updated 2025-03-18)

I highly suggest to start reading [OBS Settings](obs-settings.md) first if _you know nothing_ or _didn't setup anything_ already.

## Plugins

1. **[3D Effect](https://obsproject.com/forum/resources/3d-effect.1692/)**: Adds 3D perspective to a source (was from the old StreamFX).
2. **[Closed Captioning via Google Speech Recognition](https://obsproject.com/forum/resources/closed-captioning-via-google-speech-recognition.833/)**: Add real-time captions to your lives on Twitch only.
3. **[Gradient Source](https://obsproject.com/forum/resources/gradient-source.1172/)**: Adds a gradient background.
4. **[Move](https://obsproject.com/forum/resources/move.913/)**: Make sources movable and have animations, so they feel more alive and also react with audio.
5. **[obs-composite-blur](https://obsproject.com/forum/resources/composite-blur.1780/)**: Censor stuff you don't want to show (was from the old StreamFX).
6. **[obs-multi-rtmp](https://github.com/sorayuki/obs-multi-rtmp/)**: Enables OBS to multi-stream on any platform you want.
   1. **IMPORTANT:** Download the latest **Release** (not Pre-Release) ZIP FILE, not the installer, the installer is installing on `ProgramData` and is outdated.
7. **[obs-shaderfilter](https://github.com/exeldro/obs-shaderfilter/)**: Customize the appearance of your source with a shader filter.
8. **[Scene as Transition](https://obsproject.com/forum/resources/scene-as-transition.1704/)**: Use a entire scene to act as a transition.
9. **[Stroke Glow Shadow](https://obsproject.com/forum/resources/stroke-glow-shadow.1800/)**: Adds essential design filters to any of your sources (was from the old StreamFX).
10. **[Waveform (Audio Visualizer)](https://obsproject.com/forum/resources/waveform.1423/)**: Adds a visualizer to some sound scene.
11. **[win-capture-audio](https://obsproject.com/forum/resources/win-capture-audio.1338/)**: Filter any audio you don't want to output in 1 source.

## Themes

- **[Yami Resized](https://obsproject.com/forum/resources/yami-resized.1611/)** \*: Install at `C:\Program Files\obs-studio\data\obs-studio\themes` or your relative path and make sure your OBS is update, or else the newer file formats won't work. After this start your OBS and go to `Settings > Appearance` and change the "Yami" Style to "Resized".

## Scripts

1. **[obs-filter-hotkeys](https://obsproject.com/forum/resources/obs-filter-hotkeys.1125/)**: You can enable/disable filters with any hotkey.

- Requires **Python 3.7.9**: <https://www.python.org/downloads/release/python-379/>
- Also requires Python location setup: `%localappdata%/Programs/Python/Python37`

## Plugins which will lag your OBS:

- **SE.Live** (CPU LAG, did they fixed it?)

## Ingest Servers (URLs for multi-rtmp)

- **Twitch**: <https://help.twitch.tv/s/twitch-ingest-recommendation>, put your stream key at the end of the URL.
- **YouTube**: Go to YouTube, click on "Create", then go to "Go live" and "Stream", now copy the **Stream URL** and **Stream key** and paste on OBS if necessary.

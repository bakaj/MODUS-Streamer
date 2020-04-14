# MODUS-Streamer M4L
This is a Max4Live online collaboration tool that enables to send audiosignals lossless over network. The playback is in sync with an predefined latency such as 16bars. 
Currently it only works on MacOS due to file locking in Windows. This plugin is in it's very early stage!

## Framework
The basic concept is to record a portion and save it. An external file syncronisation tool such as [Resilio Sync](https://www.resilio.com/individuals/) will take care of the filetransfer.

In order to be in sync it recommended to use Ableton Link in combination with a VPN connection. [Hamachi](https://www.vpn.net/) is recommended.

## Next steps
- Eliminate clipping when starting playback
- Recieve tempo and transport playback without Ableton Link, since Ableton Link may vary the tempo
- optimizing the UI controls
- Setup Tutorial
- Micro chat window within the plugin
- Low-Res Webcam window

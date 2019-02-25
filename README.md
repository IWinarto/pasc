# pasc

This is a custom bash script for controlling audio sinks on PulseAudio server.

Use this script for moving all audio streams to the output audio device (sink) 
of your choice. Other uses include listing all available sinks, muting the audio 
device, and adjusting the volume.

### Usage

`pasc list | mute | up [non-negative integer] | down [non-negative integer] | set <integer> | move <index>`

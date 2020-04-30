# pasc

This is a custom bash script for controlling audio sinks on PulseAudio server.

Use this script for moving all audio streams to the output audio device (sink) 
of your choice. Other uses include listing all available sinks, muting the audio 
device, adjusting the volume, restarting the audio server, and printing the volume.

### Usage

`pasc list | mute | up [integer >= 0] | down [integer >= 0] | set <integer> | move <index> | volume | restart`

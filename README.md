# CLI transcoding tool

[latest release](https://github.com/livepeer/cli-transcoder/releases/latest)

## usage

To use this tool you need to generate an Livepeer API key.

Tool accepts .mp4 and .ts file. Out also can be .mp4 or .ts.

Example usage:

`./cli-transcoder transcode --api-key API_KEY  input_file_name.mp4 output_file_name.mp4 -r 256x144 -b 400 --framerate 47 --profile baseline --gop 20s`


Switches:

`-r widtxheight` - specifies output resolution
`-b 400` - output bitrate, in KB
`--framerate 10` - output framerate
`-profile baseline` - h264 profie, one of: baselline, main, high
`--gop 10s` - GOP length


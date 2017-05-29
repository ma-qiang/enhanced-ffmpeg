# enhanced-ffmpeg
Add some handy function to ffmpeg

## SingleFrame
A simple container for streaming that can mux as many codec as possible, especially rawvideo and pcm, so that it can be easily used in pipe, network streaming and etc. 

## ZeroMQ I/O Protocol
Add ZeroMQ I/O protocol to ffmpeg. ZeroMQ is an easy of use, auto-(re)connect tcp library. Current support following mode of ZMQ:
* Pub-Sub
* Pair
This can be used to build a simple CDN or video contribution relay.

## Multiple Program Transport Stream (MPTS)
Support Multiple Program Transport Stream (MPTS) in TS format.

## Simple Playlist Input Format

## Logo Filter

## Parallel Encoding

## AWS S3 I/O Protocol

## Thumbnail at Keyframe for libx264/5

## AES-128 for HLS Output

## Add H265 codec for flv

## How to compile
* Download ffmepg-3.3.1 from [ffmpeg official website](http://ffmpeg.org/releases/ffmpeg-3.3.1.tar.bz2)
* Replace source accordingly or apply patch.
* Compile code. 
* Or use the Build.bash

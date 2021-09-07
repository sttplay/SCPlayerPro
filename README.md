# UnitySCPlayerPro

![Image text](res/img/Cover.png) 
#### An easy-to-use media player

## sttplay home
[**www.sttplay.com**](http://www.sttplay.com)

## Unity Assetstore
[**Assetstore-SCPlayerPro**](https://assetstore.unity.com/packages/slug/199154)

## Important notice
The current version is a trial version of Unity, and we have made some restrictions on performance. But the function is complete.



## Introduce
**SCPlayerPro** is an audio and video player plug-in, We have encapsulate library, namely core decoding plug-in SCCore.dll, auxiliary tool class SCUtility.dll, in terms of video playback, we did not use DX9, DX11 for direct video rendering, and use Texture2D in Unity for intuitive rendering. Taking into account the needs of more special users, users may want to obtain the original data of the video frame, we must get the data of each frame to the CPU. Although this will affect certain performance, it can better meet the needs of users. These effects can be ignored. In terms of audio playback, we also encapsulate SCAudioPlayer.dll, the same factors as the video, we can also get the original PCM audio data. Users can easily get the original data after audio and video decoding for secondary use.

## Features
- Support most audio and video files
- It is friendly to the video support of different resolutions
- Support multiple pixel formats
- Supports hardware acceleration of multiple device types
- Friendly and compatible with videos containing transparent channels
- Support 8K 30fps
- Looping playback does not lag

## Current supported platforms
- Windows (64-bit)

## how to use
After importing the package, see SCPlayerPro/Docs/SCPlayerProVideo-UserManual.pdf

Special version for improved Intel® QUICK SYNC support
=============

This version extends support on Linux based, Intel® CPU and QuickSync capable machines. New and modern BRC methods are now supported (till now Windows only). Details about the BRC methods: [Bitrate Control Methods (BRC) in Intel® Media SDK](https://software.intel.com/en-us/articles/common-bitrate-control-methods-in-intel-media-sdk) and [Intel blog, MSS2017-R3](https://software.intel.com/en-us/blogs/2017/07/11/whats-new-in-intel-media-server-studio-2017-r3)
* `ICQ` Intelligent Constant Quality
* `LA_ICQ` Intelligent Constant Quality with Look Ahead
* `QVBR` Constant Quality with Variable Bitrate algorithm

### Requirements

* Latest [libva](https://github.com/intel/libva)
* Latest [libva-utils](https://github.com/intel/libva-utils)
* Latest [media-driver](https://github.com/intel/media-driver)
* Latest [gmmlib](https://github.com/intel/gmmlib)
* Latest [MediaSDK](https://github.com/Intel-Media-SDK/MediaSDK)

FFmpeg README
=============

FFmpeg is a collection of libraries and tools to process multimedia content
such as audio, video, subtitles and related metadata.

## Libraries

* `libavcodec` provides implementation of a wider range of codecs.
* `libavformat` implements streaming protocols, container formats and basic I/O access.
* `libavutil` includes hashers, decompressors and miscellaneous utility functions.
* `libavfilter` provides a mean to alter decoded Audio and Video through chain of filters.
* `libavdevice` provides an abstraction to access capture and playback devices.
* `libswresample` implements audio mixing and resampling routines.
* `libswscale` implements color conversion and scaling routines.

## Tools

* [ffmpeg](https://ffmpeg.org/ffmpeg.html) is a command line toolbox to
  manipulate, convert and stream multimedia content.
* [ffplay](https://ffmpeg.org/ffplay.html) is a minimalistic multimedia player.
* [ffprobe](https://ffmpeg.org/ffprobe.html) is a simple analysis tool to inspect
  multimedia content.
* [ffserver](https://ffmpeg.org/ffserver.html) is a multimedia streaming server
  for live broadcasts.
* Additional small tools such as `aviocat`, `ismindex` and `qt-faststart`.

## Documentation

The offline documentation is available in the **doc/** directory.

The online documentation is available in the main [website](https://ffmpeg.org)
and in the [wiki](https://trac.ffmpeg.org).

### Examples

Coding examples are available in the **doc/examples** directory.

## License

FFmpeg codebase is mainly LGPL-licensed with optional components licensed under
GPL. Please refer to the LICENSE file for detailed information.

## Contributing

Patches should be submitted to the ffmpeg-devel mailing list using
`git format-patch` or `git send-email`. Github pull requests should be
avoided because they are not part of our review process and will be ignored.

# @siteed/expo-audio-stream

[![kandi X-Ray](https://kandi.openweaver.com/badges/xray.svg)](https://kandi.openweaver.com/typescript/siteed/expo-audio-stream)
[![Version](https://img.shields.io/npm/v/@siteed/expo-audio-stream.svg)](https://www.npmjs.com/package/@siteed/expo-audio-stream)
[![Dependency Status](https://img.shields.io/npm/dt/@siteed/expo-audio-stream.svg)](https://www.npmjs.com/package/@siteed/expo-audio-stream)
[![License](https://img.shields.io/npm/l/@siteed/expo-audio-stream.svg)](https://www.npmjs.com/package/@siteed/expo-audio-stream)

<div align="center">
  <p align="center">
    <strong>Comprehensive library designed to facilitate real-time audio processing and streaming across iOS, Android, and web platforms, with support for dual-stream recording and audio compression.</strong>
  </p>

  <div style="display: flex; justify-content: center; gap: 20px; margin: 30px 0;">
    <div>
      <h3>iOS Demo</h3>
      <img src="../../docs/ios.gif" alt="iOS Demo" width="280" />
    </div>
    <div>
      <h3>Android Demo</h3>
      <img src="../../docs/android.gif" alt="Android Demo" width="280" />
    </div>
  </div>

  <a href="https://deeeed.github.io/expo-audio-stream/playground" style="text-decoration:none;">
    <div style="display:inline-block; padding:10px 20px; background-color:#007bff; color:white; border-radius:5px; font-size:16px;">
      Try it in the Playground
    </div>
  </a>
</div>

**Give it a GitHub star 🌟, if you found this repo useful.**
[![GitHub stars](https://img.shields.io/github/stars/deeeed/expo-audio-stream.svg?style=social&label=Star&maxAge=2592000)](https://github.com/deeeed/expo-audio-stream)

## Features

- Real-time audio streaming across iOS, Android, and web.
- Dual-stream recording capabilities:
  - Simultaneous raw PCM and compressed audio recording
  - Compression formats: OPUS or AAC
  - Configurable bitrate for compressed audio
  - Optimized storage for both high-quality and compressed formats
- Intelligent interruption handling:
  - Automatic pause/resume during phone calls
  - Configurable automatic resumption
  - Detailed interruption event callbacks
- Configurable intervals for audio buffer receipt.
- Automated microphone permissions setup in managed Expo projects.
- Background audio recording on iOS.
- Audio features extraction during recording.
- Consistent WAV PCM recording format across all platforms.
- Keep device awake during recording sessions
- Rich notification system for recording status:
  - Android: Live waveform visualization in notifications
  - Android: Fully customizable notification appearance and actions
  - iOS: Media player integration

## Documentation

For detailed documentation, please refer to the [Getting Started Guide](https://deeeed.github.io/expo-audio-stream/docs/).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
<sub>Created by [Arthur Breton](https://siteed.net) • See more projects at [siteed.net](https://siteed.net)</sub>

# TwinMindTranscriber

An iOS app that:
- Records audio using AVAudioEngine
- Automatically splits recordings into 30-second segments
- Sends segments to Whisper for transcription
- Uses SwiftData to store sessions and transcriptions
- Handles audio interruptions, route changes and background recording
- Includes retry logic and fallback to local transcription
- Provides audio level monitoring

## 📦 Features
- ✅ Real-time audio segmentation
- ✅ AVAudioEngine with session handling
- ✅ Retry & fallback for transcription
- ✅ SwiftData schema: RecordingSession & TranscriptionSegment
- ✅ Offline queue and error handling
- ✅ Modular code, testable structure

## 🚀 Getting Started
1. Open in Xcode
2. Set background mode and mic permission in Info.plist
3. Connect Whisper API if implementing real transcription
4. Run on device or simulator

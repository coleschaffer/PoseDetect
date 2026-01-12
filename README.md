# PoseDetect

![Swift](https://img.shields.io/badge/Swift-5.0-orange)
![iOS](https://img.shields.io/badge/iOS-18.2+-blue)
![SwiftUI](https://img.shields.io/badge/SwiftUI-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

A privacy-first iOS app that generates skeleton pose overlays from photos using on-device human pose detection.

## Overview

PoseDetect is a mobile application that allows users to capture or select images and generates a skeletal outline visualization of detected human poses. All processing happens locally on-device, ensuring complete privacy with zero data collection or internet connectivity required.

The app leverages Apple's native frameworks to perform real-time pose detection, making it ideal for fitness tracking, motion analysis, or creative applications where privacy is paramount.

## Features

- **On-Device Processing** - All pose detection runs locally with no cloud dependencies
- **Privacy-First Design** - Zero data collection, no internet required
- **Skeleton Visualization** - Generates clear skeletal overlays on captured images
- **SwiftData Integration** - Persistent local storage for detected poses
- **Universal Support** - Works on both iPhone and iPad

## Tech Stack

| Category | Technology |
|----------|------------|
| Language | Swift 5.0 |
| UI Framework | SwiftUI |
| Data Persistence | SwiftData |
| Platform | iOS 18.2+ |
| Build System | Xcode 16.2+ |

## Getting Started

### Prerequisites

- Xcode 16.2 or later
- macOS with Xcode command line tools
- iOS device or simulator running iOS 18.2+

### Installation

```bash
# Clone the repository
git clone https://github.com/coleschaffer/PoseDetect.git

# Open in Xcode
open PoseDetect/HumanPoseDetection.xcodeproj
```

### Running

1. Select your target device (simulator or physical device)
2. Press `Cmd + R` to build and run
3. Grant camera permissions when prompted

## Project Structure

```
PoseDetect/
├── HumanPoseDetection/
│   ├── HumanPoseDetectionApp.swift    # App entry point with ModelContainer
│   ├── ContentView.swift              # Main UI with navigation
│   ├── Item.swift                     # SwiftData model
│   ├── Assets.xcassets/               # App icons and colors
│   └── Preview Content/               # SwiftUI preview assets
├── HumanPoseDetectionTests/           # Unit tests
└── HumanPoseDetectionUITests/         # UI tests
```

## Privacy

This app is designed with privacy as a core principle:
- No data leaves your device
- No analytics or tracking
- No account required
- Works completely offline

For support, contact: coleschaffer6@gmail.com

## License

MIT License

# BlackHole - Repository Overview

## What is BlackHole?

BlackHole is an **Open-Source Music Player Application** built with Flutter. It's a feature-rich music streaming and downloading app that provides users with free, ad-free access to music with high-quality streaming (320kbps AAC).

## Technology Stack

### Primary Framework
- **Flutter**: Cross-platform mobile application framework
- **Dart**: Programming language (SDK >=2.17.0 <3.0.0)
- **Version**: 1.15.2+33

### Platform Support
- ✅ Android
- ✅ iOS
- ✅ Linux
- ✅ Windows (MSIX package available)

### Key Dependencies
- **audio_service**: Background audio playback service
- **just_audio**: Audio player for Flutter
- **youtube_explode_dart**: YouTube integration for video-to-audio streaming
- **on_audio_query**: Local music file access
- **hive_flutter**: Local database storage
- **supabase**: Backend service integration
- **cached_network_image**: Efficient image loading
- **audiotagger**: ID3 tag editing for music files

## Architecture

### Main Components

```
lib/
├── APIs/              # External API integrations (Spotify, YouTube, etc.)
├── CustomWidgets/     # Reusable UI components
├── Helpers/           # Utility functions and helpers
├── Screens/           # Application screens/pages
│   ├── About/
│   ├── Common/
│   ├── Home/
│   ├── Library/
│   ├── LocalMusic/
│   ├── Login/
│   ├── Player/
│   ├── Search/
│   ├── Settings/
│   ├── Top Charts/
│   └── YouTube/
├── Services/          # Background services and audio handling
├── localization/      # Multi-language support
├── theme/             # UI themes and styling
└── main.dart          # Application entry point
```

## Core Features

### 🎵 Music Streaming & Playback
- **Best Streaming Quality**: 320kbps AAC audio streaming
- **Online & Offline Playback**: Stream or play downloaded songs
- **Background Playback**: Continue listening with the screen off
- **Queue Management**: Control your playback queue
- **Sleep Timer**: Auto-stop playback after a set time
- **Inbuilt Equalizer**: Customize your audio experience

### 🔍 Search & Discovery
- **Song, Album, Artist, and Playlist Search**
- **Trending Songs**: Discover what's popular
- **YouTube Search Support**: Find and play YouTube content as audio
- **Trending Search Results**: Get relevant search suggestions
- **Artist and Genre Radios**: Explore music by artist or genre
- **Auto Song Recommendations**: Personalized music suggestions

### 📚 Library & Organization
- **Playlists Support**: Create and manage custom playlists
- **Add Songs to Favorites**: Build your favorite songs collection
- **Import Playlists**: Import from Spotify & YouTube
- **Import/Export Playlists**: Save playlists as JSON files
- **Share Playlists**: Share your music collections
- **Listening History**: Track your recently played songs

### 🌍 Multi-Language Support
- **15+ Music Languages Supported**
- **Language-Specific Promoted Playlists**
- **Local and Global Top Spotify Songs**
- **Available Translations**: English, Spanish, Russian, French, Portuguese, and more

### 💾 Download & Offline Features
- **Download for Offline Play**: Save songs in 320kbps quality with ID3 tags
- **Tag Editing Support**: Edit song metadata
- **Local Music Integration**: Play music files stored on your device

### 🎨 Customization
- **Dark Mode**: Eye-friendly dark theme
- **Accent Color Customization**: Personalize your app's color scheme
- **Custom Gradients**: Choose from various gradient themes
- **Portrait & Landscape Mode**: Flexible orientation support

### 🔧 Additional Features
- **Lyrics Support**: View song lyrics while playing
- **Backup & Restore**: Save your app data and settings
- **Auto Update Check**: Stay updated with the latest features
- **Cache Support**: Efficient data caching
- **No Subscription Required**: 100% free to use
- **No Ads**: Completely ad-free experience

## API Integrations

The app integrates with multiple music platforms:
1. **YouTube**: Stream videos as audio, search for content
2. **Spotify**: Import playlists, access top charts
3. **Local Storage**: Play music files from device storage

## Localization

BlackHole supports multiple languages with internationalization (i18n) infrastructure:
- Translation system using Flutter's localization features
- Community translations via [Weblate](https://hosted.weblate.org/engage/blackhole/)
- Multiple README translations (Spanish, Russian, French, Portuguese)

## Build & Distribution

### Build Configuration
- **Android**: Native Android APK
- **iOS**: Native iOS build
- **Linux**: Linux desktop application
- **Windows**: MSIX package with file associations (.mp3, .m4a)

### Available Downloads
- GitHub Releases
- F-Droid (alternative app store)
- IzzyOnDroid (F-Droid repository)
- Telegram Channel for beta versions

## Development Setup

### Prerequisites
- Flutter SDK (latest version recommended)
- Dart SDK >= 2.17.0

### Quick Start
```bash
# Clone the repository
git clone https://github.com/StarsWarrior/BlackHole.git

# Get dependencies
flutter pub get

# Run the application
flutter run
```

## License

**GPL v3.0 (GNU General Public License)**

- Free and Open Source Software (FOSS)
- Copyright © 2021 Wali Ullah Shuvo
- Source code must remain open source
- Cannot be published on closed-source platforms (like PlayStore) without distributing source code
- Any modifications must retain the same license and disclose all changes

## Community

- **Telegram Channel**: [@blackholebd](https://t.me/blackholebd)
- **Telegram Group**: For support and beta testing
- **GitHub Issues**: Bug reports and feature requests
- **Weblate**: Translation contributions

## Project Status

- ✅ Actively maintained
- ✅ Continuous Integration (CI/CD) with GitHub Actions
- ✅ Community-driven development
- ✅ Regular updates and improvements

## Key Highlights

1. **100% Free & Open Source**: No hidden costs, no subscriptions
2. **No Advertisements**: Completely ad-free experience
3. **High-Quality Audio**: 320kbps streaming quality
4. **Cross-Platform**: Works on Android, iOS, Linux, and Windows
5. **Privacy-Focused**: No data collection, no tracking
6. **Feature-Rich**: Comprehensive music player with advanced features
7. **Community-Driven**: Active community contributions and translations

---

*This document provides a comprehensive overview of the BlackHole music player application repository, its features, architecture, and capabilities.*

# 🔒 Metadata Cleaner Premium Edition

<p align="center">
  <img src="metadata.png" alt="Metadata Cleaner Logo" width="200"/>
</p>

[![Android](https://img.shields.io/badge/Platform-Android-green.svg)](https://android.com)
[![API](https://img.shields.io/badge/API-24%2B-brightgreen.svg)](https://android-arsenal.com/api?level=24)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9.10-blue.svg)](https://kotlinlang.org)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

[🇹🇷 Türkçe](README-TR.md) | 🇬🇧 English

---

## 📱 Overview

**Metadata Cleaner Premium Edition** is a powerful, privacy-focused Android application that removes hidden metadata from your photos, videos, and PDF documents. Protect your privacy by removing GPS location, camera information, timestamps, and other sensitive data before sharing your files.

### ✨ Key Features

- 🖼️ **Image Metadata Removal** - Remove EXIF data from JPEG, PNG, and WebP images
- 🎥 **Video Metadata Cleaning** - Strip metadata from MP4, MKV, and AVI videos
- 📄 **PDF Metadata Removal** - Clean author, creation date, and document properties
- 🔒 **100% Offline** - No internet connection required, all processing happens locally
- ⚡ **Batch Processing** - Clean multiple files at once
- 📊 **Before/After Comparison** - See exactly what metadata was removed
- 🚀 **One-Tap Sharing** - Share cleaned files instantly
- ⚙️ **Advanced Settings** - Selective metadata removal with granular control
- 🎨 **Modern UI** - Beautiful dark theme with Material Design 3
- 🌐 **Turkish Language** - Full Turkish localization

---

## 🎯 Why Metadata Cleaner?

### The Problem

Every photo you take contains hidden information:
- 📍 **GPS Coordinates** - Exact location where the photo was taken
- 📷 **Camera Details** - Device model, lens information, camera settings
- 📅 **Timestamps** - When the photo was created and modified
- 👤 **Author Information** - User names and software details

This metadata can compromise your privacy when sharing files online.

### The Solution

Metadata Cleaner removes all this sensitive information while preserving the quality of your files. Share photos, videos, and documents with confidence knowing your privacy is protected.

---

## 🚀 Features in Detail

### 1. 📊 Metadata Comparison

View a detailed before/after comparison showing exactly what metadata was removed:

- Side-by-side comparison view
- Highlighted removed items
- Complete transparency about what's being cleaned
- Easy to understand interface

### 2. 🚀 Bulk Sharing

After cleaning your files, share them instantly:

- One-tap sharing to any app
- Multiple files at once
- Native Android sharing integration
- Fast and convenient

### 3. ⚙️ Advanced Settings

Take full control over what gets removed:

- **GPS Location** - Remove all location data
- **Camera Information** - Strip camera model and settings
- **Date/Time** - Remove timestamps
- **Author Information** - Clean author and software details
- **Auto-Delete Original** - Optionally remove original files
- **Custom Save Location** - Choose where to save cleaned files

### 4. 🎨 Beautiful Interface

Modern, intuitive design:

- Dark gradient theme
- Smooth animations
- Cyan accent color (#00D9FF)
- Material Design 3 components
- Professional splash screen
- Responsive layout

---

## 📸 Screenshots

### Main Screen
- File selection with drag & drop support
- Real-time file list with type indicators
- Progress tracking during cleaning
- Success notifications

### Metadata Viewer
- Detailed metadata display
- Organized by categories
- Easy to read format
- Tap any file to view its metadata

### Settings Panel
- Toggle individual metadata types
- Visual switches for each option
- Save preferences
- Instant apply

### Comparison View
- Before/after side-by-side
- Arrow indicators showing changes
- Red highlighting for removed items
- Complete audit trail

---

## 🛠️ Technical Details

### Built With

- **Language:** Kotlin 1.9.10
- **UI Framework:** Jetpack Compose
- **Architecture:** MVVM (Model-View-ViewModel)
- **Min SDK:** 24 (Android 7.0)
- **Target SDK:** 34 (Android 14)
- **Gradle:** 8.5

### Libraries & Dependencies

| Library | Version | Purpose |
|---------|---------|---------|
| Jetpack Compose | 2023.10.01 | Modern UI toolkit |
| ExifInterface | 1.3.6 | Image metadata handling |
| PdfBox-Android | 2.0.27.0 | PDF processing |
| Kotlin Coroutines | 1.7.3 | Asynchronous operations |
| Material 3 | 1.1.2 | Material Design components |
| Core SplashScreen | 1.0.1 | Splash screen API |

### Architecture

```
app/
├── data/
│   ├── model/          # Data classes
│   └── repository/     # Data layer
├── domain/
│   ├── cleaner/        # Metadata removal logic
│   └── reader/         # Metadata reading logic
├── ui/
│   ├── screens/        # Compose UI screens
│   └── theme/          # App theming
└── viewmodel/          # ViewModels
```

### Supported File Types

#### Images
- JPEG (.jpg, .jpeg)
- PNG (.png)
- WebP (.webp)

#### Videos
- MP4 (.mp4)
- MKV (.mkv)
- AVI (.avi)

#### Documents
- PDF (.pdf)

---

## 🔐 Privacy & Security

### Our Commitment

- ✅ **No Data Collection** - We don't collect any personal information
- ✅ **No Internet Required** - Works 100% offline
- ✅ **No Analytics** - No tracking or usage statistics
- ✅ **No Ads** - Completely ad-free experience
- ✅ **No Third-Party Services** - No external integrations
- ✅ **Local Processing** - All operations happen on your device
- ✅ **Open Source Libraries** - Using trusted, audited libraries

### Permissions

The app requires minimal permissions:

- **READ_MEDIA_IMAGES** - To read images you select
- **READ_MEDIA_VIDEO** - To read videos you select

These permissions are only used to access files YOU explicitly choose. No background access, no automatic scanning.

---

## 📦 Installation

### Requirements

- Android 7.0 (API 24) or higher
- ~20 MB storage space
- No internet connection required

### Download

Coming soon to Google Play Store!

---

## 🎓 How to Use

### Basic Usage

1. **Select Files** - Tap "Browse Files" and choose images, videos, or PDFs
2. **Review Selection** - See all selected files in the list
3. **Clean Metadata** - Tap "Clean Metadata" button
4. **View Results** - See before/after comparison
5. **Share** - Tap "Share" to send cleaned files

### Advanced Usage

1. **Open Settings** - Tap the settings icon in the top bar
2. **Customize Options** - Toggle which metadata to remove
3. **Save Preferences** - Your settings are remembered
4. **Clean Files** - Process files with your custom settings

### Tips

- 💡 Tap any file in the list to view its metadata
- 💡 Use the comparison view to verify what was removed
- 💡 Enable "Auto-Delete Original" to save storage space
- 💡 Process multiple files at once for efficiency

---

## 🏗️ Building from Source

### Prerequisites

- Android Studio Hedgehog or newer
- JDK 21
- Android SDK 34
- Gradle 8.5+

### Clone & Build

```bash
# Clone the repository
git clone https://github.com/yourusername/metadata-cleaner.git
cd metadata-cleaner

# Build debug APK
./gradlew assembleDebug

# Build release APK
./gradlew assembleRelease

# Install on connected device
./gradlew installDebug
```

### Project Structure

```
MetaData/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/algyazilim/metadatacleaner/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│   │   └── test/
│   └── build.gradle.kts
├── gradle/
├── build.gradle.kts
└── settings.gradle.kts
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Ways to Contribute

- 🐛 Report bugs
- 💡 Suggest new features
- 📝 Improve documentation
- 🌐 Add translations
- 🔧 Submit pull requests

### Development Guidelines

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Copyright © 2026 ALG Yazılım & Elektronik Inc.**

---

## 👨‍💻 Developer

**Fatih ÖNDER (CekToR)**

### Company

**ALG Yazılım & Elektronik Inc.**
- 🌐 Website: [https://algyazilim.com](https://algyazilim.com)
- 📧 Email: info@algyazilim.com
- 📍 Location: Turkey

---

## 🙏 Acknowledgments

### Open Source Libraries

Special thanks to the following open-source projects:

- [ExifInterface](https://developer.android.com/jetpack/androidx/releases/exifinterface) - Apache License 2.0
- [PdfBox-Android](https://github.com/TomRoush/PdfBox-Android) - Apache License 2.0
- [Jetpack Compose](https://developer.android.com/jetpack/compose) - Apache License 2.0
- [Kotlin](https://kotlinlang.org/) - Apache License 2.0

---

## 📞 Support

### Need Help?

- 📧 Email: info@algyazilim.com
- 🌐 Website: [https://algyazilim.com](https://algyazilim.com)
- 📖 Documentation: [Wiki](https://github.com/yourusername/metadata-cleaner/wiki)

### FAQ

**Q: Does the app require internet?**  
A: No, the app works 100% offline.

**Q: Is my data safe?**  
A: Yes, all processing happens locally on your device. We don't collect or transmit any data.

**Q: What file formats are supported?**  
A: Images (JPEG, PNG, WebP), Videos (MP4, MKV, AVI), and PDF documents.

**Q: Can I choose which metadata to remove?**  
A: Yes, use the Advanced Settings to customize what gets removed.

**Q: Does cleaning reduce file quality?**  
A: No, only metadata is removed. The actual image/video quality remains unchanged.

---

## 🗺️ Roadmap

### Upcoming Features

- [ ] Support for more image formats (HEIC, TIFF)
- [ ] Audio file metadata cleaning (MP3, FLAC)
- [ ] Batch rename functionality
- [ ] Cloud storage integration (optional)
- [ ] Scheduled automatic cleaning
- [ ] Widget support
- [ ] Dark/Light theme toggle

---

## 📊 Stats

![GitHub repo size](https://img.shields.io/github/repo-size/cektor/metadata-cleaner)
![GitHub code size](https://img.shields.io/github/languages/code-size/cektor/metadata-cleaner)
![Lines of code](https://img.shields.io/tokei/lines/github/cektor/metadata-cleaner)

---

## ⭐ Star History

If you find this project useful, please consider giving it a star!

---

**Made with ❤️ in Turkey**

**Basit • Hızlı • Güvenli**

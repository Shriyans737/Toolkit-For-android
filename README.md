ToolKit

ToolKit is a free, all-in-one multi-tool utility application built using Flutter. It brings together a wide range of everyday utilities, image tools, PDF tools, and productivity features into a single application. ToolKit is distributed directly as an APK to friends and family and is not published on the Google Play Store.

## Overview

ToolKit is a solo-developed project designed to provide a comprehensive set of tools without advertisements, sign-up requirements, or subscription fees. The application is under active development, with new tools and improvements added on a continuous basis.

## Tool Inventory

The application currently includes the following tools:

1. PDF Merger
2. PDF Splitter
3. PDF to PNG
4. PNG to PDF
5. Printer Configuration
6. EXIF Configuration Viewer
7. Image Cropper
8. WebP to PNG
9. Unit Converter
10. Calculator / Scientific Calculator
11. Image Generator (Gemini Powered)
12. Meme Generator
13. Image Generator (Pollinations Powered)
14. Homework Solver
15. Document Solver
16. Website to PDF
17. QR Code Generator
18. Image Compressor
19. Audio Converter
20. Video to Audio Converter
21. PDF to Text / Word to Text
22. EMI Calculator
23. GST Calculator
24. Bulk File Renamer

## Key Features

- No advertisements and no account or sign-up requirement
- Ability to pin up to two frequently used tools to the top of the dashboard for quick access
- Optional splash screen animation on launch, which can be enabled or disabled from the Settings page
- Dark and light theme support
- Manual update checking via a direct link to the GitHub releases page

## Technology Stack

- **Framework:** Flutter (Dart)
- **AI Backends:** Gemini API (used for the Gemini-powered image generator and Homework Solver), Pollinations API (used for the Pollinations-powered image generator)
- **Key Packages:** `video_player`, `flutter_native_splash`, `flutter_math_fork`, `ffmpeg_kit_flutter` (min-gpl variant), `shared_preferences`, `klipy_dart`
- **Development Tools:** Visual Studio Code with GitHub Copilot as the primary coding assistant, Android Studio (used solely for the Android SDK and emulator), Git and GitHub for version control

## System Requirements

- A device or emulator running Android 10 (API level 29) or later, due to scoped storage requirements used by several tools
- Sufficient storage space to accommodate the application package, which includes bundled media processing libraries

## Installation Guide

### For End Users

1. Navigate to the project's GitHub releases page with https://github.com/Shriyans737/Toolkit-For-android/releases
2. Download the latest APK file listed under the most recent release.
3. On the Android device, ensure that installation from unknown sources is permitted for the browser or file manager being used to open the APK. This setting can typically be found under Settings, then Apps, then Special App Access, then Install Unknown Apps.
4. Open the downloaded APK file and follow the on-screen prompts to complete installation.
5. Once installed, the application can be opened from the home screen or app drawer like any other application.

To check for future updates, open the application, navigate to Settings, and select the Check for Updates option. This will direct to the GitHub releases page for manual download of the latest version.

### For Developers

To set up the project locally for development purposes, the following steps should be followed.

**Prerequisites:**

- Flutter SDK installed and configured
- Android Studio installed, for access to the Android SDK and emulator
- Visual Studio Code, or an equivalent IDE with Flutter and Dart plugin support
- Git installed for version control

**Setup Steps:**

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate into the project directory:
   ```
   cd toolkit
   ```
3. Install project dependencies:
   ```
   flutter pub get
   ```
4. Connect a physical Android device with USB debugging enabled, or start an Android emulator through Android Studio.
5. Run the application in debug mode:
   ```
   flutter run
   ```

**Building a Release APK:**

To build a release APK for distribution, run the following command from the project root:
```
flutter build apk --release
```
The generated APK file will be located under `build/app/outputs/flutter-apk/`.

## Project Notes

- The application is not distributed through the Google Play Store. All distribution is handled manually through direct APK sharing and the GitHub releases page.
- An iOS port of the application is in progress, with a porting checklist maintained separately to track compatibility and platform-specific adjustments.
- Development tracking is managed through GitHub Issues, with tasks organized in checklist format and closed through commit references or the GitHub CLI.

## License

This project is a personal, non-commercial application. Licensing terms should be added here if the project is made available for wider distribution or open-source contribution.
ME.md…]()


## 🎨 Design

Dark theme by default, with a light theme option. Clean, simple, no clutter.

## 📜 Credits

Made with ❤️ by Shriyans, for friends & family. Completely free, always will be.
No ads. No account requi![Upl
<img width="1561" height="870" alt="Screenshot 2026-09-16 at 7 49 16 PM" src="https://github.com/user-attachments/assets/06da927c-ada0-4104-ae28-09c420797547" />
<img width="1553" height="874" alt="Screenshot 2026-09-16 at 7 49 30 PM" src="https://github.com/user-attachments/assets/59567117-f988-431f-9a36-beaa32c9db43" />
<img width="1552" height="869" alt="Screenshot 2026-09-16 at 7 49 37 PM" src="https://github.com/user-attachments/assets/275da1cc-4771-4812-b5b8-88cf41a848c5" />

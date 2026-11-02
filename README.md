
# Standoff2Visuals-DarkPro

Android visual customization prototype.

## Features
- Dark Pro UI
- Crosshair preview: Classic, Dot, Circle, X
- Color themes: Ice, Violet, Mint, Amber
- Brightness and contrast preview controls
- UI animation toggle
- Weapon and skin concept showcase

## Build APK with GitHub Actions

1. Upload `Standoff2Visuals_DarkPro_v0.1_source.zip` to the repository root.
2. Add `.github/workflows/build.yml`.
3. Commit and push the files.
4. Open the Actions tab.
5. Run **Build Dark Pro APK**.
6. Wait for the build to finish.
7. Download the `DarkPro-debug-apk` artifact.
8. Extract the downloaded ZIP to get `app-debug.apk`.

## Build environment
- Java 17
- Gradle 8.9
- Android Gradle Plugin 8.7.3
- Android SDK 35

This is a standalone prototype. It does not modify or inject into Standoff 2.

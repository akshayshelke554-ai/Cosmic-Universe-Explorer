# Cosmic Universe Explorer

Starter Android project for a realistic 3D Solar System viewer.

## Features
- Interactive 3D planet models with texture maps
- Planet selection, rotation, orbit-style camera controls and zoom
- English interface starter
- GitHub Actions workflow to build a debug APK

## Build from an Android phone
1. Create/sign in to GitHub.
2. Create a new repository named `Cosmic-Universe-Explorer`.
3. Upload the contents of this ZIP (not the enclosing folder) to the repository.
4. Open the repository's **Actions** tab and enable workflows if prompted.
5. Run **Build Cosmic Universe Explorer APK** using **Run workflow**.
6. When complete, open the workflow run, scroll to **Artifacts**, and download `Cosmic-Universe-Explorer-APK`.
7. Extract the artifact ZIP and install `app-debug.apk`. Android may ask you to allow installation from that browser/file manager.

## Notes
- Planet texture maps are loaded from Solar System Scope over the internet, so first launch needs internet access.
- This is a starter build, not a Play Store release. A signed release AAB, privacy policy, app icon, offline texture packaging, Marathi/English language switch and testing are still required before publishing.

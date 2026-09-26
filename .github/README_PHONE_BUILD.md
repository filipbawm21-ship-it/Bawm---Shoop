# Bawm shoop — phone-only APK build

This project includes a GitHub Actions workflow at `.github/workflows/build-apk.yml`.

After uploading the project files to a GitHub repository, GitHub Actions builds `app-debug.apk` in the cloud. No Android Studio is needed on the phone.

1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root (including `.github/workflows/build-apk.yml`).
3. If the default branch is `main`, the build starts automatically. Otherwise open Actions and run **Build Bawm shoop APK** manually.
4. Open the completed workflow run and download the **Bawm-shoop-APK** artifact.
5. Extract the artifact ZIP and install `app-debug.apk` on Android.

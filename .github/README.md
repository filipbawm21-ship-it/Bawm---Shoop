# Bawm shoop — Proper Android App Project

This is a real Android Studio project wrapping the Bawm shoop Store + Admin Panel inside a native Android WebView. It does NOT depend on opening a `content://` HTML file, so the `ERR_FILE_NOT_FOUND` problem from the browser is avoided.

## Build APK
1. Install Android Studio.
2. Open this folder: `Bawm_shoop_Android_Proper`.
3. Let Gradle sync/download the Android Gradle Plugin and dependencies.
4. Select **Build > Build App Bundle(s) / APK(s) > Build APK(s)**.
5. Install the generated APK on the phone.

## Demo admin
Username: `admin`
Password: `123456`

Note: the current Store/Admin data is browser-local (localStorage). It is not a secure cloud database and is not shared between different phones. A production multi-device admin system needs a backend/database and secure authentication.

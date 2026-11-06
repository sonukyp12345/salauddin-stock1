# Salauddin Enterprises Stock — Android Studio project

This is an Android WebView app wrapper for the supplied stock-management HTML app.

## Build APK
1. Install Android Studio (current stable) and Android SDK Platform 35.
2. Open this folder (`SalauddinStockAndroid`) in Android Studio.
3. Allow Gradle sync to complete.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Android Studio will show the generated APK location, normally `app/build/outputs/apk/debug/app-debug.apk`.

## Included features
- Dashboard: total items, total units, stock value, low-stock count
- Add/edit/delete stock items
- Stock In and Stock Out with movement history
- Low-stock view and alert indicators
- Excel-compatible CSV export
- PDF/print report from the report menu (uses the device/browser print flow)
- JSON backup and restore

## Data
Data is stored locally in this app on the device. Use Backup regularly. Clearing app data or uninstalling the app may remove locally stored records unless a backup has been saved.

## Package details
Application ID: `com.salauddin.stock`
Minimum Android: Android 6.0 (API 23)

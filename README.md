# Smart App QR Generator

A GitHub Pages QR generator that creates one QR code for iOS and Android.

## How it works

The repository contains one permanent `redirect.html`. The generator places the App Store and Google Play URLs in the QR's redirect URL as parameters.

No per-app HTML file uploads are required.

- iPhone / iPad → App Store
- Android → Google Play
- Desktop / unknown device → fallback URL or store-choice page

The generator can download QR codes as PNG or SVG.

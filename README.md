# ESIM - VoIP Calling App

A Progressive Web App (PWA) for making VoIP calls. Users register with phone number and get SIP credentials for calling.

## Features

- 📱 **PWA** - Installable on iPhone & Android
- 🔐 **OTP Verification** - Register with phone number
- 📞 **VoIP Calls** - Make calls using SIP
- 💾 **Offline Support** - Works without internet (basic UI)
- 🎨 **Modern UI** - Beautiful orange theme

## How to Use

1. Open the web app
2. Enter phone number and click "Send OTP"
3. Check OTP server for code
4. Enter OTP to login
5. Make calls!

## Deployment

Upload to any web server:
- `index.html` - Main app
- `manifest.json` - PWA config
- `sw.js` - Service worker

## API Server

Requires a Flask backend running on port 5002 with:
- `/send-otp` - Send OTP
- `/verify-otp` - Verify OTP

## Built With

- HTML5, CSS3, JavaScript
- PWA (Service Workers, Manifest)
- SIP/VoIP integration ready

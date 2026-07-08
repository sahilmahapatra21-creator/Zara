# ZARA - Your AI Companion App 💕

A beautiful, fully-featured AI companion app built with web technologies and packaged as a native Android application.

## Features

✨ **Voice-Activated AI**
- Talk to ZARA with your voice
- Hands-free mode with "Zara" wake word detection
- Natural text-to-speech responses

🤖 **Multiple AI Providers**
- Groq (Llama 3.3)
- Google Gemini 2.5 Flash

💬 **Smart Conversations**
- Emotion detection
- Context-aware responses
- Chat history

🎤 **Advanced Voice Features**
- Speech recognition
- Real-time voice input
- Customizable voice output

📱 **Mobile Native**
- Full Android app experience
- Offline-friendly
- Local storage of conversations

## Installation

### Option 1: Download Pre-built APK
1. Go to [Releases](../../releases)
2. Download the latest `zara-release.apk`
3. Install on your Android phone

### Option 2: Build from Source

**Requirements:**
- Node.js 18+
- Java 11+
- Android SDK

**Steps:**
```bash
# Clone the repo
git clone https://github.com/sahilmahapatra21-creator/Zara.git
cd Zara

# Install dependencies
npm install

# Add Android platform
npx cordova platform add android

# Build the APK
npx cordova build android --release
```

## Setup

1. **Get API Keys:**
   - **Groq**: Get free key at [console.groq.com](https://console.groq.com)
   - **Gemini**: Get free key at [makersuite.google.com](https://makersuite.google.com)

2. **Open ZARA App**
3. **Tap Settings ⚙️**
4. **Paste your API key**
5. **Start chatting!** 💕

## Usage

### Text Chat
- Type your message
- Tap send button
- ZARA responds with voice (if enabled)

### Voice Chat
1. Tap the 🎤 microphone button
2. Say your message
3. Release to send

### Hands-Free Mode
1. Toggle **Hands-free ON**
2. Say **"Zara, your message here"**
3. ZARA listens and responds automatically
4. Keep chatting hands-free!

## Permissions Required

- **Microphone**: For voice input and hands-free mode
- **Internet**: To connect to AI APIs
- **Storage**: To save conversations

## Customization

### Change Name
- Settings → Your name

### Change Language
- Settings → Language (English / हिंदी)

### Change Voice
- Settings → Voice Engine

### Change AI Provider
- Settings → AI Provider (Groq / Gemini)

## Troubleshooting

**Hands-free not working?**
- Tap ⚙️ Settings → Enable Mic
- Grant microphone permission
- Say "Zara, hello" clearly

**API error?**
- Check internet connection
- Verify API key is correct
- Tap Test button to validate key

**Voice not playing?**
- Toggle Voice OFF and ON in Settings
- Check phone volume

## Privacy

✅ **Your data is safe:**
- API keys stored locally on your device
- Conversations saved locally
- No tracking or analytics
- No data sent to servers except AI API calls

## Support

For issues or feedback:
- Open an [Issue](../../issues)
- Check [Discussions](../../discussions)

## License

MIT License - See LICENSE file for details

## Credits

Built with ❤️ using:
- Cordova (Native wrapper)
- Web Speech API (Voice)
- Groq & Google Gemini APIs
- Modern CSS & JavaScript

---

**Made with 💕 for meaningful conversations**

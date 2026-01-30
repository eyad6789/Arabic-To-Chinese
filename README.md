# Arabic to Chinese Real-Time Translator

A web application designed to help Chinese speakers understand Arabic conversations in real-time. This is particularly useful for individuals living in Arabic-speaking regions (like Iraq) who need immediate translations whispered into their ears via AirPods.

## 🚀 Features

- **Real-Time Arabic Speech Recognition**: Optimized for Iraqi Arabic (`ar-IQ`).
- **Instant Translation**: Uses MyMemory API to translate Arabic to Simplified Chinese (`zh-CN`).
- **Low Latency**: Near-instant real-time translation display (100ms debounce).
- **Text-to-Speech (TTS)**: Automatic Mandarin Chinese voice output with adjustable speed.
- **AirPods Optimized**: Easy microphone selection to route audio directly to Bluetooth earphones.
- **Background Support**: Continues to function even when the browser tab is in the background.
- **Mobile Friendly**: Includes Screen Wake Lock to prevent the phone from sleeping during use.
- **Privacy Focused**: No data is stored on servers; all processing happens in the browser.

## 🛠️ Technologies Used

- **Web Speech API**: For high-accuracy speech-to-text.
- **MyMemory API**: Free translation service (1000 requests/day).
- **Web Audio API**: To keep processing active in the background.
- **Vanilla JS/HTML/CSS**: No heavy frameworks, fast and lightweight.

## 📖 How to Use

1. **Connect Audio**: Pair your AirPods or Bluetooth headset to your device.
2. **Open App**: Access the application via a supported browser (Chrome/Edge).
3. **Select Mic**: Choose your audio device from the "Microphone" dropdown.
4. **Start**: Press the **START** button.
5. **Listen/Read**: Speak Arabic! You will see live transcription and hear Chinese translations in your ears.

## ⚙️ Settings

- **Speech Speed**: Control how fast the translation is spoken (Slow, Normal, Fast).
- **Auto-Speak**: Toggle whether you want to hear the translations automatically.
- **Clear History**: Reset the session transcription log.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

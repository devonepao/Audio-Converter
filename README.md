# Audio Converter 🎵

A free, privacy-focused audio converter that runs entirely in your browser. Convert audio files to various formats without uploading them to any server.

## ✨ Features

- **100% Browser-Based**: All conversion happens locally in your browser - your files never leave your device
- **Multiple Formats**: Convert to MP3, WAV, OGG, and web-optimized formats (WebM/Opus)
- **Web-Optimized Option**: Special format optimized for web delivery with excellent quality/size ratio
- **Responsive Design**: Fully optimized for both mobile and desktop devices
- **Drag & Drop**: Easy file upload with drag and drop support
- **Fast Conversion**: Utilizes Web Audio API for efficient processing
- **Privacy First**: No file uploads, no tracking, no data collection

## 🚀 Live Demo

Visit the live app at: `https://devonepao.github.io/Audio-Converter/`

## 📱 Supported Formats

### Input Formats
- MP3
- WAV
- OGG
- M4A
- FLAC
- AAC
- And many more audio formats supported by your browser

### Output Formats
- **MP3** - Universal compatibility (converts to WAV, requires external library for true MP3 encoding)
- **WAV** - Uncompressed quality
- **OGG** - Open-source Vorbis codec
- **WebM/Opus** - Web-optimized format (recommended for web use)

## 🛠️ Technical Details

The app uses:
- Web Audio API for audio processing
- MediaRecorder API for format conversion
- Pure HTML/CSS/JavaScript - no build process required
- Responsive CSS Grid and Flexbox for layout
- Modern ES6+ JavaScript

## 📖 How to Use

1. Open the app in your web browser
2. Click or drag & drop an audio file into the upload area
3. Select your desired output format
4. Click "Convert Audio"
5. Your converted file will automatically download

## 🌐 Deploying to GitHub Pages

This app is designed to work as a static GitHub Pages site:

1. Enable GitHub Pages in your repository settings
2. Set the source to the main/master branch
3. The site will be available at `https://[username].github.io/Audio-Converter/`

## 🔒 Privacy & Security

- **No Server Processing**: All audio processing happens in your browser
- **No Data Collection**: We don't collect, store, or transmit your files
- **Open Source**: Full source code is available for review
- **Offline Capable**: Works without an internet connection after initial load

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

This project is open source and available for free use.

## 🔗 Credits

Powered by [solvepao research](https://solvepao.com)

## 🐛 Known Limitations

- True MP3 encoding requires additional libraries (currently outputs WAV when MP3 is selected)
- OGG and WebM support depends on browser capabilities
- Large files may take longer to process
- Some mobile browsers may have limited codec support

## 💡 Browser Compatibility

Works best on modern browsers:
- Chrome/Edge 80+
- Firefox 75+
- Safari 13+
- Mobile browsers with Web Audio API support

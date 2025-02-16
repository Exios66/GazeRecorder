# GazeRecorder - Advanced Screen Recording Application

A modern, feature-rich screen recording application built with HTML5 and JavaScript, utilizing the Apowersoft Screen Recorder API.

## Features

- 🎥 High-quality screen recording
- 🎙️ Multiple audio input options (Microphone/System Audio)
- 🌓 Dark/Light theme support
- 📊 Adjustable video quality (HD/SD)
- ⏱️ Key moment marking during recording
- 🖼️ Live preview window
- 💾 Easy download functionality
- 📱 Responsive design

## Requirements

- Modern web browser with screen capture API support
- Permissions for screen recording and audio capture
- Internet connection (for Apowersoft API)

## Setup

1. Clone the repository:

```bash
git clone https://github.com/yourusername/GazeRecorder.git
cd GazeRecorder
```

2. Open `index.html` in a web browser or serve it using a local development server.

## Usage

1. **Starting a Recording**:
   - Select your desired video quality (HD/SD)
   - Choose your audio input source
   - Click "Start Recording"
   - Select the screen/window you want to record

2. **During Recording**:
   - Use the floating preview window to monitor your recording
   - Click "Mark Key Moment" to mark important timestamps
   - Click "Stop Recording" when finished

3. **After Recording**:
   - Preview your recording in the video player
   - Download the recording using the download button
   - Recording is saved in WebM format

## Technical Details

- Built using vanilla JavaScript
- Uses MediaRecorder API for screen capture
- Implements the Apowersoft Screen Recorder API
- Recordings are stored in WebM format
- Supports both dark and light themes using CSS variables

## Known Limitations

- System audio recording may not be available in all browsers
- WebM format may need conversion for some media players
- Screen recording requires HTTPS in production environments

## Browser Compatibility

- Chrome (recommended) ✅
- Firefox ✅
- Edge ✅
- Safari (limited support) ⚠️

## License

MIT License - Feel free to use and modify as needed.

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

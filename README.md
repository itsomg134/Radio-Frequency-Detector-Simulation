# Radio-Frequency-Detector-Simulation

A web-based simulation of a radio frequency detector with interactive controls and visual signal representation. This educational tool demonstrates how RF detection works across different frequency bands.

![RF Detector Screenshot](https://img.shields.io/badge/Status-Functional-success) ![GitHub](https://img.shields.io/badge/License-MIT-blue) ![Browser](https://img.shields.io/badge/Browser-Compatible-green)

## ✨ Features

- **Real-time Frequency Scanning**: Simulates scanning across multiple frequency bands
- **Interactive Controls**: Start/stop scanning, adjust sensitivity, and switch between bands
- **Multiple Frequency Bands**:
  - AM/FM Radio
  - Aviation & Marine
  - Weather Radio
  - Police/Fire Communications
  - WiFi 2.4GHz
  - Satellite Communications
- **Visual Signal Representation**:
  - Dynamic waveform visualization
  - Signal strength indicators
  - Detected signals list with strength bars
- **Responsive Design**: Works on desktop and mobile devices
- **Educational Focus**: Learn about frequency allocations and RF detection principles

##  Demo image

<img width="1880" height="1889" alt="image" src="https://github.com/user-attachments/assets/a3894c2f-e896-470a-97f0-baa5eedd9669" />

## 🛠️ Installation

### Option 1: Direct Download
1. Download the `index.html` file
2. Open it directly in any modern web browser

### Option 2: Local Server (Recommended)
```bash
# Clone the repository
git clone https://github.com/yourusername/rf-detector.git

# Navigate to the directory
cd rf-detector

# Serve with a local HTTP server
python3 -m http.server 8000
# or
npx http-server
```

Then open `http://localhost:8000` in your browser.

## 📖 How to Use

### Basic Controls:
1. **Scan Button**: Starts scanning through frequencies
2. **Pause Button**: Stops scanning at current frequency
3. **Reset Button**: Returns to default FM radio band
4. **Frequency Range Slider**: Select between different frequency bands
5. **Sensitivity Slider**: Adjust detection sensitivity (affects signal strength readings)

### Reading the Display:
- **Current Frequency**: Shows the currently scanned frequency
- **Signal Type**: Identifies the type of signal (radio station, aviation, etc.)
- **Signal Strength**: Percentage indicator of signal strength
- **Waveform**: Visual representation of the detected signal
- **Detected Signals List**: Shows all signals in the current band with their strengths

## 🔧 Technical Details

### Implementation:
- Pure HTML, CSS, and JavaScript (no external dependencies)
- SVG-based waveform generation
- Responsive CSS Grid and Flexbox layout
- Font Awesome icons for UI elements

### Frequency Bands Simulated:

| Band | Range | Common Uses |
|------|-------|-------------|
| AM Radio | 530-1710 kHz | News, talk, sports radio |
| FM Radio | 88-108 MHz | Music, entertainment |
| Aviation | 108-137 MHz | Air traffic control |
| Marine | 156-162 MHz | Ship communication |
| Weather | 162-169 MHz | NOAA weather radio |
| Police/Fire | 450-470 MHz | Emergency services |
| WiFi 2.4G | 2.4-2.5 GHz | Wireless networks |
| Satellite | 3-30 GHz | GPS, satellite comms |

## 📝 Educational Note

⚠️ **Important**: This is a **simulation** for educational purposes only. Actual RF detection requires specialized hardware like:

- Software Defined Radios (SDR)
- RF spectrum analyzers
- Directional antennas
- Proper licensing for transmission

This tool helps understand:
- How frequency bands are allocated
- What types of signals exist in different bands
- How RF detectors visualize signals
- Basic principles of radio frequency communication

## 🖥️ Browser Compatibility

Tested and working on:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Areas for improvement:
- Add more frequency bands
- Implement realistic signal propagation effects
- Add signal modulation types (AM, FM, digital)
- Create recording/playback functionality
- Add export capability for detected signals

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Frequency allocation data based on FCC/ITU standards
- Inspired by real RF detection equipment interfaces
- Icons by [Font Awesome](https://fontawesome.com/)
- Color scheme inspired by professional RF equipment

## 📧 Contact
Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app

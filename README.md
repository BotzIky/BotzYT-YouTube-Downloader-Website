# YouTube Downloader

A modern, responsive YouTube downloader web application that allows users to download YouTube videos and audio in multiple qualities using the BotzApi.

![YouTube Downloader](https://cdn.botzaku.eu.org/1dgrg_UmOtvHsMwCfoK0eYgdulOD-pa6G)

---

## Features

- 🎵 **Multiple Format Support**: Download audio (MP3) or video in various qualities (144p, 240p, 360p, 480p, 720p, 1080p)
- 🎨 **Modern UI/UX**: Clean, dark-themed interface with smooth animations
- 📱 **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- ⚡ **Fast Processing**: Quick video information retrieval and download via BotzApi
- 🔄 **Dynamic Quality Selection**: Switch between different qualities without re-entering the URL
- 🖼️ **Video Preview**: Display thumbnail and metadata before downloading
- 🌐 **SEO Optimized**: Includes meta tags for better search engine visibility

---

## 🚀 Demo

Visit the live demo: [YouTube Downloader](https://ytdl.botzaku.eu.org)

---

## 📸 Screenshots
![Screenshot](https://cdn.botzaku.eu.org/1OSC63Hk6amHc3DBFjg0aBxWZKarqbVXL)

---

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with animations and responsive design
- **JavaScript (ES6+)**: Async/await for API calls and dynamic UI updates
- **Bootstrap Icons**: Icon library for UI elements
- **SweetAlert2**: Beautiful, responsive alert dialogs
- **BotzApi**: YouTube download API backend

---

## Installation

1. Clone this repository:
```bash
git clone https://github.com/BotzIky/youtube-downloader.git
cd youtube-downloader
```

2. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index. html
```

Or simply drag and drop the `index.html` file into your browser.

---

## Usage

1. **Paste YouTube URL**: Copy a YouTube video URL and paste it into the input field
2.  **Select Format**: Choose your desired format from the dropdown menu:
   - MP3 (Audio only)
   - 144p, 240p, 360p, 480p, 720p, 1080p (Video)
3. **Fetch Video**: Click the "Download" button to retrieve video information
4. **Change Quality**: Click on any quality badge to switch formats
5. **Download**: Click the "Download" button to open the download link in a new tab

---

## File Structure

```
youtube-downloader/
├── index.html          # Main application file (standalone)
└── README.md          # Documentation (this file)
```

---

## API Integration

This application uses the BotzApi YouTube download endpoint:

```
https://host.optikl. ink/download/youtube?url={VIDEO_URL}&format={FORMAT}
```

**Parameters:**
- `url`: YouTube video URL (URL-encoded)
- `format`: Desired format (mp3, 144, 240, 360, 480, 720, 1080)

**Response Structure:**
```json
{
  "status": true,
  "code": 200,
  "result": {
    "title": "Video Title",
    "thumbnail": "https://.. .",
    "duration": 180,
    "type": "video",
    "quality": "720p",
    "format": "720",
    "download": "https://..."
  }
}
```

---

## Browser Compatibility

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Opera (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile, Samsung Internet)

---

## Features Breakdown

### Navigation
- Fixed navigation bar with logo and links
- Hamburger menu for mobile devices
- Smooth menu transitions

### Video Information Display
- Thumbnail preview
- Video title
- Duration (formatted as hours, minutes, seconds)
- Video type indicator
- Quality badges for easy format switching

### Download Functionality
- Direct download button
- "Open Source" link to view/download from API directly
- Reset button to start a new search

### Loading States
- Full-screen loading overlay with spinner
- Informative loading messages
- Disabled buttons during processing

### Notifications
- Toast notifications for user feedback
- Success, error, and warning alerts
- Auto-dismiss timers

---

## Customization

### Colors
The primary color scheme uses a dark theme with green accents:
- Background: `#000` (Black)
- Primary text: `#f1fdf1` (Light green)
- Accent color: `#98ff98` (Mint green)
- Hover color: `#7ae87a` (Bright green)

### Modify Colors
Edit the CSS variables in the `<style>` section of `index.html`:

```css
body { background: #000; color: #f1fdf1; }
.btn { background: #98ff98; color: #000; }
```

---

## Legal Notice

This tool is provided for **personal use** and **convenience** only. Users must:

- ✅ Respect copyright laws and YouTube's Terms of Service
- ✅ Only download content they have rights to use
- ✅ Use the tool responsibly and ethically
- ❌ Not use for commercial redistribution without permission

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 🐛 Bug Reports

If you find any bugs, please create an issue on GitHub with:
- Description of the bug
- Steps to reproduce
- Expected behavior
- Screenshots (if applicable)
- Browser and OS information

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 

---

## 👨‍💻 Author

**BotzAku (Riski Yanda)**
- Website: [https://botzaku.eu.org](https://botzaku.eu.org)
- Instagram: [@botzaku](https://instagram.com/botzaku)
- TikTok: [@botzaku](https://tiktok.com/@botzaku)
- Twitter: [@botz_aku](https://twitter.com/botz_aku)
- Telegram: [BotzAku](https://t.me/BotzAku)
- WhatsApp: [Channel](https://whatsapp.com/channel/0029VbBjxQl8qIzmg51J5W3x)
- Discord: [Server](https://discord.gg/Ehr7DrsU)

---

## 🙏 Acknowledgments

- [BotzApi](https://host.optikl.ink) for providing the TikTok download API
- [Bootstrap Icons](https://icons.getbootstrap.com/) for beautiful icons
- [SweetAlert2](https://sweetalert2.github.io/) for elegant alerts
- All contributors and users of this project

---

## ❗ Important
For anyone who wants to use my repositories Web [Instagram Downloader](https://github.com/BotzIky/BotzIG-Instagram-Downloader-Website), [TikTok Downloader](https://github.com/BotzIky/TikBotz-TikTok-Downloader-Website), and [YouTube Downloader](https://github.com/BotzIky/BotzYT-YouTube-Downloader-Website), please remove the last four <script> tags at the bottom of index.html if you want to disable the ads.
![Important](https://cdn.botzaku.eu.org/1aRAMFfMXrnQ9vnNhkRtaJvO8utVJR56v)

---

## ⭐ Star History

If you find this project useful, please consider giving it a star on GitHub! 

---

Made with ❤️ by [BotzAku](https://botzaku.eu.org)

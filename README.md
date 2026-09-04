# 🎵 Music Player - Download & Play

A fully functional music player with download capabilities, local playback, and progress tracking. Built with pure HTML, CSS, and JavaScript.

## Features

### 🎧 Audio Playback
- Native HTML5 audio player with controls
- Play/Pause buttons for each track
- Real-time progress bar with visual feedback
- Current time and duration display
- Support for multiple audio formats

### ⬇️ Download Functionality
- Download any track directly to your device
- One-click download button
- Downloads save as MP3 files with track names
- No server-side processing needed

### 🎨 Modern UI/UX
- Responsive grid layout (mobile-friendly)
- Beautiful gradient background
- Glassmorphism card design
- Smooth animations and transitions
- Spotify-inspired green theme
- Album artwork with smooth fade-in

### 📚 Dual Album Collections
- **Royalty-Free Collection Vol. 1** - 6 curated tracks
- **Royalty-Free Collection Vol. 2** - 6 curated tracks
- Independent players for each album
- Track metadata (name, artist, duration)
- Easy track switching via dropdown

### 🎛️ Track Selection
- Dropdown menu for track selection
- Dynamic updates when switching tracks
- Track information updates automatically
- Clean, intuitive interface

## How to Use

### Playing Music
1. Select an album (Vol. 1 or Vol. 2)
2. Choose a track from the dropdown menu
3. Click the **▶ Play** button or use native controls
4. Use the progress bar to seek through the track
5. Click **⏸ Pause** to stop playback

### Downloading Tracks
1. Select the track you want to download
2. Click the **⬇ Download** button
3. The MP3 file will download to your device
4. Save it wherever you prefer

### Features in Action
- **Progress Bar**: Visualizes playback progress, clickable to seek
- **Time Display**: Shows current time and total duration
- **Native Controls**: Full HTML5 audio controls for advanced playback
- **Track Metadata**: Displays track name and artist information

## Customization

### Adding Your Own Tracks

Replace the audio URLs in the HTML:

```html
<option value="YOUR_MP3_URL" data-name="Track Name" data-artist="Artist Name" data-duration="3:40">Track Name</option>
```

### Changing Album Information

Update the album names and metadata:

```html
<h2>Your Album Title</h2>
<p class="artist">Artist Name</p>
<p class="album">🎼 Year - Label</p>
```

### Album Artwork

Replace the image URLs:

```html
<img class="album-art" src="YOUR_IMAGE_URL" alt="Album Name">
```

## File Structure

```
frank-ocean-player/
├── index.html          # Main player application
├── README.md           # This file
└── .gitignore          # Git configuration
```

## Browser Compatibility

- ✅ Chrome/Chromium (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Audio Format Support

The player supports all formats that HTML5 audio supports:
- MP3 (.mp3)
- WAV (.wav)
- OGG (.ogg)
- M4A (.m4a)
- FLAC (.flac)

## Responsive Design

- **Desktop**: Full 2-column layout with large album cards
- **Tablet**: Responsive grid adjusts to screen size
- **Mobile**: Single column layout optimized for touch

## Technical Details

### No Dependencies
- Pure vanilla JavaScript (no frameworks required)
- CSS3 for styling and animations
- HTML5 audio API for playback

### Performance
- Lightweight and fast loading
- Efficient DOM manipulation
- Smooth 60fps animations

### Security
- Client-side only processing
- No data sent to servers
- Safe local file downloads
- CORS-compliant audio hosting

## Tips & Tricks

1. **Keyboard Controls**: Use spacebar to play/pause (if audio element is focused)
2. **Seeking**: Click anywhere on the progress bar to jump to that position
3. **Volume**: Use the native audio controls to adjust volume
4. **Batch Downloads**: Download multiple tracks by selecting and downloading each one
5. **Mobile**: Tap the track name to select from dropdown on mobile devices

## Troubleshooting

### Audio won't play
- Check your internet connection (audio files need to be downloaded)
- Ensure the audio URL is correct
- Try a different browser
- Check browser console for CORS errors

### Download isn't working
- Try a different browser
- Check if pop-ups are blocked
- Ensure you have storage space available

### Progress bar not updating
- Refresh the page
- Check if the audio file is loading properly
- Try a different audio file

## License

MIT License - Feel free to use, modify, and distribute this project freely.

## Credits

- Royalty-free audio from [SoundHelix](https://www.soundhelix.com)
- Album artwork from [Unsplash](https://unsplash.com)
- Built with ❤️ for music lovers

## Future Enhancements

Potential features for future versions:
- 🎚️ Equalizer controls
- 🔁 Repeat/Shuffle functionality
- 📱 Progressive Web App (PWA) support
- 💾 Local storage of favorites
- 🎼 Playlist creation
- 🔊 Volume normalization
- 📊 Audio visualization
- 🌙 Dark/Light theme toggle
- 🎤 Lyrics display
- 🌍 Multi-language support

## Support

For issues or suggestions, please check the repository's issues section or contact the maintainer.

---

**Made with 🎵 and ❤️ for audio enthusiasts**

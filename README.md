# 🎵 Frank Ocean Player

A beautiful, dual-album music player for Frank Ocean's **Channel Orange** (2012) and **Blonde** (2016).

## Features

✨ **Modern Design**
- Responsive grid layout with glassmorphism effects
- Smooth animations and hover effects
- Dark theme optimized for music listening
- Gradient background

🎮 **Controls**
- Play/Pause buttons for each album
- Stop functionality to reset playback
- Native HTML5 audio controls
- Track selection dropdown

💿 **Two Albums**
- **Channel Orange** - 6 tracks including "Thinkin Bout You", "Pink + White", "Novacane"
- **Blonde** - 6 tracks including "Nikes", "Ivy", "Self Control", "Nights"

🔄 **Independent Players**
- Each album has its own independent player
- Switch between albums without stopping the other
- Separate volume and playback controls

## Usage

1. Open `index.html` in your browser
2. Select a track from either album
3. Click Play or use the native audio controls
4. Use the Play/Pause and Stop buttons for quick control

## Customization

To use your own audio files:

1. Replace the URLs in the `value` attributes of the `<option>` tags
2. Update the `data-album` attributes with your own album artwork URLs
3. Modify the track names as needed

### Example:
```html
<option value="YOUR_MP3_URL" data-album="YOUR_IMAGE_URL" data-artist="Artist Name">Track Name</option>
```

## Browser Support

- Chrome/Chromium
- Firefox
- Safari
- Edge
- Opera

## Notes

- Audio files should be in MP3 format or other web-compatible formats
- Album artwork should be square images (1:1 aspect ratio)
- Uses placeholder audio from SoundHelix for demo purposes
- Uses Unsplash images for album artwork

## License

MIT License - Feel free to modify and distribute

---

**Made with ❤️ for Frank Ocean fans**
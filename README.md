# The Experimentalist's Case for Change

A professional, responsive presentation built with Reveal.js for Sawyer Business School, Suffolk University.

## Features

- **Fully Responsive**: Optimized for all screen sizes from mobile to desktop
- **Professional Design**: Clean, scholarly aesthetic with thoughtful typography
- **Accessible**: Proper semantic HTML and readable text sizing
- **GitHub Pages Ready**: Configured for easy deployment

## Viewing Locally

Simply open `index.html` in your web browser, or use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Deploying to GitHub Pages

1. Push this repository to GitHub
2. Go to your repository settings
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select the branch (usually `main` or `master`)
5. Click "Save"
6. Your presentation will be available at `https://[your-username].github.io/power_of_experimentation/`

## Navigation

- **Arrow Keys**: Navigate between slides
- **Space/Enter**: Next slide
- **ESC**: Overview mode
- **Touch Gestures**: Swipe on mobile devices

## Browser Support

Works best in modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

The presentation uses CSS custom properties (variables) defined in the `:root` selector for easy color customization. Modify these values to change the color scheme:

- `--scholarly-navy`: Primary dark blue
- `--teal`: Accent teal color
- `--amber`: Accent amber/orange color
- `--surface`: Light background color

## License

This presentation is for educational use at Sawyer Business School, Suffolk University.


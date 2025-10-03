# EllyFeelGood — AI Assistant Deck

A clean, single-file HTML presentation for the EllyFeelGood AI Assistant pitch deck. Built for easy deployment on Netlify or any static hosting platform.

## Features

- **Single-file deployment**: Everything in one HTML file
- **Responsive design**: Works on desktop and mobile
- **Keyboard navigation**: Use arrow keys to navigate slides
- **Print/Export**: Built-in PDF export functionality
- **Professional styling**: Matches maru-briefing-forms design system
- **Accessibility**: WCAG AA compliant with proper alt text and contrast

## Assets

The presentation includes the following assets:

- `assets/how-the-experience-works.svg` - Experience flow diagram
- `assets/current-whatsapp-experience.png` - WhatsApp conversation screenshot
- `assets/01-solution-global-map.svg` - AI Assistant solution overview
- `assets/new_maru_logo_neutral-960.png` - Maru Online logo

## Deployment

### Netlify (Recommended)

1. Push this repository to GitHub
2. Connect your GitHub repository to Netlify
3. Set build command to: `echo "No build required"`
4. Set publish directory to: `/` (root)
5. Deploy!

### GitHub Pages

1. Push to GitHub
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" → main
4. Save

### Manual Deployment

Simply upload the `index.html` file and `assets/` folder to any web server.

## Navigation

- **Arrow Keys**: Navigate between slides
- **Home**: Go to first slide
- **End**: Go to last slide
- **Toggle Mode**: Switch between slides and reading mode
- **Export PDF**: Print/export the presentation

## Customization

The presentation uses CSS custom properties for easy theming:

```css
:root {
  --bg: #f5f5f5; /* Background color */
  --panel: #ffffff; /* Card background */
  --text: #333333; /* Text color */
  --brand: #007bff; /* Brand color */
  --maxw: 1200px; /* Max container width */
}
```

## License

© Maru Online — AI Automation

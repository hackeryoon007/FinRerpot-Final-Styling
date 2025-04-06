# FinReport

A sleek, responsive financial analysis report dashboard with light/dark mode toggle functionality.

![FinReport Dashboard](https://raw.githubusercontent.com/username/finreport/main/screenshot.png)

## Features

- **Dual Theme Support**: Seamlessly switch between dark and light modes with user preference persistence
- **Responsive Design**: Optimized for both desktop and mobile viewing experiences
- **Financial Analysis Framework**: Structured display of market factors, risk assessment, and trend analysis
- **Multilingual Support**: Displays original news content with English translations
- **Interactive Elements**: Clean UI with toggle controls and visual indicators

## Technology Stack

- Pure HTML5, CSS3, and JavaScript (No external dependencies)
- CSS Custom Properties (Variables) for theming
- Local Storage API for persisting user preferences
- SVG for custom graphics (compass icon)
- Responsive design with media queries

## Usage

Simply clone the repository and open `index.html` in any modern web browser:

```bash
git clone https://github.com/username/finreport.git
cd finreport
open index.html  # or use your browser to open the file
```

## Customization

### Modifying Color Schemes

The application uses CSS variables for easy theming. To customize colors, modify the variables in the `:root` and `.light-mode` selectors:

```css
:root {
    /* Dark Mode Variables (Default) */
    --bg-primary: #1e1e1e;
    --bg-secondary: #2c2c2c;
    /* Additional variables... */
}

/* Light Mode Variables */
.light-mode {
    --bg-primary: #ffffff;
    --bg-secondary: #f4f4f4;
    /* Additional variables... */
}
```

### Adding New Sections

To add new sections to the report:

1. Create a new section header:
```html
<h2 class="section-header">Your Section Title</h2>
```

2. Add content using existing styles like:
```html
<div class="your-section-class">
    <p>Your content here with <span class="positive">positive</span> or 
    <span class="negative">negative</span> highlights.</p>
</div>
```

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

MIT License

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Acknowledgments

- Compass icon inspired by traditional navigation tools
- Financial reporting structure based on standard investment analysis frameworks

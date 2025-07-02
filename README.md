# Armed Detective Agency Website

A beautiful, responsive website inspired by the Armed Detective Agency from Bungou Stray Dogs anime/manga series.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Navigation**: Smooth scrolling navigation with mobile hamburger menu
- **Modern Aesthetics**: Color palette and design inspired by the Bungou Stray Dogs aesthetic
- **Professional Layout**: Clean, organized sections showcasing agency information
- **Contact Form**: Functional contact form with validation
- **Smooth Animations**: Fade-in animations and hover effects throughout the site

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Information about the agency's mission and capabilities
3. **Services**: Four main service offerings with detailed descriptions
4. **Team Members**: Profiles of key agency members
5. **Contact**: Contact information and inquiry form
6. **Footer**: Additional links and information

## Color Palette

The website uses a warm, professional color scheme inspired by the reddish-brown brick building:

- Primary: `#8B4513` (Reddish-brown brick color)
- Secondary: `#D2691E` (Warm orange-brown)
- Accent: `#CD853F` (Sandy brown)
- Dark: `#2F1B14` (Dark brown)
- Light: `#F5F5DC` (Beige)

## Typography

- **Primary Font**: Crimson Text (serif) - for headings and titles
- **Secondary Font**: Source Sans Pro (sans-serif) - for body text

## File Structure

```
detective-agency-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## Deployment to Netlify

### Method 1: Drag and Drop
1. Zip all the files in this directory
2. Go to [Netlify](https://netlify.com)
3. Drag and drop the zip file to deploy

### Method 2: Git Repository
1. Create a new repository on GitHub
2. Upload these files to the repository
3. Connect the repository to Netlify for automatic deployments

### Method 3: Netlify CLI
1. Install Netlify CLI: `npm install -g netlify-cli`
2. Run `netlify deploy` in this directory
3. Follow the prompts to deploy

## Local Development

To run the website locally:

1. Navigate to the project directory
2. Start a local server:
   ```bash
   python3 -m http.server 8000
   ```
   or
   ```bash
   npx serve .
   ```
3. Open `http://localhost:8000` in your browser

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features Implemented

### Interactive Elements
- Mobile-responsive navigation menu
- Smooth scrolling between sections
- Form validation and submission handling
- Hover effects on cards and buttons
- Scroll-to-top button
- Parallax effects
- Fade-in animations on scroll

### Responsive Design
- Mobile-first approach
- Flexible grid layouts
- Responsive typography
- Touch-friendly interface
- Optimized for various screen sizes

### Performance Optimizations
- Efficient CSS animations
- Debounced scroll handlers
- Optimized image loading
- Minimal JavaScript footprint

## Customization

To customize the website:

1. **Colors**: Modify the CSS custom properties in `:root` selector
2. **Content**: Update the HTML content in `index.html`
3. **Styling**: Adjust styles in `styles.css`
4. **Functionality**: Modify interactions in `script.js`

## Credits

- Inspired by Bungou Stray Dogs by Kafka Asagiri
- Design and development by Manus AI
- Fonts from Google Fonts
- Icons using Unicode emojis

## License

This project is for educational and demonstration purposes. Bungou Stray Dogs is the property of its respective creators and publishers.


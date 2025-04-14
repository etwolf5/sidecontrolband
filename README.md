# Side Control Band Website

A minimalistic website for Side Control, an indie rock band.

## Features

- Responsive design for desktop and mobile devices
- Dark theme with lavender accent color
- Smooth scrolling navigation
- Section for band photos
- About section
- Links to social media and music platforms

## Getting Started

### Local Development

1. Clone this repository:
```
git clone https://github.com/yourusername/sidecontrolband.git
cd sidecontrolband
```

2. Open the website locally:
   - Open `index.html` in your browser
   - Alternatively, you can use a local development server like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension for VS Code

### Adding Your Content

#### Photos
Replace the photo placeholders in the `photos` section with your actual band photos:

1. Add your image files to the project (consider creating an `images` folder)
2. Update the HTML in `index.html` to point to your images

```html
<div class="photo-grid">
    <div class="photo-item">
        <img src="images/your-photo-1.jpg" alt="Side Control Band">
    </div>
    <!-- Add more photos as needed -->
</div>
```

#### About Content
Update the "About Us" section in `index.html` with your band's description.

#### Social Links
Update the links in the "Listen & Follow" section with your actual social media and music platform URLs.

## Customization

### Colors
You can customize the color scheme by editing the CSS variables in `styles.css`:

```css
:root {
    --dark-bg: #0A0A0A;               /* Matte black background */
    --dark-secondary: #111111;        /* Soft charcoal for sections */
    --light-text: #F5F5F5;            /* Soft white for high contrast */
    --primary: #C77DFF;               /* Neon lavender for primary accent */
    --accent: #FF6A3D;                /* Burnt orange for hover/CTA */
    --muted: #999999;                 /* For subtle elements, dividers */
}
```

### Fonts
The website uses Google Fonts, specifically Montserrat and Raleway. You can change these by:

1. Updating the Google Fonts link in the `<head>` of `index.html`
2. Updating the font-family properties in `styles.css`

## Deployment

You can deploy this website to various platforms:

- GitHub Pages
- Netlify
- Vercel
- Any static website hosting service

## License

This project is licensed under the MIT License - see the LICENSE file for details.

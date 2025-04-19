# Modern Website Template

This is a modern, responsive website template based on the structure of schottland-tuebingen.de. The template includes a clean, professional design with smooth animations and mobile responsiveness.

## Features

- Responsive design that works on all devices
- Modern and clean UI
- Smooth scrolling navigation
- Mobile-friendly navigation menu
- Contact form
- Animated sections on scroll
- Social media integration
- CSS Grid and Flexbox layouts

## File Structure

```
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Main stylesheet
├── js/
│   └── main.js         # JavaScript functionality
└── images/             # Image directory (create this folder)
    ├── hero-bg.jpg     # Hero section background
    └── about-placeholder.jpg  # About section image
```

## Setup Instructions

1. Create an `images` folder in the root directory
2. Add your images:
   - Add a hero background image as `hero-bg.jpg`
   - Add an about section image as `about-placeholder.jpg`
3. Customize the content in `index.html`:
   - Update the title
   - Modify the navigation links
   - Add your own content to sections
   - Update contact information
4. Customize the styling in `css/styles.css`:
   - Modify the color scheme in the `:root` variables
   - Adjust spacing and layouts as needed
5. Customize the JavaScript in `js/main.js` if needed:
   - Modify form submission handling
   - Adjust animation triggers
   - Add additional interactive features

## Customization

### Colors
The color scheme can be modified in the `:root` section of `styles.css`:
```css
:root {
    --primary-color: #1a1a1a;
    --secondary-color: #4a4a4a;
    --accent-color: #007bff;
    --text-color: #333;
    --light-bg: #f8f9fa;
    --white: #ffffff;
}
```

### Images
Replace the placeholder images in the `images` folder with your own:
- `hero-bg.jpg`: A high-quality background image for the hero section
- `about-placeholder.jpg`: An image for the about section

### Content
Update the content in `index.html` to match your needs:
- Update the navigation menu items
- Modify section headings and text
- Add your own services
- Update contact information
- Modify footer content

## Browser Support

The template is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Dependencies

- Font Awesome 6.0.0 (included via CDN)
- No other external dependencies required

## License

This template is free to use for both personal and commercial projects.

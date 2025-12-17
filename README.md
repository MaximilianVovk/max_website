# max_website
Personal website with orange and black color scheme

## Overview
This is a modern, responsive personal portfolio website featuring sections for:
- Experiences
- Education
- Publications
- Awards

## Features
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Orange & Black Theme**: Professional color palette with dark mode aesthetics
- **Smooth Animations**: Card hover effects and scroll animations
- **Easy Navigation**: Sticky navigation bar with smooth scrolling
- **Modular Structure**: Simple to add new sections

## Getting Started

### Viewing the Website
Simply open `index.html` in your web browser to view the website locally.

### Deploying to GitHub Pages
1. Go to your repository settings on GitHub
2. Navigate to "Pages" section
3. Under "Source", select the branch you want to deploy (e.g., `main` or `copilot/create-personal-website`)
4. Click "Save"
5. Your website will be available at `https://maximilianvovk.github.io/max_website/`

## Customization

### Adding Content
Edit `index.html` to add your personal information:
1. Update the hero section with your name and tagline
2. Add your experiences, education, publications, and awards by duplicating the card structure
3. Replace placeholder text with your actual content

### Adding a New Section
To add a new section (e.g., "Projects" or "Skills"):

1. **Add navigation link** in the navbar:
```html
<li><a href="#newsection">New Section</a></li>
```

2. **Add the section** after existing sections:
```html
<section id="newsection" class="section">
    <div class="container">
        <h2 class="section-title">New Section</h2>
        <div class="section-content">
            <div class="card">
                <h3 class="card-title">Item Title</h3>
                <p class="card-meta">Metadata</p>
                <p class="card-description">Description</p>
            </div>
            <!-- Add more cards as needed -->
        </div>
    </div>
</section>
```

3. Alternate the section class between `section` and `section section-alt` for visual variety.

### Customizing Colors
The color palette is defined in CSS variables at the top of `styles.css`:
```css
:root {
    --primary-color: #FF8C00;   /* Dark Orange */
    --secondary-color: #FFA500;  /* Orange */
    --accent-color: #FFB347;     /* Light Orange */
    --dark-color: #000000;       /* Black */
    /* Modify these values to change the color scheme */
}
```

## File Structure
```
max_website/
├── index.html      # Main HTML structure
├── styles.css      # Styling and color scheme
├── script.js       # Interactive features
└── README.md       # Documentation
```

## Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License
All rights reserved © 2025 Maximilian Vovk

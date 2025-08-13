# NeuroAssist Website Documentation

This document explains the HTML structure and CSS styling used in the NeuroAssist website.

## HTML Structure

### Semantic Tags Used

- `<header>`: Contains the navigation and hero section
- `<nav>`: Navigation menu with links to different sections
- `<section>`: Distinct content sections (About, Features, Screenshots, etc.)
- `<figure>`: Container for images and their captions
- `<figcaption>`: Captions for screenshots
- `<blockquote>`: Testimonial in the Impact section
- `<footer>`: Contact information and copyright

### Class Naming Convention

We use descriptive class names that indicate the purpose of elements:

- `.hero`: Main landing section
- `.feature-card`: Individual feature boxes
- `.tech-item`: Technology stack items
- `.screenshot-grid`: Image gallery layout

## CSS Styling

### Color Palette

```css
--primary-color: #7C9EC2    /* Soft blue */
--secondary-color: #E6EEF5   /* Light blue background */
--accent-color: #B4A7D6      /* Soft purple */
--text-color: #2C3E50        /* Dark blue text */
--light-text: #6C7A89        /* Gray text */
--background: #FFFFFF        /* White background */
--card-background: #F8FAFC   /* Off-white for cards */
```

### Typography

- Font Family: 'Poppins' (Google Fonts)
- Responsive font sizes using rem units
- Hierarchical heading styles (h1, h2, h3)

### Layout Techniques

1. **Flexbox**
   - Navigation menu layout
   - Hero content centering
   - Footer content alignment

2. **CSS Grid**
   - Feature cards layout
   - Screenshot gallery
   - Technology stack grid

### Responsive Design

- Mobile-first approach
- Breakpoint at 768px for layout changes
- Responsive typography and spacing
- Grid columns adjust based on viewport width

### Interactive Elements

1. **Hover Effects**
   - Smooth color transitions on links
   - Card elevation on hover
   - Button scale animation

2. **Cards**
   - Subtle shadows
   - Rounded corners
   - Consistent padding

### Accessibility Features

- Semantic HTML structure
- Alt text for images
- Sufficient color contrast
- Clear visual hierarchy

## Best Practices Used

1. **CSS Organization**
   - CSS Custom Properties (variables)
   - Logical grouping of styles
   - Consistent spacing and indentation

2. **Performance**
   - Efficient selectors
   - Reusable utility classes
   - Optimized media queries

3. **Maintainability**
   - Clear class naming
   - Modular components
   - Commented sections

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles
└── Images/             # Screenshot images
```

## Browser Compatibility

The website is designed to work across modern browsers using standard CSS features:
- Flexbox and Grid layouts
- CSS Custom Properties
- Modern pseudo-selectors
- Viewport units
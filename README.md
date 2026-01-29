# Lumina Systems

A modern, professional website for Lumina Systems - a technology company providing comprehensive digital solutions including cloud architecture, web engineering, and UI/UX design.

## Features

### Pages
- **Home** - Hero section with core services showcase and call-to-action
- **About** - Company mission, values, team profiles, and impact statistics
- **Services** - Detailed service offerings with process workflow
- **Portfolio** - Showcase of completed projects with filtering capabilities
- **Contact** - Contact form, business information, and inquiry submission

### Design Features
- **Responsive Design** - Mobile-first approach, optimized for all devices
- **Modern Typography** - Inter for body text, Playfair Display for headings
- **Professional Color Scheme** - Blue (#0ea5e9) primary accent with dark navy backgrounds
- **Smooth Animations** - Hover effects, transitions, and interactive elements
- **Accessible Navigation** - Fixed navbar with mobile hamburger menu
- **Consistent Branding** - Unified footer across all pages with social links

### Technical Features
- **Pure CSS** - No JavaScript dependencies (except Font Awesome icons)
- **Grid Layouts** - CSS Grid for responsive card layouts
- **Flexbox Components** - Flexible navigation and utility layouts
- **CSS Variables** - Centralized color and spacing management
- **Performance Optimized** - Lightweight AVIF images and efficient CSS

## Project Structure

```
lumina-systems/
├── index.html           # Home page
├── about.html           # About us page
├── services.html        # Services page
├── portfolio.html       # Portfolio showcase
├── contact.html         # Contact page
├── style.css            # Global styles and core components
├── about.css            # About page specific styles
├── services.css         # Services page specific styles
├── portfolio.css        # Portfolio page specific styles
├── contact.css          # Contact page specific styles
├── assets/
│   ├── Lumina.png       # Company logo
│   ├── hero.avif        # Hero section image
│   ├── cloud.avif       # Cloud service image
│   ├── web.avif         # Web development image
│   └── ui-ux.avif       # UI/UX design image
├── LICENSE
└── README.md            # This file
```

## Color Palette

- **Primary**: #0ea5e9 (Sky Blue)
- **Dark**: #0f172a (Navy)
- **White**: #ffffff
- **Text**: #334155 (Slate Gray)
- **Light BG**: #f8fafc (Light Slate)

## Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 992px
- **Desktop**: > 992px

## Typography

- **Body Font**: Inter (400, 500 weights)
- **Heading Font**: Playfair Display (700, 800 weights)
- **Font Sizes**:
  - H1: 3rem (desktop), 2rem (mobile)
  - H2: 2.5rem (desktop), 2rem (mobile)
  - Body: 1rem - 1.1rem
  - Small: 0.85rem - 0.95rem

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/lumina-systems.git
   cd lumina-systems
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     python -m http.server 8000
     # Then visit http://localhost:8000
     ```

## Pages Overview

### Home (index.html)
- Hero section with company tagline
- Core services grid (Cloud, Web, UI/UX)
- Call-to-action section
- Professional footer

### About (about.html)
- Company mission and vision
- Core values with icons
- Impact statistics
- Team member profiles
- CTA to contact page

### Services (services.html)
- Introduction to service offerings
- Main services with feature lists
- Additional services showcase
- 4-step process workflow
- Service-specific CTAs

### Portfolio (portfolio.html)
- Project showcase with images
- Interactive filter by category (Cloud, Web, Design)
- Project details and tech stacks
- Client statistics
- Project-based CTA

### Contact (contact.html)
- Contact information (address, email, phone)
- Social media links
- Contact form with validation
- Service selection dropdown
- Professional footer

## Customization

### Colors
Edit CSS variables in `style.css`:
```css
:root {
    --primary: #0ea5e9;
    --dark: #0f172a;
    --white: #ffffff;
    --text: #334155;
    --light-bg: #f8fafc;
}
```

### Content
- Update text in HTML files
- Replace images in `/assets` folder
- Modify company info in footer sections
- Update social media links

### Fonts
Google Fonts are loaded in each HTML file. To change:
1. Update the `<link>` tag in head
2. Modify font-family in CSS

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

**Lumina Systems**
- Email: hello@luminasystems.com
- Phone: +254 700 000 000
- Location: 123 Tech Plaza, Westlands, Nairobi, Kenya
- Website: [lumina-systems.com](https://lumina-systems.vercel.app/)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Version History

- **v1.0.0** (January 2026) - Initial release with all core pages and features

---

**Built with passion using HTML, CSS, and best practices**
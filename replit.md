# Anovar HC - IT Consulting Services Website

## Overview

This is a static website for Anovar HC, an IT consulting services company. The project is built using pure HTML, CSS, and JavaScript with a focus on modern web design principles and responsive layout. The website includes a homepage (index.html), a dedicated services page (services.html), and a portfolio page (portfolio.html) showcasing the company's comprehensive IT consulting offerings and successful projects.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Technology Stack**: Pure HTML5, CSS3, and JavaScript
- **Design Approach**: Multi-page application with homepage and dedicated services page
- **Styling**: Custom CSS with CSS custom properties (variables) for consistent theming
- **Responsive Design**: Mobile-first approach with hamburger menu for mobile devices
- **Typography**: Google Fonts (Open Sans primary, Roboto fallback) for modern, readable text
- **Icons**: Font Awesome 6.4.0 for scalable vector icons

### Key Design Decisions
1. **Static Site Approach**: Chosen for simplicity, fast loading times, and easy deployment
2. **CSS Custom Properties**: Used for maintainable theming and consistent color scheme
3. **Fixed Navigation**: Provides persistent access to all sections while scrolling
4. **Backdrop Filter**: Modern CSS feature for glassmorphism effect on navigation

## Key Components

### Navigation System
- Fixed header with company branding
- Horizontal navigation menu for desktop with inter-page navigation
- Mobile hamburger menu for responsive design
- Active state management for current page/section

### Page Structure
- **Homepage (index.html)**: Hero section, services overview, testimonials, footer
- **Services Page (services.html)**: Dedicated services hero, detailed service blocks, CTA section
- **Portfolio Page (portfolio.html)**: Portfolio hero, filter buttons, project cards with case studies, CTA section

### Theming System
- CSS custom properties for color management
- Consistent spacing and typography scales
- Shadow and transition variables for unified effects
- Primary color: #3498db (blue)
- Secondary color: #2c3e50 (dark blue-gray)
- Accent color: #e74c3c (red)

### Layout Structure
- Container-based layout with max-width constraint (1200px)
- Section-based content organization
- Responsive padding and margin system

## Data Flow

As a static website, there is no complex data flow. The architecture follows a simple pattern:
1. HTML provides semantic structure
2. CSS handles presentation and responsive behavior
3. JavaScript (implied) manages interactive elements like navigation and mobile menu

## External Dependencies

### CDN Resources
- **Google Fonts**: Roboto font family (300, 400, 500, 700 weights)
- **Font Awesome**: Version 6.4.0 for icons via CDN
- **Rationale**: CDN usage reduces bundle size and leverages browser caching

### Browser Features
- CSS Custom Properties (IE 11+ support)
- Backdrop Filter (modern browsers)
- Flexbox/Grid layout systems

## Deployment Strategy

### Static Hosting Compatibility
- Designed for static hosting platforms (Netlify, Vercel, GitHub Pages)
- No server-side processing required
- All assets can be served directly from CDN or static file server

### Performance Considerations
- Minimal external dependencies
- Optimized for fast loading
- Responsive images and modern CSS techniques
- Browser caching friendly structure

### Scalability Notes
- Easy to extend with additional sections
- Modular CSS structure allows for component addition
- Can be converted to a framework-based solution if dynamic features are needed

## Development Guidelines

### Code Organization
- HTML semantic structure with clear section divisions
- CSS organized with clear comment sections
- Consistent naming conventions (kebab-case for CSS classes)
- Mobile-first responsive design approach

### Browser Support
- Modern browsers with CSS custom properties support
- Graceful degradation for older browsers
- Progressive enhancement principles applied
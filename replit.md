# Angeldp.in Desktop Publishing Website

## Overview

This is a static business website for Angeldp.in, a desktop publishing service company. The site serves as a professional online presence showcasing services like typing, content creation, book publishing, and graphic design. Built with pure HTML, CSS, and JavaScript, it features a modern, responsive design with smooth scrolling navigation and interactive elements.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Pure Web Technologies**: Built using vanilla HTML5, CSS3, and JavaScript without any frameworks or build tools
- **Single Page Application (SPA) Pattern**: All content is contained in a single HTML file with JavaScript-powered navigation between sections
- **Component-Based CSS**: Modular CSS architecture with clearly defined components (navbar, hero, buttons, cards)
- **Responsive Design**: Mobile-first approach using CSS media queries and flexible layouts

### Design Patterns
- **Progressive Enhancement**: Core content accessible without JavaScript, enhanced with smooth scrolling and animations when available
- **Smooth Scrolling Navigation**: JavaScript-powered section navigation with offset calculations for fixed header
- **Dynamic Navbar**: Scroll-based styling changes for improved user experience
- **Floating Card Components**: Reusable visual elements for showcasing key features

### Performance Optimizations
- **Lightweight Architecture**: No external dependencies or frameworks for fast loading
- **CSS Transitions**: Hardware-accelerated animations using CSS transforms and opacity
- **Backdrop Blur Effects**: Modern glass morphism design using CSS backdrop-filter
- **Event Delegation**: Efficient event handling for navigation and button interactions

### Browser Compatibility
- **Modern Web Standards**: Uses contemporary CSS features like backdrop-filter and CSS Grid
- **Graceful Degradation**: Fallbacks for older browsers that don't support advanced CSS features
- **Cross-Platform Fonts**: Font stack includes system fonts for consistent rendering across devices

## External Dependencies

### Fonts
- **Google Fonts (Inter)**: Primary typeface loaded from Google Fonts CDN
- **System Font Fallbacks**: Comprehensive fallback stack including -apple-system, BlinkMacSystemFont, Segoe UI, Roboto

### No External Services
- **Self-Contained**: No external APIs, databases, or third-party services required
- **Static Hosting Ready**: Can be deployed to any static hosting platform (GitHub Pages, Netlify, Vercel)
- **No Build Process**: Direct deployment without compilation or bundling steps
# Portfolio Website for Fengshuo Liu

## Overview

This is a single-page personal portfolio website for Fengshuo Liu, a student pursuing dual degrees in Applied Mathematics and Information & Computing Science. The website showcases his academic projects, professional experience, and skills in quantitative research and financial engineering. Built as a responsive, modern portfolio using a single HTML file architecture for simplicity and easy deployment.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single-file Architecture**: The entire website is contained within a single HTML file (`index.html`) with embedded CSS and JavaScript, making it lightweight and easy to deploy on any static hosting platform
- **Responsive Design**: Built with Bootstrap 5 grid system and responsive utilities to ensure optimal viewing across desktop, tablet, and mobile devices
- **Component-based Sections**: Organized into distinct sections (Hero, About, Projects, Experience, Education, Contact) with smooth scrolling navigation

### Design System
- **CSS Custom Properties**: Uses CSS variables for consistent theming with a dark color scheme featuring primary colors like `--primary-color: #64ffda` and `--background-dark: #0f172a`
- **Typography**: Implements Google Fonts (Inter) for modern, clean typography with multiple font weights
- **Icon System**: Integrates Font Awesome for scalable vector icons throughout the interface

### Navigation & UX
- **Fixed Navigation**: Sticky navbar that remains visible during scrolling with smooth scroll behavior
- **Single Page Application (SPA) Style**: All content loads on one page with anchor-based navigation to different sections
- **Interactive Elements**: Hover effects, transitions, and responsive button states for enhanced user experience

### Content Architecture
- **Projects Showcase**: Primary focus section using Bootstrap cards to display academic and personal projects
- **Professional Timeline**: Experience section structured to highlight internships and professional development
- **Skills & Education**: Dedicated sections for technical competencies and academic achievements

## External Dependencies

### CDN-based Dependencies
- **Bootstrap 5.3.2**: CSS framework for responsive grid system, components, and utilities loaded from `cdn.jsdelivr.net`
- **Font Awesome 6.4.0**: Icon library for social media links and UI elements loaded from `cdnjs.cloudflare.com`
- **Google Fonts (Inter)**: Web font family loaded from `fonts.googleapis.com` for typography consistency

### Hosting & Deployment
- **Static Hosting Ready**: Designed for deployment on platforms like GitHub Pages, Netlify, or Vercel
- **No Server Requirements**: Pure client-side application requiring only static file hosting
- **Cross-browser Compatibility**: Built with modern web standards while maintaining broad browser support
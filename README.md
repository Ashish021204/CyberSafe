# CyberSafe
A modern, fully responsive Cybersecurity Awareness landing page built using pure HTML and CSS. Includes a glass-effect UI, CSS-only mobile navigation, accessibility features, and clean, modern design elements. Ideal for showcasing frontend skills and responsive layout techniques.


# Cybersecurity Awareness Landing Page

A clean, accessible, responsive landing page built with **HTML and CSS only** (no JavaScript). Features a CSS-only mobile navigation and comprehensive accessibility measures.

---

## 🚀 How to Run

Open Directly in Browser
1. Download or clone this directory
2. Open `index.html` in any modern web browser
3. The page will load immediately with all features working

---

## ✅ Accessibility Checklist

This landing page implements the following accessibility measures:

### Keyboard Navigation
- ✓ **Skip-to-content link**: Visible on keyboard focus, allows users to jump directly to main content
- ✓ **Full keyboard operability**: All interactive elements (links, buttons, mobile menu) are accessible via keyboard
- ✓ **Focus indicators**: Clear, high-contrast focus states on all interactive elements (2px primary color outline)
- ✓ **Logical tab order**: Elements follow natural document flow for intuitive navigation

### Screen Reader Support
- ✓ **Semantic HTML5**: Uses `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` for proper document structure
- ✓ **ARIA attributes**: Includes `role`, `aria-label`, `aria-labelledby`, `aria-describedby`, `aria-hidden` where appropriate
- ✓ **Meaningful alt text**: All images and decorative SVGs have descriptive alt text or `aria-label` attributes
- ✓ **Hidden decorative elements**: Icons marked with `aria-hidden="true"` to prevent redundant announcements
- ✓ **Form labels**: All inputs properly associated with visible labels using `for`/`id` attributes

### Visual Accessibility
- ✓ **Color contrast**: All text meets WCAG AA standards (4.5:1 for normal text, 3:1 for large text)
- ✓ **CSS-only mobile navigation**: Accessible hamburger menu using checkbox hack, no JavaScript required
- ✓ **Responsive design**: Mobile-first approach with breakpoints at 600px and 900px
- ✓ **Touch targets**: Minimum 44×44px tap targets on mobile for easy interaction
- ✓ **Reduced motion support**: Respects `prefers-reduced-motion` media query to disable animations for sensitive users

### Content & Structure
- ✓ **Proper heading hierarchy**: Single `<h1>` followed by logical `<h2>`, `<h3>` structure
- ✓ **Descriptive link text**: All links have meaningful text (no "click here" or "read more")
- ✓ **Landmark regions**: Proper use of `role="banner"`, `role="navigation"`, `role="contentinfo"`
- ✓ **Meta tags**: Includes charset, viewport, description for SEO and accessibility

### Technical Accessibility
- ✓ **Valid HTML5**: Semantic markup with no validation errors
- ✓ **External links**: Include `rel="noopener noreferrer"` for security
- ✓ **Language declared**: `lang="en"` attribute on `<html>` element
- ✓ **Screen reader-only text**: `.sr-only` class for context that should only be read, not seen

---

## 🎨 Features

- **CSS-Only Mobile Navigation**: Hamburger menu using checkbox hack (no JavaScript)
- **Semantic HTML5**: Proper structure with header, nav, main, sections, footer
- **CSS Variables**: Clean design system with color palette, typography scale, spacing
- **Responsive Layout**: Flexbox and CSS Grid for mobile, tablet, desktop
- **Modern Design**: Deep navy and teal color scheme with smooth transitions
- **Google Fonts**: Inter and Space Grotesk for clean, professional typography

---

## 🌐 Browser Support

Works in all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

---

## 📝 Content Included

- Hero section with CTA
- Why Cybersecurity (4 feature cards)
- Quick Tips (5 actionable items)
- Resources section with search box (non-functional, CSS appearance only)
- Contact section
- Footer with social links (GitHub, Twitter, LinkedIn)

---

## 🔒 Security & Privacy

This is a static HTML/CSS landing page with no data collection, no cookies, no tracking, and no external dependencies (except Google Fonts).

---

**Built with accessibility and security in mind.**  
© 2025 CyberSafe. All rights reserved.

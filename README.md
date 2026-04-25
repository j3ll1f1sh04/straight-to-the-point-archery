# Straight to the Point Archery — Website

A multi-page website for Straight to the Point Archery, a non-profit indoor archery center based in Seattle, WA.

## Pages

| File | Description |
|------|-------------|
| `index.html` | Homepage — hero, class previews, mission, group programs |
| `classes.html` | Full class listings — A101, A102, A103, private lessons, group programs |
| `instructors.html` | Instructor profiles with photos, certifications, and bios |
| `about.html` | Center history, mission, facility details, affiliations, and policies |
| `contact.html` | Contact info, hours, and inquiry form |
| `style.css` | Shared stylesheet for all pages |

## Project Structure

```
project/
├── imgs/
│   ├── archeryAcademy-logo-color.png
│   ├── archeryAcademy-logo-white.png
│   ├── footerImage.jpg
│   ├── instructor-bio-image1.png
│   ├── instructor-bio-image2.png
│   ├── instructor-bio-image3.png
│   └── instructor-bio-image4.png
├── index.html
├── classes.html
├── instructors.html
├── about.html
├── contact.html
└── style.css
```

## Design

Built to match the official Straight to the Point style guide:

- **Primary color:** `#03a3df`
- **Navy:** `#1b447f`
- **Gold accent:** `#ecb722`
- **Typography:** Arial Bold / Regular (H1 40px, H2 24px, H3 17px, Body 17px)

## Features

- Semantic HTML5 elements throughout (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `address`)
- Fully responsive layout using CSS Flexbox and Grid with mobile breakpoints
- Sticky header with hamburger menu on mobile
- Skip navigation link for keyboard and screen reader accessibility
- Styled focus states on all interactive elements
- Font Awesome 6 icons via CDN
- No JavaScript frameworks — vanilla JS for the mobile nav toggle only

## Affiliations

Straight to the Point Archery is affiliated with the **Washington State Archery Association (WSAA)** and the **National Field Archery Association (NFAA)**. All instructors hold **USA Archery** certification.

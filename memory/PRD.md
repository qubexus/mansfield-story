# Mansfield Story - Product Requirements Document

## Problem Statement
Create a simple, bilingual (PL/EN) news portal for the Polish community in Mansfield that:
- Is free to host (GitHub Pages)
- Uses single HTML file approach
- Supports static JSON news feed
- Has professional branding (Navy #002147, Gold #D4AF37)
- Works perfectly on mobile devices
- Requires zero backend maintenance

## User Persona
**Jacob** - Polish community reporter in Mansfield
- Wants to share local news quickly
- Needs bilingual content (Polish and English)
- No technical/coding background
- Wants zero maintenance costs
- Updates news by editing JSON file on GitHub

## Core Requirements (Static)
1. Single HTML file with embedded CSS/JS
2. Bilingual toggle (PL/EN) with localStorage
3. Breaking news alert system (red pulse animation)
4. News feed loaded from JSON file
5. Contact form (Formspree integration)
6. About section for reporter
7. Responsive mobile-first design
8. Professional branding colors

## Architecture

### Technology Stack
- **Frontend**: Single HTML file
- **Styling**: Tailwind CSS (CDN)
- **Icons**: FontAwesome (CDN)
- **Fonts**: Google Fonts - Inter
- **Hosting**: GitHub Pages (free)
- **Form**: Formspree (free tier)
- **Data**: Static JSON file

### File Structure
```
mansfield-story/
├── index.html           # Main page (all-in-one)
├── newsy.json          # News feed data
├── image_6.png         # Reporter avatar
└── README.md           # Documentation
```

## What's Been Implemented ✅

### Date: December 10, 2025

#### Completed Features:
1. **index.html (25KB)**
   - Sticky navigation with branding
   - Language toggle (PL/EN) with localStorage
   - Hero section with gradient
   - Breaking news alert with pulse animation
   - News grid (3 columns on desktop, responsive)
   - About section with avatar
   - Contact form (Formspree ready)
   - Footer with social links
   - All CSS animations and transitions

2. **newsy.json**
   - 6 sample news articles
   - Bilingual structure (title_pl/title_en, text_pl/text_en)
   - Breaking news flag
   - Image URLs (Unsplash)
   - Links to X/Twitter posts
   - Date fields

3. **MANSFIELD_README.md**
   - Complete setup instructions
   - GitHub Pages deployment guide
   - How to edit news
   - How to add Formspree ID
   - FAQ section
   - Color palette reference

4. **preview.html**
   - Visual overview of the site
   - Feature list
   - Quick start guide
   - Links to all files

### Features Detail:

#### Bilingual System
- Instant language switching
- localStorage persistence
- All UI elements translated
- News content in both languages

#### Visual Design
- Deep Navy (#002147) gradient header
- Gold (#D4AF37) accents and borders
- Breaking news red (#DC2626) with pulse animation
- Glassmorphism effects on contact form
- Smooth transitions and hover effects
- Mobile-first responsive design

#### Functionality
- Dynamic JSON news loading
- Conditional breaking news display
- Smooth scroll navigation
- Form submission handling
- Error handling for missing JSON
- Skeleton loading states

## Prioritized Backlog

### P0 (User must do)
- [ ] Add personal reporter photo (image_6.png)
- [ ] Create Formspree account and add ID to form
- [ ] Create GitHub repository
- [ ] Upload files to GitHub
- [ ] Enable GitHub Pages

### P1 (Nice to have)
- [ ] Add real news content to newsy.json
- [ ] Update social media links
- [ ] Add Google Analytics
- [ ] Custom domain setup

### P2 (Future enhancements)
- [ ] RSS feed generation
- [ ] Search functionality
- [ ] News categories/tags
- [ ] Comment system
- [ ] Newsletter signup

## Next Tasks
1. User downloads the 3 files (index.html, newsy.json, README)
2. User adds their reporter photo as image_6.png
3. User creates GitHub repository
4. User uploads files to GitHub
5. User enables GitHub Pages in Settings
6. User creates Formspree account and updates form ID
7. User edits newsy.json with their first real news article
8. Site is live! 🚀

## Technical Notes
- All external resources use CDN (no npm/build required)
- News images can be from Unsplash or any public URL
- Form submissions go to Formspree (free 50/month)
- Language preference stored in browser localStorage
- Zero backend = zero maintenance = zero costs

## Success Metrics
- ✅ Single file deployment
- ✅ Zero hosting costs
- ✅ Mobile responsive
- ✅ Professional design
- ✅ Bilingual support
- ✅ Easy news updates (JSON editing)
- ✅ No technical knowledge required

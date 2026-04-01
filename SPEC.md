# STAGE Website Specification

## Project Overview
- **Project Name**: STAGE (Study of Theatre Arts & Global Entertainment)
- **Type**: Multi-page static website
- **Core Functionality**: A website for STAGE concentration in Production Media department, Vocational Education Program, University of Indonesia. Focuses on Broadway/Performance Art education.
- **Target Users**: Students interested in performing arts, theatre, and stage performance

## UI/UX Specification

### Layout Structure
- **Header**: Logo and navigation
- **Hero Section**: Main landing area with animated text and illustration
- **Main Content**: Level progress and navigation buttons
- **Footer**: Social links and copyright

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Visual Design

#### Color Palette
- **Primary**: #4B1E83 (Deep Purple)
- **Background Gradient**: #5A2AA3 (Lighter Purple) to #4B1E83
- **Accent**: #0D10DD (Electric Blue)
- **Text**: #FFFFFF (White)

#### Typography
- **Font Family**: "Poppins" (Google Fonts - Sans Serif, elegant and modern)
- **Hero STAGE**: 8rem, bold, white
- **Hero Subtitle**: 2.5rem, medium weight
- **Hero Description**: 1.2rem, light
- **Body Text**: 1rem, regular

#### Spacing System
- Section padding: 80px vertical
- Content max-width: 1200px
- Card padding: 30px
- Button padding: 15px 40px

### Components

#### Hero Section
- Large "STAGE" text centered
- "Rise of The Performer" subtitle below
- "Embark on an exciting adventure to become a stage star!" description
- Performance art illustration box (CSS art/placeholder)
- "Start Your Stage Journey" CTA button

#### Level Progress Bar
- Current level display (New Talent, Rising Star, etc.)
- XP counter with progress bar
- Animated progress fill

#### Navigation Cards (3 equal columns)
- Explore STAGE - navigates to explore.html
- Watch Performance - navigates to watch.html
- Claim Reward - navigates to reward.html

#### Button States
- Default: Solid background with accent color
- Hover: Scale up 1.05, glow effect
- Active: Slightly pressed effect

## Functionality Specification

### Core Features
1. **Hero Animation**: Fade-in animations on page load
2. **Level System**: Display current level and XP (simulated)
3. **Navigation**: Smooth transitions between pages
4. **Interactive Cards**: Hover effects on main navigation

### Pages
1. **index.html** - Main landing page
2. **explore.html** - About STAGE program
3. **watch.html** - Performance gallery
4. **reward.html** - Rewards/claims system

### User Interactions
- Click navigation buttons to switch pages
- Hover effects on interactive elements
- Level bar animation on load

## Acceptance Criteria
1. ✓ Hero section displays with STAGE as largest text
2. ✓ Rise of The Performer appears below STAGE
3. ✓ Description text appears below subtitle
4. ✓ Illustration box present below text content
5. ✓ Start Your Stage Journey button present
6. ✓ Level bar shows current level and XP
7. ✓ Three navigation cards displayed equally sized
8. ✓ Color palette matches specification
9. ✓ Sans-serif font (Poppins) applied
10. ✓ Responsive design works on all devices
# The Bernini-Warhol Project - Website Specification

## 1. Project Overview
- **Project Name**: The Bernini-Warhol Project
- **Type**: Static multi-section website
- **Core Functionality**: Cultural initiative homepage showcasing community programs, events, and mission
- **Target Users**: Artists, cultural enthusiasts, community organizers, potential partners

## 2. UI/UX Specification

### Layout Structure
- **Header**: Fixed navigation with logo and menu links
- **Hero**: Full-viewport dramatic opening with animated text
- **About**: Mission statement with visual dialogue concept
- **Programs**: Four program cards in responsive grid
- **Vision**: Section highlighting the bridge between tradition and innovation
- **Footer**: Contact and social links

### Responsive Breakpoints
- Mobile: < 768px (single column)
- Tablet: 768px - 1024px (two columns)
- Desktop: > 1024px (full layout)

### Visual Design

#### Color Palette
- **Primary**: `#0D0D0D` (rich black)
- **Secondary**: `#F5F0E8` (warm ivory/cream)
- **Accent Classical**: `#8B4513` (sienna/Baroque brown)
- **Accent Modern**: `#FF3366` (Warhol pop pink)
- **Muted**: `#4A4A4A` (charcoal gray)
- **Gold accent**: `#C9A962` (antique gold)

#### Typography
- **Headings**: "Playfair Display" (serif, classical elegance)
- **Body**: "Syne" (modern, distinctive geometric sans)
- **Accent Text**: "Cormorant Garamond" (refined italic for quotes)

#### Spacing System
- Section padding: 100px vertical, 5% horizontal
- Card gaps: 32px
- Component margins: 24px

#### Visual Effects
- Smooth scroll behavior
- Fade-in animations on scroll (intersection observer)
- Subtle parallax on hero
- Hover lift effects on cards
- Text reveal animations
- Border accent animations (dual-colored lines)

### Components

#### Navigation
- Logo text: "B|W" monogram + "Bernini-Warhol Project"
- Links: About, Programs, Vision, Contact
- Hamburger menu on mobile
- Backdrop blur on scroll

#### Hero Section
- Split background: left side darker with classical texture, right with bold color block
- Animated title with staggered letter reveal
- Subtitle with typewriter-style reveal
- Scroll indicator arrow

#### About Section
- Large pull quote
- Two-column layout explaining the dialogue concept
- Decorative line elements

#### Programs Grid
- 4 cards: Collaborative Events, Workshops & Dialogues, Cultural Bridge-Building, Global Community Networks
- Each card: icon, title, description, hover effect
- Alternating accent colors (classical gold / modern pink)

#### Vision Section
- Centered inspirational message
- Background subtle gradient
- Animated border element

#### Footer
- Minimal design
- Social links
- Copyright

## 3. Functionality Specification

### Core Features
- Smooth scrolling navigation
- Scroll-triggered animations
- Mobile-responsive hamburger menu
- Interactive hover states on all clickable elements

### User Interactions
- Click nav links → smooth scroll to section
- Hover cards → lift and accent reveal
- Scroll → elements fade in from bottom

### Animations
- Hero title: letter-by-letter fade-in with slight upward motion
- Hero subtitle: fade in after title completes
- Cards: stagger fade-in on scroll
- Decorative lines: draw animation

## 4. Acceptance Criteria
- [ ] Page loads with hero animation sequence
- [ ] Navigation scrolls smoothly to all sections
- [ ] All 4 program cards display with correct content
- [ ] Mobile menu opens/closes properly
- [ ] Scroll animations trigger at correct positions
- [ ] Colors match specified palette exactly
- [ ] Fonts load correctly (Google Fonts)
- [ ] Responsive at all breakpoints

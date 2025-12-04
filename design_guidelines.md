# VAHNARA Design Guidelines

## Design Approach
**Reference-Based Approach**: Sci-fi aesthetic inspired by Star Wars, Pokémon Go, and modern AR experiences. Focus on cinematic immersion with neon energy lines, cosmic gradients, and glowing elements that evoke a futuristic exploration universe.

## Core Design Elements

### Typography
- **Primary Font**: Poppins (hero headlines, body text)
- **Secondary Font**: Orbitron (tech/UI elements, stats, VCI features)
- **Accent Font**: Inter (form labels, small UI text)
- **Hero Headline**: Bold, 3xl-6xl, with soft cyan glow effect (text-shadow)
- **Section Headers**: 2xl-4xl, medium weight, subtle purple glow
- **Body Text**: Base to lg, light weight, high contrast against dark backgrounds

### Color Palette
- **Background**: #05050A (deep cosmic black)
- **Primary Accent**: #7B4BFF (neon purple)
- **Secondary Accent**: #00E5FF (neon cyan)
- **Gradients**: Purple-to-cyan for cards, cosmic nebula gradients for backgrounds
- **Text**: White (#FFFFFF) primary, rgba(255,255,255,0.7) for secondary text
- **Glow Effects**: Cyan and purple halos around interactive elements

### Layout System
- **Spacing**: Tailwind units of 4, 8, 12, 16, 24 (p-4, py-8, my-12, etc.)
- **Container**: max-w-7xl for main content, full-width for hero and cosmic sections
- **Section Padding**: py-16 to py-24 for desktop, py-12 for mobile
- **Multi-Column**: 2-3 columns for feature cards (lg:grid-cols-3), single column on mobile

## Page Structure

### 1. Hero Section (100vh)
- Animated cosmic background with particle effects and nebula
- Centered headline: "Follow your path. Vahnara will do the rest."
- Subtext with lore emphasis
- Two prominent CTAs: "Join Early Access" (primary purple) and "Watch Trailer" (secondary outline with cyan glow)
- Buttons use backdrop blur effect

### 2. About Vahnara
- Two-column layout (text + cosmic visual element)
- Lore-style typography with quotable text: "In Vahnara, the only wrong path... is the one you never walk."
- Purple gradient background with particle overlay

### 3. The World / Lore Section
- Grid of mystical glyphs and placeholder symbols (3-column on desktop)
- Each card has subtle hover glow effect (purple-to-cyan transition)
- Dark cards with neon borders and cosmic iconography

### 4. VCI Device Section
- Centered rotating/pulsing orb graphic (simulating 3D)
- 4-column feature grid below:
  - Real-world detection
  - Haptic feedback + light signals
  - Social proximity alerts
  - AR creature interactions
- "Preorder / Join Waitlist" CTA with cyan glow

### 5. Gameplay & Features
- 3-column glowing card grid (2 on tablet, 1 on mobile)
- Cards with hover animations (lift effect + glow intensification)
- Features: Exploration, Raids, Social Encounters, Daily Quests, Territory Zones, Fitness Integration, Competitive Events
- Icons/symbols for each feature with neon accents

### 6. Social Mission Section
- Single-column centered layout
- Community icons with purple/cyan gradient fills
- Emphasis on outdoor exploration and real-world connections

### 7. Early Access Signup
- Centered form with cosmic background
- Headline: "Become a Pathfinder. Join the First Wave."
- Fields: Name, Email, Location (glowing input borders on focus)
- Submit button with cyan-to-purple gradient

### 8. Community Links
- 4-button horizontal layout (Discord, YouTube, Instagram, WhatsApp)
- Icon buttons with hover glow effects
- Purple-to-cyan gradient borders

### 9. Footer
- Dark background with purple accent line separator
- Logo placeholder, tagline, legal links (Privacy, Terms)
- Minimal, clean layout

## Animations & Interactions
- **Parallax Scrolling**: Subtle on hero cosmic elements
- **Particle Background**: Slow-moving stars/energy particles in hero
- **Hover Effects**: Cards lift with shadow + glow intensification
- **Text Glow**: Soft pulsing on headlines and CTAs
- **Smooth Scroll**: Transitions between sections
- **Button States**: Glow on hover, slight scale on active

## Images
**Large Hero Image**: Yes - animated cosmic background (particles, nebula, stars). This is generated via CSS/canvas animations rather than static image.

**VCI Device Visual**: Glowing orb placeholder - can be CSS-generated or simple graphic. Should pulse/rotate subtly.

**Lore Section Icons**: Placeholder glyphs and mystical symbols (SVG or icon font).

All visuals maintain the neon sci-fi aesthetic with purple/cyan color scheme.
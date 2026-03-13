# AI-Themed Portfolio for Pawan Singh - Specification

## Project Overview
- **Project Name**: Pawan Singh Portfolio
- **Type**: Single-page personal portfolio website
- **Core Functionality**: Interactive AI-themed portfolio showcasing skills, projects, and achievements
- **Target Users**: Recruiters, potential employers, collaborators

## UI/UX Specification

### Layout Structure
- **Navigation**: Fixed top nav with glassmorphism effect, smooth scroll links
- **Hero Section**: Full viewport height with animated AI neural network background
- **About Section**: Brief intro with typing animation
- **Education Section**: Timeline-style with animated cards
- **Skills Section**: Animated progress bars with glow effects
- **Projects Section**: Card grid with hover effects
- **Achievements Section**: Counter animations with particle effects
- **Contact Section**: Interactive form with AI chatbot-style hints
- **Footer**: Minimal with social links

### Visual Design

#### Color Palette
- **Primary Background**: #0a0a0f (deep space black)
- **Secondary Background**: #12121a (dark navy)
- **Primary Accent**: #00f5d4 (cyan/teal - AI theme)
- **Secondary Accent**: #7b2cbf (purple)
- **Tertiary Accent**: #ff006e (pink)
- **Text Primary**: #ffffff
- **Text Secondary**: #a0a0b0
- **Card Background**: rgba(255, 255, 255, 0.05)

#### Typography
- **Headings**: 'Orbitron', sans-serif (futuristic tech font)
- **Body**: 'Exo 2', sans-serif
- **Code/Tech**: 'Fira Code', monospace

#### Spacing System
- Section padding: 100px vertical
- Card padding: 30px
- Element gaps: 20px

#### Visual Effects
- **Neural Network Animation**: Canvas-based particle network in hero
- **Glow Effects**: Cyan/purple glow on interactive elements
- **Glassmorphism**: Frosted glass cards with blur
- **Typing Animation**: For hero tagline
- **Scroll Animations**: Fade-in, slide-up on scroll
- **Hover Effects**: Scale, glow, color shift
- **Floating Particles**: Subtle background particles
- **Gradient Borders**: Animated gradient borders on cards
- **Matrix Rain Effect**: Subtle digital rain in background

### Components

1. **Nav Bar**
   - Logo with glow effect
   - Links: About, Education, Skills, Projects, Achievements, Contact
   - Hamburger menu on mobile
   - Glassmorphism background

2. **Hero Section**
   - Neural network animated background (canvas)
   - Profile image with circular glow
   - Name with typing animation
   - Title: "B.Tech CS Student | Software Developer"
   - CTA buttons with hover glow
   - Scroll indicator

3. **Education Cards**
   - Institution name
   - Degree details
   - Timeline indicator
   - Animated entrance

4. **Skill Bars**
   - Category grouping (Languages, Web, Tools)
   - Animated fill with glow
   - Percentage display
   - Hover tooltips

5. **Project Cards**
   - Image/screenshot area
   - Title and description
   - Tech stack tags
   - GitHub link
   - Hover: lift + glow

6. **Achievement Counters**
   - Animated number counting
   - Icon with glow
   - Description

7. **Contact Form**
   - Input fields with floating labels
   - AI suggestion hints
   - Submit button with loading state

## Functionality Specification

### Core Features
1. **Smooth Scrolling**: Navigation links scroll to sections
2. **Mobile Responsive**: Hamburger menu, stacked layouts
3. **Dark Mode Only**: AI/tech theme (no toggle needed)
4. **Contact Form**: Functional form (can use Formspree)
5. **Social Links**: LinkedIn, GitHub, Email

### User Interactions
- Hover effects on all interactive elements
- Click to navigate sections
- Scroll-triggered animations
- Form validation

### Animations
- Hero: Neural network canvas animation (continuous)
- Typing effect on hero text
- Skill bars animate on scroll into view
- Cards fade-in on scroll
- Counter animations for achievements
- Floating particles in background
- Gradient border animations on cards
- Button hover: scale + glow pulse

## Content to Include

### Personal Info
- Name: Pawan Singh
- Location: Bhopal, Madhya Pradesh, India
- Phone: +91-9905865183
- Email: pspawansingh016@gmail.com
- LinkedIn: linkedin.com/in/pawansingh999

### Education
- B.Tech in CSE | Sagar Group of Institutions - SISTec | Oct 2023 - Oct 2027
- Relevant Coursework: DSA, OOP, Web Dev, DBMS

### Skills
- **Languages**: C, C++, Python, HTML, CSS, JavaScript
- **Web**: HTML5, CSS3, Responsive Design, Frontend Dev
- **Tools**: Git, GitHub, VS Code, Linux/Unix
- **Core**: DSA, OOP, Problem Solving, SDLC

### Projects
1. Personal Portfolio Website (2024)
2. Student Management System (2024)
3. Algorithm Visualizer (2023)

### Achievements
- 100+ DSA problems solved
- 3-star CodeChef rating
- Mentored 10+ students
- Active coding competitions participant

## Acceptance Criteria

1. ✅ Hero section displays with neural network animation
2. ✅ All sections (About, Education, Skills, Projects, Achievements, Contact) are present
3. ✅ Responsive on mobile, tablet, desktop
4. ✅ Smooth scroll navigation works
5. ✅ All animations render smoothly
6. ✅ Contact form is functional
7. ✅ Social links open in new tabs
8. ✅ No console errors
9. ✅ All content from resume is accurately included
10. ✅ AI/tech theme is consistent throughout

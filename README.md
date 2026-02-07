**Live Link:https://cursor-clone-drab-five.vercel.app/

**OutputScreenshot:
[CURSOR](assets/output-c.jpeg "output-cursor")
# Cursor Website

A modern, responsive website for Cursor - an AI-powered code editor. This project showcases a sleek dark theme design with interactive sections and brand displays.

## Getting Started

### Prerequisites
- Git (for cloning the repository)
- A modern web browser (Chrome, Firefox, Safari, Edge, etc.)
- Optional: Python 3 or Node.js (for running a local development server)

### Installation & Running Locally

#### 1. Clone the Repository
```bash
git clone https://github.com/AnujRaghav/cursor.git
cd cursor
```

#### 2. Run the Website

**Option A: Direct Browser (Simplest)**
- Navigate to the cloned folder
- Double-click `index.html` to open it in your default browser
- The site will load and display fully


```

**Option B: Using VS Code Live Server**
- Install the "Live Server" extension in VS Code
- Right-click `index.html` and select "Open with Live Server"
- The site will open automatically in your browser

### Project Structure
```
cursor/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with all colors and fonts
├── README.md           # This file
└── assets/             # Images and media files
    ├── background/     # Background images
    ├── Ide/           # IDE screenshots
    ├── logo/          # Logos
    └── people/        # Profile images
```

---

## Sections Recreated

### 1. **Header/Navigation**
- Sticky navigation bar with logo
- Navigation links (Features, Enterprise, Pricing, Resources)
- Sign In and Download buttons
- Responsive design with proper spacing

### 2. **Hero Section**
- Main headline: "Built to make you extraordinarily productive, Cursor is the best way to code with AI."
- Download for Linux button with arrow indicator
- Eye-catching typography with optimized spacing

### 3. **Primary Hero with Media**
- Background image display
- Overlaid IDE screenshots showcasing the product
- Responsive layout with proper aspect ratios

### 4. **Trusted By**
- "Trusted every day by millions of professional developers" headline
- Logo grid displaying 8 partner companies:
  - Stripe, OpenAI, Linear, Datadog, Nvidia, Figma, Ramp, Adobe
- Card-based layout with consistent spacing

### 5. **Feature Sections (Secondary Heroes)**
Three feature showcase sections with alternating left-right layouts:
- **Agent**: "Agent turns ideas into code" - highlighting AI-powered development
- **Tab**: "Magically accurate autocomplete" - featuring precise code predictions
- **Ecosystem**: "Everywhere software gets built" - showing GitHub, Slack, and other integrations
- Each includes background imagery, IDE previews, and call-to-action links

### 6. **Testimonials/Comments Section**
- Six customer testimonial cards featuring quotes from industry leaders:
  - Diana Hu (Y Combinator General Partner)
  - shadcn (Creator of shadcn/ui)
  - Andrej Karpathy (CEO, Eureka Labs)
  - Patrick Collison (Co-Founder & CEO, Stripe)
  - ThePrimeagen (Prominent developer)
  - Greg Brockman (President, OpenAI)
- User images, names, and roles
- Grid-based responsive layout (3 columns)

### 7. **Stay on the Frontier Section**
- "Stay on the frontier" headline
- Three feature cards:
  - "Use the best model for every task"
  - "Complete codebase understanding"
  - "Develop enduring software"
- Each card includes description, link, and supporting imagery

### 8. **Changelog Section**
- Latest updates and version releases
- Four changelog items with version numbers and dates
- "See what's new in Cursor" link for more updates

### 9. **Team Section**
- "Cursor is an applied research team" headline
- Team photo section with background imagery
- "Join us" call-to-action link

### 10. **Highlights/Blog Section**
- Featured articles:
  - "Introducing Cursor 2.0 and Composer"
  - "Improving Cursor Tab with online RL"
  - "1.5x faster MoE training with custom MXFP8 kernels"
- Each highlight includes title, description, category, and date
- "More posts" navigation link

### 11. **Footer**
- Multi-column footer layout with 6 sections:
  - Product (Agents, Enterprise, Code Review, Tab, CLI, Cloud Agents, Pricing)
  - Resources (Download, Changelog, Docs, Forum)
  - Company (Careers, Blog, Community, Students, Brand, Anysphere)
  - Legal (Terms of Service, Privacy Policy, Data Use)
  - Connect (X, LinkedIn, YouTube)
- Copyright notice

---

## Fonts

**Primary Font: Poppins**
- Imported from Google Fonts
- All weights available: 100-900 (including italic variants)
- Applied globally to all text elements via CSS variable
- Provides clean, modern, and highly readable typography

---

## Colors

### Dark Theme Palette

| Variable | HSL Value | Name | Usage |
|----------|-----------|------|-------|
| `--c-main` | hsl(47, 29%, 6%) | Deep Dark Brown | Main background color |
| `--c-card` | hsl(45, 17%, 9%) | Dark Brown | Card backgrounds, containers |
| `--c-text` | hsl(40, 3%, 79%) | Light Gray/Beige | Primary text content |
| `--c-mute-text` | hsl(45, 2%, 56%) | Medium Gray | Secondary text, muted labels |
| `--c-button` | hsl(0, 3%, 93%) | Off-White | Headlines, buttons, emphasis |
| `--c-btn-white` | hsl(0, 3%, 93%) | Off-White | White button text |
| `--c-link` | hsl(19, 100%, 48%) | Bright Orange | Links and accent elements |
| Additional | #201e18 | Dark Brown Highlight | Card backgrounds (highlights) |
| Additional | #1b1913 | Very Dark Brown | Section backgrounds |

### Color Accessibility
- High contrast between text and backgrounds ensures readability
- Orange accent (`--c-link`) provides visual hierarchy and call-to-action emphasis
- Dark theme reduces eye strain while maintaining modern aesthetics

---

## Design Features

- **Responsive Layout**: Grid and flexbox-based responsive design
- **Modern Spacing**: Consistent padding and margin using CSS custom properties
- **Rounded Corners**: 4px and 8px border-radius for a polished look
- **Hover Effects**: Interactive elements with opacity changes on hover
- **Image Optimization**: WebP format for backgrounds, PNG for screenshots
- **Accessibility**: Proper semantic HTML with alt text for all images

---

## Asset Structure

```
assets/
├── background/      # Background images for sections
├── Ide/            # IDE/product screenshot images
├── logo/           # Company logos (Cursor and partner logos)
└── people/         # User testimonial profile images
```

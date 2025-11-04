# My Web Development Journey — Portfolio Website

A modern, professional portfolio website showcasing my 4+ year journey in web development, from learning HTML to building full-stack applications with Next.js, Node.js, and PHP.

## 🌟 Features

- **Modern, Minimal Design** — Clean and professional UI with a government-tech inspired aesthetic
- **Responsive Layout** — Fully responsive design that works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations** — Subtle hover effects and transitions for better user experience
- **Timeline Journey** — Interactive timeline showcasing my learning progression from 2020 to 2025
- **Project Showcase** — Featured projects with technology stack highlights
- **Technology Stack Display** — Visual representation of all technologies I've learned
- **Dark Footer** — Professional footer with contact information
- **Scroll Progress Bar** — Visual indicator of page scroll progress

## 🎨 Design System

### Color Palette
- **Primary Blue**: `#3B82F6`
- **Violet**: `#8B5CF6`
- **Magenta**: `#EC4899`
- **Green**: `#22C55E`
- **Teal**: `#06B6D4`
- **Orange**: `#F97316`
- **Background**: `#F9FAFB` (Light gray)
- **Cards**: `#FFFFFF` (White)
- **Footer**: `#0F172A` (Dark navy)

### Typography
- **Headings**: Poppins (600-700 weight)
- **Body Text**: Inter (400-500 weight)

### Design Elements
- Border Radius: 16px (standard), 20px (large)
- Shadows: Soft shadows with 0.05 opacity
- Transitions: 0.3s ease for smooth interactions
- Hover Effects: Scale 1.03 with shadow lift

## 🚀 Technologies Used

This portfolio website is built with:

- **HTML5** — Semantic markup
- **CSS3** — Custom properties (CSS variables), Flexbox, Grid
- **Vanilla JavaScript** — Smooth scrolling, scroll progress indicator
- **Google Fonts** — Poppins & Inter font families

## 📁 Project Structure

```
about-me-english/
├── index.html          # Main HTML file with embedded CSS and JS
└── README.md           # Project documentation
```

## 🎯 Sections Overview

### 1. **Header / Navigation**
- Logo with initials
- Brand name and tagline
- Navigation menu with smooth scroll links
- Call-to-action button

### 2. **Hero Section**
- Main heading with journey description
- Lead paragraph explaining the story
- Two action buttons (View Projects, Get in Touch)
- Statistics cards (Years, Projects, Technologies)

### 3. **Timeline (2020 → 2025)**
- Year-by-year breakdown of learning journey
- Starting from HTML basics to full-stack development
- Includes technologies learned and projects built at each stage

### 4. **Featured Projects**
Six major projects showcasing different technologies:
- **I-Card Generator** — Next.js, MongoDB, Cloudinary
- **Taqdis Computers Portal** — PHP/Next.js with quiz system
- **Ladki Bahin Yojna Portal** — Next.js data extraction project
- **News App** — Node.js/Express API integration
- **StudyDocs** — Next.js + Nextra documentation site
- **CookBook** — Angular + Firebase application

### 5. **Technology Stack**
Visual grid displaying 10+ technologies:
- HTML & CSS
- JavaScript
- React.js & Next.js
- Node.js & Express
- MongoDB & MySQL
- PHP
- Git & GitHub

### 6. **About Section**
Four info cards covering:
- Education (MCA Student)
- Location (Dhule, Maharashtra)
- Experience (4+ years)
- Approach (Self-taught)

### 7. **Footer / Contact**
- Contact heading and description
- Email and phone information
- Email CTA button
- Copyright notice

## 💡 Key Features Explained

### Scroll Progress Bar
A fixed progress indicator at the top of the page that shows how much of the content has been scrolled.

### Smooth Scrolling
All navigation links use smooth scrolling behavior for better user experience when jumping between sections.

### Responsive Design
The layout automatically adapts to different screen sizes:
- Desktop: Full multi-column layouts
- Tablet: Adjusted column counts
- Mobile: Single-column stacked layout

### Hover Effects
All interactive elements (cards, buttons, links) have subtle hover effects:
- Scale transformation (1.03)
- Shadow elevation
- Color transitions

## 🛠️ Setup & Usage

### Option 1: Direct Browser Opening
Simply open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

### Option 2: Local Server
For development with live reload, use any local server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Then visit http://localhost:8000
```

**Using Node.js (with http-server):**
```bash
npx http-server -p 8000
```

**Using PHP:**
```bash
php -S localhost:8000
```

**Using VS Code Live Server Extension:**
1. Install "Live Server" extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 🎨 Customization Guide

### Changing Colors
All colors are defined as CSS variables in the `:root` selector. Modify these values to change the color scheme:

```css
:root {
  --blue: #3B82F6;        /* Change primary color */
  --violet: #8B5CF6;      /* Change secondary color */
  --magenta: #EC4899;     /* Change accent color */
  /* ... etc */
}
```

### Updating Content
1. **Personal Information**: Update the header section with your name and title
2. **Timeline**: Modify the `.timeline` section with your journey
3. **Projects**: Update the `.projects` section with your project details
4. **Contact Info**: Change email and phone in the footer

### Adding New Sections
Follow the existing section structure:
```html
<section class="section">
  <h2 class="section-title">Section Title</h2>
  <!-- Your content here -->
</section>
```

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 🌐 Deployment

This is a static website and can be deployed to any static hosting service:

### Free Hosting Options:
- **Vercel** — Best for Next.js but supports static sites
- **Netlify** — Drag & drop deployment
- **GitHub Pages** — Free hosting with GitHub
- **Cloudflare Pages** — Fast CDN delivery
- **Render** — Free static site hosting

### Quick Deploy to GitHub Pages:
1. Create a GitHub repository
2. Push your code
3. Go to Settings → Pages
4. Select branch and root folder
5. Your site will be live at `username.github.io/repo-name`

## 📝 To-Do / Future Enhancements

- [ ] Add project links (currently placeholders)
- [ ] Integrate a contact form with backend
- [ ] Add blog section for technical articles
- [ ] Include testimonials or recommendations
- [ ] Add dark mode toggle
- [ ] Implement analytics tracking
- [ ] Add social media links
- [ ] Create downloadable resume/CV

## 👤 Author

**Ansari Intesab**
- Email: ansariintesab048@gmail.com
- Phone: +91 89832 45824
- Location: Dhule, Maharashtra

## 📄 License

This project is open source and available for personal use. Feel free to fork and customize for your own portfolio!

## 🙏 Acknowledgments

- **CodeWithHarry** — Primary learning resource for web development
- **Google Fonts** — Poppins and Inter font families
- **YouTube Community** — Various tutorials and learning resources

---

**Built with 💙 by Ansari Intesab**

*A self-taught developer's journey from HTML pages to full-stack applications*

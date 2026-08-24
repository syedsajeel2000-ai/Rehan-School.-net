# Rehan School Clone — CWI Task 44

A fully functional clone of [RehanSchool.net](https://rehanschool.net/), an AI-enabled educational platform focused on innovative curriculum, technology-based learning, entrepreneurship, and holistic development.

## 📋 Project Description

This project is a complete, modern, responsive web application inspired by Rehan School's public-facing website. It communicates the school's innovative vision for education in the AI and internet era, including:

- **AI-Enabled Education** — Pakistan's first AI-enabled school
- **Innovative Curriculum** — Technology-driven, evolving learning approach
- **"No Pen, No Book"** — Technology as primary learning tools
- **Entrepreneurial Focus** — Learn to earn through freelancing and digital skills
- **Global Citizenship** — SDG-aligned life missions
- **Holistic Development** — Beyond academics

## ✨ Features

### Pages
- **Home** — Hero, Mission/Vision, Unique Features, Statistics, Curriculum Preview, Testimonials, Articles, CTA
- **Curriculum** — Philosophy, Levels (5th-8th Grade), Technology, Wala/Wali concept, SDGs
- **Facilitators** — Team profiles with roles, bios, and social links
- **Contact** — Form with validation, phone, email, addresses
- **About** — School overview, why choose us, unique features
- **Founder** — Rehan Allahwala's message and vision
- **Campus** — Locations and special learning environments
- **Video Tours** — Virtual tour links and campus highlights
- **Article Detail** — Individual article pages with content

### Technical Features
- ⚡ **React + Vite** — Fast development and build
- 🎨 **Modern Design** — Clean, premium UI with custom CSS
- 📱 **Fully Responsive** — Works on all screen sizes (320px to 1440px+)
- 🎯 **Scroll Animations** — Intersection Observer-based reveal animations
- 🔢 **Counter Animations** — Animated statistics counters
- 📝 **Form Validation** — Client-side validation with error states
- 🍔 **Mobile Navigation** — Hamburger menu with animations
- ♿ **Accessibility** — Semantic HTML, ARIA labels, keyboard navigation
- 🔄 **Route-based Loading** — Lazy loading with Suspense
- 🛡️ **Error Handling** — 404 page, form errors, loading states

## 🛠️ Technologies Used

- **React 19** — UI framework
- **React Router DOM 7** — Client-side routing
- **Vite 8** — Build tool and dev server
- **Pure CSS** — No CSS frameworks, fully custom styling
- **Intersection Observer API** — Scroll animations

## 📁 Project Structure

```
├── public/              # Static assets
├── src/
│   ├── components/      # Shared components
│   │   ├── Header.jsx   # Navigation header with mobile menu
│   │   ├── Header.css
│   │   ├── Footer.jsx   # Site footer
│   │   ├── Footer.css
│   │   └── Icons.jsx    # SVG icon library
│   ├── data/
│   │   └── siteData.js  # All structured data
│   ├── hooks/
│   │   └── useInView.js # Intersection Observer hooks
│   ├── pages/
│   │   ├── Home.jsx     # Homepage with all sections
│   │   ├── Home.css
│   │   ├── Curriculum.jsx
│   │   ├── Curriculum.css
│   │   ├── Facilitators.jsx
│   │   ├── Facilitators.css
│   │   ├── Contact.jsx
│   │   ├── Contact.css
│   │   ├── About.jsx
│   │   ├── About.css
│   │   ├── Founder.jsx
│   │   ├── Founder.css
│   │   ├── Campus.jsx
│   │   ├── Campus.css
│   │   ├── Tours.jsx
│   │   ├── Tours.css
│   │   ├── ArticleDetail.jsx
│   │   ├── ArticleDetail.css
│   │   ├── NotFound.jsx
│   │   └── NotFound.css
│   ├── styles/
│   │   └── index.css    # Global styles and CSS variables
│   ├── App.jsx          # Router and app shell
│   └── main.jsx         # Entry point
├── index.html
├── package.json
├── vite.config.js
├── README.md
├── LICENSE
└── .gitignore
```

## 🚀 Installation & Setup

### Prerequisites
- Node.js 18+ (recommended: 20+)
- npm, yarn, or pnpm

### Install Dependencies
```bash
npm install
```

### Development Server
```bash
npm run dev
```
The app will be available at `http://localhost:5173`

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

## 📄 Environment Variables

This project does not require any environment variables for development. All content is statically defined in `src/data/siteData.js`.

## 🚢 Deployment

The project builds to a static `dist/` folder that can be deployed to any static hosting service:

- **Vercel**: `npx vercel`
- **Netlify**: Drag and drop `dist/` folder
- **GitHub Pages**: Configure base path in `vite.config.js`
- **Any static host**: Upload `dist/` contents

## 📝 Notes

### Contact Form
The contact form is fully functional with client-side validation. Since no email service is configured, successful submissions display a demo success message noting that no email was actually sent. To add real email functionality, integrate with a service like EmailJS, Formspree, or a custom backend.

### Content Accuracy
All content is based on publicly available information from [rehanschool.net](https://rehanschool.net/) as referenced during development. Team member information, testimonials, and curriculum details are sourced from the public website.

### Images
The application uses placeholder visual elements (icons, gradients, initials) for images since the original website's image assets are proprietary. Replace with actual images in production.

## 🔗 Reference

- **Reference Website**: [rehanschool.net](https://rehanschool.net/)
- **CWI Task**: Task 44

## 📜 License

MIT License - See [LICENSE](LICENSE) for details.

## 👥 Credits

- **Rehan School** — Educational vision and content reference
- **Rehan Allahwala** — Founder of Rehan School
- Built as an educational clone for CWI Task 44

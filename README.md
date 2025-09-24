# Muhammad Umar Azam - Portfolio Website

A modern, responsive portfolio website showcasing my skills in **Web Development** and **Data Science & AI**. Built with React, TypeScript, and Tailwind CSS.

## 🌟 Live Demo

**Portfolio URL**: [View Live Portfolio](https://your-portfolio-url.vercel.app)

## 🚀 About Me

I'm Muhammad Umar Azam, a Bachelor of Computer Science student at DHA Suffa University, passionate about both Web Development and Data Science. This portfolio combines creativity from web development with analytical thinking from Data Science.

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript, Tailwind CSS
- **Build Tool**: Vite
- **UI Components**: Radix UI, shadcn/ui
- **Icons**: Lucide React
- **Deployment**: Vercel/Netlify Ready

## 📋 Features

- ✅ Responsive design (mobile-first)
- ✅ Dark/Light mode support
- ✅ Smooth scrolling navigation
- ✅ Interactive project cards
- ✅ Contact form with validation
- ✅ SEO optimized
- ✅ Performance optimized

## 🎯 Sections

1. **Hero** - Introduction with call-to-action buttons
2. **About** - Personal introduction and journey
3. **Skills** - Web Development & Data Science skills
4. **Projects** - Featured projects with live demos
5. **Experience** - Work experience and internships
6. **Education** - Academic background
7. **Hobbies** - Personal interests
8. **Contact** - Get in touch form

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ and npm

### Installation

```bash
# Clone the repository
git clone https://github.com/thisisumar/portfolio-website.git

# Navigate to project directory
cd portfolio-website

# Install dependencies
npm install

# Start development server
npm run dev
```

### Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint         # Run ESLint
```

## 📁 Project Structure

```
src/
├── components/          # React components
│   ├── ui/             # Reusable UI components
│   ├── Hero.tsx        # Hero section
│   ├── About.tsx       # About section
│   ├── Skills.tsx      # Skills showcase
│   ├── Projects.tsx    # Projects portfolio
│   ├── Experience.tsx  # Work experience
│   ├── Hobbies.tsx     # Personal hobbies
│   ├── Contact.tsx     # Contact form
│   └── Navigation.tsx  # Navigation bar
├── pages/              # Page components
├── assets/             # Static assets
├── lib/                # Utility functions
└── hooks/              # Custom React hooks
```

## 🎨 Design System

The portfolio uses a custom design system with:
- **Primary Colors**: Bright yellow (#F7DC6F) with teal accents
- **Typography**: Clean, modern font hierarchy
- **Components**: Consistent spacing and styling
- **Responsive**: Mobile-first approach

## 🔧 Customization

### Colors
Update colors in `src/index.css`:
```css
:root {
  --primary: 48 96% 72%;  /* Bright yellow */
  --secondary: 174 64% 45%; /* Teal */
  /* Add your custom colors */
}
```

### Content
Update personal information in component files:
- Contact details in `Contact.tsx`
- Projects in `Projects.tsx`
- Skills in `Skills.tsx`

## 📱 Screenshots

### Desktop View
![Desktop Screenshot](https://via.placeholder.com/800x400)

### Mobile View
![Mobile Screenshot](https://via.placeholder.com/400x600)

## 🌐 Deployment

### Vercel (Recommended)
1. Push code to GitHub
2. Connect repository to Vercel
3. Deploy automatically

### Netlify
1. Build the project: `npm run build`
2. Upload `dist` folder to Netlify

### GitHub Pages
1. Install gh-pages: `npm install --save-dev gh-pages`
2. Add to package.json:
```json
{
  "homepage": "https://thisisumar.github.io/portfolio-website",
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
  }
}
```
3. Deploy: `npm run deploy`

## 📊 Performance

- ⚡ Lighthouse Score: 90+
- 📱 Mobile Friendly
- 🚀 Fast Loading
- ♿ Accessible

## 📞 Contact

- **Email**: [uazam100@gmail.com](mailto:uazam100@gmail.com)
- **GitHub**: [@thisisumar](https://github.com/thisisumar)
- **LinkedIn**: [Muhammad Umar Azam](https://linkedin.com/in/umar-azam-985051247)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

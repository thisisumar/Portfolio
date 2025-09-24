Muhammad Umar Azam - Portfolio Website
A modern, responsive portfolio website showcasing my skills in Web Development and Data Science & AI. Built with React, TypeScript, and Tailwind CSS.

🌟 Live Demo
Portfolio URL: View Live Portfolio

🚀 About Me
I'm Muhammad Umar Azam, a Bachelor of Computer Science student at DHA Suffa University, passionate about both Web Development and Data Science. This portfolio combines creativity from web development with analytical thinking from Data Science.

🛠️ Tech Stack
Frontend: React 18, TypeScript, Tailwind CSS
Build Tool: Vite
UI Components: Radix UI, shadcn/ui
Icons: Lucide React
Deployment: Vercel/Netlify Ready
📋 Features
✅ Responsive design (mobile-first)
✅ Dark/Light mode support
✅ Smooth scrolling navigation
✅ Interactive project cards
✅ Contact form with validation
✅ SEO optimized
✅ Performance optimized
🎯 Sections
Hero - Introduction with call-to-action buttons
About - Personal introduction and journey
Skills - Web Development & Data Science skills
Projects - Featured projects with live demos
Experience - Work experience and internships
Education - Academic background
Hobbies - Personal interests
Contact - Get in touch form
🚀 Quick Start
Prerequisites
Node.js 18+ and npm
Installation
# Clone the repository
git clone https://github.com/thisisumar/portfolio-website.git

# Navigate to project directory
cd portfolio-website

# Install dependencies
npm install

# Start development server
npm run dev
Scripts
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint         # Run ESLint
📁 Project Structure
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
🎨 Design System
The portfolio uses a custom design system with:

Primary Colors: Bright yellow (#F7DC6F) with teal accents
Typography: Clean, modern font hierarchy
Components: Consistent spacing and styling
Responsive: Mobile-first approach
🔧 Customization
Colors
Update colors in src/index.css:

:root {
  --primary: 48 96% 72%;  /* Bright yellow */
  --secondary: 174 64% 45%; /* Teal */
  /* Add your custom colors */
}
Content
Update personal information in component files:

Contact details in Contact.tsx
Projects in Projects.tsx
Skills in Skills.tsx
📱 Screenshots
Desktop View
Desktop Screenshot

Mobile View
Mobile Screenshot

🌐 Deployment
Vercel (Recommended)
Push code to GitHub
Connect repository to Vercel
Deploy automatically
Netlify
Build the project: npm run build
Upload dist folder to Netlify
GitHub Pages
Install gh-pages: npm install --save-dev gh-pages
Add to package.json:
{
  "homepage": "https://thisisumar.github.io/portfolio-website",
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
  }
}
Deploy: npm run deploy
📊 Performance
⚡ Lighthouse Score: 90+
📱 Mobile Friendly
🚀 Fast Loading
♿ Accessible
📞 Contact
Email: uazam100@gmail.com
GitHub: @thisisumar
LinkedIn: Muhammad Umar Azam
📄 License
This project is open source and available under the MIT License.

🙏 Acknowledgments
Built with Lovable
UI Components by shadcn/ui
Icons by Lucide
⭐ Star this repository if you found it helpful!

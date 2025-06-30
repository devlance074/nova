# NOVA Creative Agency Template

A stunning, modern creative agency website template built with React, TypeScript, and Tailwind CSS. Features smooth animations, responsive design, and a professional aesthetic perfect for creative agencies, design studios, and digital marketing companies.

![NOVA Creative Agency](https://nova-nextgen.netlify.app/)

## ✨ Features

- **Modern Design**: Clean, professional aesthetic with gradient accents and smooth animations
- **Fully Responsive**: Optimized for all devices from mobile to desktop
- **Smooth Animations**: Powered by Framer Motion for engaging user interactions
- **TypeScript**: Full type safety and better development experience
- **Performance Optimized**: Built with Vite for fast development and production builds
- **SEO Ready**: Semantic HTML structure and optimized meta tags
- **Accessible**: WCAG compliant with proper ARIA labels and keyboard navigation

## 🚀 Quick Start

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <https://github.com/devlance074/nova.git>
   cd nova-creative-agency
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to see your site

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality

## 📁 Project Structure

```
src/
├── components/          # React components
│   ├── Navbar.tsx      # Navigation component
│   ├── Hero.tsx        # Hero section
│   ├── Services.tsx    # Services showcase
│   ├── Work.tsx        # Portfolio/work section
│   └── Contact.tsx     # Contact form
├── App.tsx             # Main app component
├── main.tsx           # App entry point
├── index.css          # Global styles and Tailwind imports
└── vite-env.d.ts      # Vite type definitions
```

## 🎨 Customization Guide

### Colors and Branding

The template uses a gradient color scheme that can be easily customized:

1. **Primary Gradients**: Update the gradient classes in components
   - `from-purple-600 to-pink-600` - Main brand gradient
   - `from-purple-400 to-pink-600` - Text gradient
   - Modify these in `tailwind.config.js` for global changes

2. **Brand Name**: Change "NOVA" in `src/components/Navbar.tsx`

### Content Customization

#### Hero Section (`src/components/Hero.tsx`)
- Update the main headline and description
- Replace the background image URL
- Modify the call-to-action button text

#### Services Section (`src/components/Services.tsx`)
- Edit the `services` array to match your offerings
- Update service titles, descriptions, and icons
- Customize gradient colors for each service

#### Work/Portfolio Section (`src/components/Work.tsx`)
- Replace the `projects` array with your actual work
- Update project images, titles, and categories
- Modify the masonry layout if needed

#### Contact Section (`src/components/Contact.tsx`)
- Customize form fields as needed
- Add form submission handling
- Update contact information

### Styling

The template uses Tailwind CSS for styling:

- **Global styles**: `src/index.css`
- **Component styles**: Inline Tailwind classes
- **Custom utilities**: Defined in `src/index.css`

### Images

All images are sourced from Unsplash with proper URLs. To use your own images:

1. Replace Unsplash URLs with your image URLs
2. Ensure images are optimized for web (WebP format recommended)
3. Use appropriate alt text for accessibility

## 🔧 Technical Details

### Built With

- **React 18** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Animation library
- **Lucide React** - Icon library
- **React Intersection Observer** - Scroll-triggered animations

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

### Performance

- Lighthouse Score: 95+ (Performance, Accessibility, Best Practices, SEO)
- Core Web Vitals optimized
- Lazy loading for images
- Optimized bundle size

## 📱 Responsive Design

The template is fully responsive with breakpoints:

- **Mobile**: 320px - 768px
- **Tablet**: 768px - 1024px
- **Desktop**: 1024px+

## 🚀 Deployment

### Netlify (Recommended)

1. Build the project: `npm run build`
2. Deploy the `dist` folder to Netlify
3. Configure custom domain if needed

### Vercel

1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect Vite and deploy

### Other Platforms

The template generates static files that can be deployed to any static hosting service:
- GitHub Pages
- AWS S3
- Firebase Hosting
- Surge.sh

## 🔒 Environment Variables

Currently, no environment variables are required. If you add features like:
- Contact form submission
- Analytics
- CMS integration

Create a `.env` file in the root directory and add your variables.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see below for details:

### MIT License

Copyright (c) 2024 NOVA Creative Agency Template

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## 🙏 Acknowledgments

- **Unsplash** - For providing high-quality stock photos
- **Lucide** - For the beautiful icon set
- **Framer Motion** - For smooth animations
- **Tailwind CSS** - For the utility-first CSS framework

## 📞 Support

If you encounter any issues or have questions:

1. Check the [https://github.com/devlance074/nova.git/issues) section
2. Create a new issue with detailed information
3. Include your environment details and steps to reproduce

## 🔄 Updates

This template is actively maintained. Check for updates regularly:

```bash
git pull origin main
npm install
```

---

*Happy coding! 🚀*

*Made with ❤ by DevLance for the developer community*


*Transform your digital presence with NOVA - where creativity meets technology.*
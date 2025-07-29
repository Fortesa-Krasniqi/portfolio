# Modern Portfolio Website

A beautiful, responsive portfolio website built with React, TypeScript, and Framer Motion. Features smooth animations, dark mode support, and a modern design.

## 🚀 Features

- **Modern Design**: Clean, professional design with smooth animations
- **Responsive**: Fully responsive across all devices
- **Dark Mode**: Toggle between light and dark themes
- **Smooth Animations**: Powered by Framer Motion for fluid interactions
- **TypeScript**: Full type safety and better development experience
- **Tailwind CSS**: Utility-first CSS framework for rapid styling
- **React Router**: Client-side routing for seamless navigation
- **Lucide Icons**: Beautiful, customizable icons

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Routing**: React Router DOM
- **Icons**: Lucide React
- **Build Tool**: Create React App

## 📦 Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## 🎨 Customization

### Personal Information
Update the following files with your information:

- **Navbar**: `src/components/Navbar.tsx` - Update logo and navigation
- **Home**: `src/pages/Home.tsx` - Update hero content and social links
- **About**: `src/pages/About.tsx` - Update personal story, skills, and experience
- **Projects**: `src/pages/Projects.tsx` - Add your projects
- **Contact**: `src/pages/Contact.tsx` - Update contact information
- **Footer**: `src/components/Footer.tsx` - Update social links

### Styling
- **Colors**: Update the color scheme in `tailwind.config.js`
- **Fonts**: Modify font families in `src/index.css`
- **Animations**: Customize Framer Motion animations in components

### Content
- Replace placeholder images with your own
- Update project descriptions and links
- Add your real contact information
- Customize the about section with your story

## 📁 Project Structure

```
src/
├── components/          # Reusable components
│   ├── Navbar.tsx      # Navigation component
│   └── Footer.tsx      # Footer component
├── pages/              # Page components
│   ├── Home.tsx        # Home page
│   ├── About.tsx       # About page
│   ├── Projects.tsx    # Projects page
│   └── Contact.tsx     # Contact page
├── App.tsx             # Main app component
├── index.tsx           # Entry point
└── index.css           # Global styles
```

## 🎯 Available Scripts

- `npm start` - Runs the app in development mode
- `npm run build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm run eject` - Ejects from Create React App (one-way operation)

## 🌟 Key Features Explained

### Smooth Animations
The portfolio uses Framer Motion for:
- Page transitions
- Scroll-triggered animations
- Hover effects
- Loading animations

### Dark Mode
- Automatic theme detection
- Manual toggle in navbar
- Persistent theme preference
- Smooth theme transitions

### Responsive Design
- Mobile-first approach
- Breakpoint-specific layouts
- Touch-friendly interactions
- Optimized for all screen sizes

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Deploy to Netlify
1. Push your code to GitHub
2. Connect your repository to Netlify
3. Set build command: `npm run build`
4. Set publish directory: `build`

### Deploy to Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

If you have any questions or need help, feel free to reach out!

---

Made with ❤️ using React, TypeScript, and Framer Motion

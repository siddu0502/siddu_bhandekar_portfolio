# Siddartha Bhandekar Portfolio

A modern, responsive portfolio website built with React and Tailwind CSS.

## 🚀 Features
- Responsive design for all devices
- Smooth animations with Framer Motion
- Contact form with EmailJS integration
- Modern UI with Tailwind CSS
- React Router for navigation

## 🛠️ Technologies Used
- **React** - Frontend framework
- **Tailwind CSS** - Styling
- **Framer Motion** - Animations
- **EmailJS** - Contact form functionality
- **React Router** - Navigation

## 📦 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone [your-repo-url]
   cd siddu-bhandekar-portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 🚀 Deployment

### Deploy to GitHub Pages
1. Install gh-pages:
   ```bash
   npm install --save-dev gh-pages
   ```

2. Add to package.json:
   ```json
   "homepage": "https://[your-username].github.io/siddu-bhandekar-portfolio",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d build"
   }
   ```

3. Deploy:
   ```bash
   npm run deploy
   ```

### Deploy to Netlify/Vercel
1. Build the project:
   ```bash
   npm run build
   ```

2. Drag and drop the `build` folder to Netlify/Vercel

## 📁 Project Structure
```
siddu-bhandekar-portfolio/
├── public/
│   ├── index.html
│   ├── resume.txt
│   └── ...
├── src/
│   ├── components/
│   │   ├── Navbar.js
│   │   └── Footer.js
│   ├── pages/
│   │   ├── Home.js
│   │   ├── About.js
│   │   ├── Projects.js
│   │   ├── Skills.js
│   │   ├── Education.js
│   │   ├── Internships.js
│   │   ├── Achievements.js
│   │   ├── Courses.js
│   │   └── Contact.js
│   ├── App.js
│   ├── index.js
│   └── index.css
├── package.json
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

## 🎯 Usage
- **Development**: `npm start`
- **Production Build**: `npm run build`
- **Test**: `npm test`

## 📞 Contact
- **Email**: [your-email@domain.com]
- **LinkedIn**: [your-linkedin-url]
- **GitHub**: [your-github-url]

## 📄 License
This project is open source and available under the [MIT License](LICENSE).

# K72.ca Clone

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)

A modern, animated portfolio website clone built with React and GSAP, featuring complex responsive layouts and buttery-smooth 60fps animations.

## 📸 Screenshots
> 
> ### Hero Section
> ![Mobile Responsive](https://github.com/user-attachments/assets/5575b641-cb4f-4deb-8ae2-4f3a1a5cedc4)
> 
> ### Project Section
> ![Mobile Responsive](https://github.com/user-attachments/assets/f765383f-a26f-463c-8851-23e50b9d1521)
> 
> ### Menu Bar
> ![Animation Demo](https://github.com/user-attachments/assets/b80fdccb-faee-49c5-a190-ccd5bf255410)

## ✨ Features

- **Smooth Animations**: Leveraging GSAP for performant, hardware-accelerated animations at 60fps
- **Responsive Design**: Mobile-first approach with complex layouts that adapt beautifully across all devices
- **Modern React Patterns**: Component-based architecture with hooks and functional components
- **Page Transitions**: Seamless navigation experience with React Router and animated transitions
- **Performance Optimized**: Efficient rendering and animation techniques for smooth user experience

## 🛠️ Tech Stack

- **Frontend Framework**: React 18+
- **Styling**: Tailwind CSS
- **Animations**: GSAP (GreenSock Animation Platform)
- **Routing**: React Router v6
- **Build Tool**: Vite (or Create React App)
- **Package Manager**: npm/yarn

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/k72-clone.git
cd k72-clone
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Start the development server
```bash
npm run dev
# or
yarn dev
```

4. Open your browser and visit `http://localhost:5173` (or the port shown in your terminal)

### Build for Production

```bash
npm run build
# or
yarn build
```

The optimized production build will be in the `dist` folder.

## 📁 Project Structure

```
k72-clone/
├── public/
│   └── assets/
├── src/
│   ├── components/
│   │   ├── Header/
│   │   ├── Hero/
│   │   ├── About/
│   │   └── ...
│   ├── pages/
│   ├── hooks/
│   ├── utils/
│   ├── App.jsx
│   └── main.jsx
├── package.json
└── README.md
```

## 💡 Key Learnings

### GSAP Implementation
This was my first project using GSAP, and the difference compared to CSS animations is remarkable:
- **Performance**: Hardware-accelerated transforms running at consistent 60fps
- **Control**: Timeline-based animations with precise sequencing
- **ScrollTrigger**: Scroll-based animations that feel native and responsive

### Complex Layouts
Tackled advanced responsive layouts including:
- CSS Grid and Flexbox combinations
- Dynamic component positioning
- Breakpoint management with Tailwind
- Mobile-first responsive design patterns

### React Architecture
- Custom hooks for animation logic
- Component composition patterns
- State management for UI interactions
- Optimized re-rendering strategies

## 🎯 Challenges & Solutions

### Challenge 1: Animation Performance
**Problem**: Initial CSS transitions felt janky and couldn't handle complex sequences.

**Solution**: Implemented GSAP with Timeline animations and ScrollTrigger for smooth, choreographed effects.

### Challenge 2: Responsive Complex Layouts
**Problem**: Maintaining layout integrity across different screen sizes with animations.

**Solution**: Used Tailwind's responsive utilities combined with GSAP's matchMedia to adapt animations per breakpoint.

### Challenge 3: Page Transition Performance
**Problem**: React Router navigation caused abrupt content changes.

**Solution**: Created custom transition components using GSAP's timeline to orchestrate exit and enter animations.

## 🔮 Future Enhancements

- [ ] Deploy to Vercel/Netlify
- [ ] Add dark mode toggle
- [ ] Implement lazy loading for images
- [ ] Add more micro-interactions
- [ ] Create additional page templates
- [ ] Add unit tests
- [ ] Optimize bundle size
- [ ] Add accessibility improvements (ARIA labels, keyboard navigation)

## 📚 Resources & Inspiration

- [Original K72.ca](https://k72.ca) - Original design inspiration
- [GSAP Documentation](https://greensock.com/docs/) - Animation library docs
- [React Documentation](https://react.dev/) - React best practices
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework

## 🤝 Contributing

This is a personal learning project, but suggestions and feedback are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Your Name**
- GitHub: [Partha06](https://github.com/Partha06)
- LinkedIn: [Your LinkedIn](www.linkedin.com/in/partha-biswass)

## 🙏 Acknowledgments

- K72.ca for the original design inspiration
- GreenSock (GSAP) team for an incredible animation library
- React and Tailwind CSS communities for excellent documentation

---

⭐ **If you found this project interesting, please consider giving it a star!**

💬 **Questions or suggestions? Open an issue or reach out!**

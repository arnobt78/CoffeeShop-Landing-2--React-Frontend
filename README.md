
# Coffee Shop 2 Landing Page - React, Vite, TailwindCSS Frontend Project

A modern, responsive coffee shop landing page built with React, Vite, and Tailwind CSS. This project demonstrates best practices in React component structure, animation, and UI/UX, making it a great template for learning, customization, and real-world use.

- **Live Demo:** [https://coffeelover-cafe.netlify.app/](https://coffeelover-cafe.netlify.app/)

*Note: View my Coffee Shop 1 template for another showcase of my design and development skills:*

- **Live Demo:** [https://coffeeshop-arnob.vercel.app/](https://coffeeshop-arnob.vercel.app/)
- **GitHub Repo:** [https://github.com/arnobt78/CoffeeShop-1--TailwindCSS-Fundamental-Project-7](https://github.com/arnobt78/CoffeeShop-1--TailwindCSS-Fundamental-Project-7)

![Screenshot 2025-07-28 at 00 31 25](https://github.com/user-attachments/assets/fb885ac2-9e72-4630-a2f9-8e7e1dd526d6)
![Screenshot 2025-07-28 at 00 32 10](https://github.com/user-attachments/assets/7775e932-35b6-4912-a5e9-46ec7bde2f52)
![Screenshot 2025-07-28 at 00 32 32](https://github.com/user-attachments/assets/a4d2ebc3-abc2-433a-aa57-080d53d7ed8f)
![Screenshot 2025-07-28 at 00 33 23](https://github.com/user-attachments/assets/05d561da-f8d3-4011-85f0-90c7014ee965)

## Table of Contents

- [Project Summary](#project-summary)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Component Walkthrough](#component-walkthrough)
- [How to Run](#how-to-run)
- [How to Reuse Components](#how-to-reuse-components)
- [Customization & Theming](#customization--theming)
- [Keywords](#keywords)
- [Conclusion](#conclusion)

---

## Project Summary

Coffee Cafe is a visually appealing, single-page web app for a coffee shop. It features animated sections, a mobile-friendly layout, and reusable React components. The project is ideal for learning modern frontend development, rapid prototyping, or as a starting point for your own business site.

---

## Features

- ⚡️ Fast development with Vite
- 🎨 Styled with Tailwind CSS and custom fonts
- 🌙 Dark mode support
- ✨ Smooth animations using AOS (Animate On Scroll)
- 📱 Responsive design for all devices
- 🧩 Modular, reusable React components
- 🏪 App store/Play store promo section
- ⭐️ Testimonials slider
- 📚 Clean, well-commented code

---

## Tech Stack

- **React** (18+)
- **Vite** (for fast dev/build)
- **Tailwind CSS** (utility-first styling)
- **AOS** (scroll animations)
- **React Slick** (testimonials slider)
- **React Icons** (iconography)
- **PostCSS** (with autoprefixer)
- **ESLint** (code linting)

---

## Project Structure

```bash
coffee-cafe-main/
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
├── public/
│   └── vite.svg
├── src/
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   ├── assets/
│   │   └── ... (images, logos)
│   └── components/
│       ├── AppStore/
│       ├── Banner/
│       ├── Footer/
│       ├── Hero/
│       ├── Navbar/
│       ├── Services/
│       └── Testimonials/
└── README.md
```

---

## Component Walkthrough

### `Navbar`

- Displays logo and navigation links.
- Uses Tailwind for layout and style.
- Responsive and animated on scroll.

### `Hero`

- Main landing section with headline, call-to-action, and hero image.
- Uses AOS for entrance animations.

### `Services`

- Showcases coffee types/services in cards.
- Data-driven: easily add new services.
- Animated cards with hover effects.

### `Banner`

- About/promo section with background image and feature highlights.

### `AppStore`

- Promotes mobile app availability.
- Includes Play Store and App Store badges.

### `Testimonials`

- Carousel/slider of customer reviews.
- Uses `react-slick` for smooth sliding.

### `Footer`

- Social links, navigation, and background image.
- Responsive and styled for dark/light modes.

---

## How to Run

1. **Install dependencies:**

   ```bash
   npm install
   ```

2. **Start the development server:**

   ```bash
   npm run dev
   ```

3. **Open your browser:**  
   Visit the local URL shown in the terminal (usually <http://localhost:5173>).

4. **Build for production:**

   ```sh
   npm run build
   ```

---

## How to Reuse Components

Each component is self-contained and can be imported into other React projects:

```jsx
import Hero from './components/Hero/Hero';
import Services from './components/Services/Services';
// ...etc
```

- **Props:** Most components are data-driven. For example, to add a new service, edit the `ServicesData` array in `Services.jsx`.
- **Styling:** All styles use Tailwind CSS classes, so you can easily adjust themes via `tailwind.config.js`.
- **Assets:** Place your images in `src/assets/` and update import paths as needed.

---

## Customization & Theming

- **Colors & Fonts:** Edit `tailwind.config.js` to change primary/secondary colors or font families.
- **Animations:** Adjust AOS settings in `App.jsx` or per component.
- **Dark Mode:** Toggle dark mode by adding/removing the `dark` class on the `<body>` or root div.

---

## Keywords

React, Vite, Tailwind CSS, Coffee Shop, Landing Page, AOS, Animation, Responsive, Component, UI, Template, Modern, App Store, Testimonials, Slider, Dark Mode, Web Development, Frontend, JavaScript, Learning, Boilerplate

---

## Conclusion

This project is a great starting point for modern web development with React and Vite. Explore the code, customize the UI, and use the components in your own projects. Contributions and feedback are welcome!

---

Happy coding! ☕️

Thank you!

---

# Warren Bill: Personal Portfolio

An interactive personal portfolio built with **React**, **Three.js**, and **Vite**, showcasing work experience, projects, and contact info with 3D animations and smooth transitions.

![Image](https://github.com/WarrenBillTT/Portfolio-V1/blob/main/portfolio.png)

🔗 **Live Demo:** Coming soon

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?logo=vite&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-0.180-black?logo=three.js)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-38BDF8?logo=tailwindcss&logoColor=white)

---

## About the Project

This website is a personal portfolio featuring:
- An interactive **Hero Section** with a 3D model and parallax effects using `react-three-fiber` and `drei`
- An **About Me** section with animated cards (design principles, tech stack, etc.)
- A **Projects** showcase with descriptions and tech stack for each project
- An **Experience** section listing work history
- A **Contact** area with a copy-email button and links to social media (LinkedIn, Instagram, GitHub, LeetCode)
- An interactive globe built with **cobe**
- Smooth animations powered by **motion (Framer Motion)**

## Tech Stack

| Category | Technology |
|---|---|
| Frontend | React 19, Vite 7 |
| Styling | Tailwind CSS 4 |
| 3D / Graphics | Three.js, @react-three/fiber, @react-three/drei, maath |
| Animation | Motion (Framer Motion) |
| Globe | Cobe |
| Utilities | react-responsive, tailwind-merge |
| Linting | ESLint |

## Project Structure

```
Portofolio-V1/
├── public/
│   ├── assets/          # Images, logos, social media icons
│   └── models/          # 3D models
├── src/
│   ├── components/      # Reusable components (Card, Globe, Loader, etc.)
│   ├── constants/        # Static data (projects, socials, experiences)
│   ├── sections/         # Page sections (Hero, About, Projects, Footer, etc.)
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── vite.config.js
├── tailwind.config.js
└── package.json
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/WarrenBillTT/Portofolio-V1.git
   cd Portofolio-V1
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:5173](http://localhost:5173) in your browser.

4. **Build for production**
   ```bash
   npm run build
   ```

5. **Preview the production build**
   ```bash
   npm run preview
   ```

## Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Starts the development server with HMR |
| `npm run build` | Builds the project for production |
| `npm run lint` | Runs ESLint |
| `npm run preview` | Previews the production build locally |

## License

This project was built for personal use. Feel free to use it as a reference, but please don't copy it identically for your own portfolio.

# Winz Infotech - Frontend

Official frontend web application for **Winz Infotech**, built with **React 19**, **Vite**, and **Tailwind CSS**.

---

## 🚀 Tech Stack

- **Framework & Build Tool:** [React 19](https://react.dev/), [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Animations:** [Framer Motion](https://www.framer.com/motion/), [GSAP](https://gsap.com/)
- **Routing:** [React Router v7](https://reactrouter.com/)
- **Smooth Scrolling:** [@studio-freight/lenis](https://lenis.darkroom.engineering/)
- **Carousel & Sliders:** [Swiper](https://swiperjs.com/)
- **Icons:** [Lucide React](https://lucide.dev/), [React Icons](https://react-icons.github.io/react-icons/)
- **Integrations:** [EmailJS](https://www.emailjs.com/), [React Calendly](https://github.com/tcampb/react-calendly), [Cloudinary](https://cloudinary.com/)
- **SEO & Analytics:** React Helmet, Google Analytics 4 (`useGA4`)

---

## 📁 Project Structure

```text
├── public/                 # Static assets, images, videos, and icons
├── src/
│   ├── assets/             # Project-specific graphics and fonts
│   ├── components/         # Reusable UI components & animations
│   │   ├── Animations/     # Framer motion & text animations
│   │   └── hook/           # Component sections and interactive hooks
│   ├── pages/              # Top-level route pages (Home, About, Service, Portfolio, etc.)
│   ├── utils/              # Helper utilities (GA4, custom helpers)
│   ├── App.jsx             # Main router configuration & layout
│   ├── index.css           # Global stylesheets & font declarations
│   └── main.jsx            # Entry point
├── index.html              # HTML template
├── package.json            # Project dependencies and npm scripts
├── vercel.json             # Vercel deployment configuration
└── vite.config.js          # Vite build configuration
```

---

## 🛠️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/KrishnaKausikBarik/WinzInfotech.git
cd WinzInfotech
npm install
```

### Development Server

Run the development server locally:

```bash
npm run dev
```

The application will start at `http://localhost:5173`.

### Production Build

Create an optimized production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

---

## 🚀 Deployment

The project is preconfigured for deployment on **[Vercel](https://vercel.com/)** using the included `vercel.json` routing configuration:

```bash
# Deploy to Vercel
npx vercel --prod
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

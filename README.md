# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh



# My_Portfolio2025
 MY portfolio 2025

 # create a React file (project)
step1-> npm create vite@latest hjk-portfolio
# After install the file in React Framework then follow the steps.
cd hjk-portfolio
  npm install
  npm run dev
# install tailwindcss 
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
# Open tailwind.config.ja 
Replace 
content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],  
  from content: [], // rempve content:[] 
  # Open index.css paste this
  before paste this remove every thing
  @tailwind base;
@tailwind components;
@tailwind utilities;

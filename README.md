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

# Fonts 
fonts.google.com
search font style  in this project this font is use  (josefin sans & Roboto)     https://fonts.google.com/
click Get Font
click get embed code 
select @import or linkl  we use @import 
open index.css paste on top

@import url('https://fonts.googleapis.com/css2?family=Cormorant:ital,wght@0,300..700;1,300..700&family=Ubuntu:wght@700&display=swap');

# open tailwind.config.js
paste this 
 fontFamily:{
      body: ['Josefin Sans'],
      special:['Roboto'],
    }

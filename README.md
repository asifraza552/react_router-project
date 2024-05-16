# my name is asif raza 
# contact 0305 2226380
# react_router-project

is paroject may react router ka use kiya hay 
is may vite + taillwind-css + react-router-dom ka use keya hay

# paroject installation comand

(1) npm create vite@latest my-project -- --template react
cd my-project
(2) npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
(3) 
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
(4)
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
(5)
@tailwind base;
@tailwind components;
@tailwind utilities;
(6)
npm i react-router-dom
(7)
npm run dev

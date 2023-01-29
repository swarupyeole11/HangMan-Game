# HangMan-Game

## The way to set up tailwind css in the Project is: 
           
           1)npm install -D tailwindcss postcss autoprefixer
        
           2)npx tailwindcss init -p

           3) module.exports = {
              content:["./src/**/*.{js,jsx}","./index.html"],
              theme: {
              extend: {},
               },
              plugins: [],
              }

           4) Add this to the css file and import it into the App.jsx 
              @tailwind base;
              @tailwind components;
              @tailwind utilities;

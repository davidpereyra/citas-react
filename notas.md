run project
npm run dev

install
 npm i -D tailwind css postcss autoprefixer
 npm install -D tailwindcss postcss autoprefixer
 
npm install -D tailwindcss

iniciar tailwind
npx tailwindcss init -p

en tailwind.config.cjs agregar los archivos que van a usar la libreria
  module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
}


para build
cambiar
  content: ["./index.html", "./src/**/*.jsx"],
a
  content: ["index.html", "./src/**/*.jsx"],
en tailwind.config
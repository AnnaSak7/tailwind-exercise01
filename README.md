# learning tailwind. code along.

### NOTE:


- npm init 
- npm install tailwindcss 

- mkdir src 

- in src/css file add
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

<!-- - mkdir public

- add in package.json 
      "scripts": {
    "build-css": "tailwindcss build src/styles.css -o public/style.css"
  },
- npm run build-css -->

- npx tailwindcss -i ./src/styles.css -o ./dist/styles.css --watch

- npx tailwindcss init --full
- npx tailwindxcss init (gives blanc config file)
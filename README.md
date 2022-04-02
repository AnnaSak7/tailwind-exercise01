# learning tailwind. code along.

### NOTE:

- npm install tailwindcss

- mkdir src / touch src
- mkdir public

- in css file add
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

- add in package.json 
      "scripts": {
    "build-css": "tailwindcss build src/styles.css -o public/style.css"
  },
- npm run build-css



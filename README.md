# Netflix GPT

- Create React App
- Configure Css
  npm install -D tailwindcss
  npx tailwindcss init

  - tailwind.config.css

    /** @type {import('tailwindcss').Config} \*/
    module.exports = {
    content: [
    "./src/**/\*.{js,jsx,ts,tsx}",
    ],
    theme: {
    extend: {},
    },
    plugins: [],
    }

  - index.css

    @tailwind base;
    @tailwind components;
    @tailwind utilities;

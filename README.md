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

- Imported React Routing
  - npm i -D react-router-dom
- Header
- Login Form
- Sign Up Form

# Features

- Login/Sign Up
  - Sign In/Sign Up Form
  - Redirect to Browse Page
- Browse (After Authentication)
  - Header
  - Trailer In BackGround
  - Title & Description
  - Movies Suggestions
    - MoviesLists \* N
- Netflix GPT
  - Search Bar
  - Movie Suggestions

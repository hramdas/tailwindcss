```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

* Add the paths to all of your template files in your tailwind.config.js file.
 ```
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
 ```

 * Add the Tailwind directives to your CSS
 ```
@tailwind base;
@tailwind components;
@tailwind utilities;
 ```
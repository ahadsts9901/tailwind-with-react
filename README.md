# Create a react app

## Run these commands in the root directory
    npm install -D tailwindcss

    npx tailwindcss init

## In your "App.css" paste this code
    @tailwind base;

    @tailwind components;

    @tailwind utilities;

## Run this command in src folder
    npx tailwindcss -i ./src/App.css -o ./src/tailwind.css --watch

## Paste this code in your:  
### tailwind.config.js ====> line number 3
    content: ["./src/*.jsx", "./src/components/*.jsx", "./src/pages/*.jsx", "./*.html"],

## Import tailwind.css file in your files and use
    import "./tailwind.css"

### Now your project is ready to use Tailwindcss. Install the Tailwindcss extension for suggestion.

### Don't forget to ⭐ this repo
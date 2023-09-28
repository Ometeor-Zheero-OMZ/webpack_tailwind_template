# This is the tailwind css template with webpack 
First things first you have to install node module before using the project.
hit this command in your command prompt or terminal "npm i -y" so that node modules will be steadily downloaded.

Once you code html and css, and so on, hit this command to see how your website works "npm run dev"

You are able to set your own custom css like darkBlue in tailwind.config.js: 

`/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./dist/*.{html, js}"],
  theme: {
    extend: {
      colors: {
        cyan: "hsl(180, 66%, 49%)",
        cyanLight: "hsl(180, 66%, 69%)",
        darkViolet: "hsl(257, 27%, 26%)",
        red: "hsl(0, 87%, 67%)",
        grayishViolet: "hsl(257, 7%, 63%)",
        veryDarkBlue: "hsl(255, 11%, 22%)",
        veryDarkViolet: "hsl(260, 8%, 14%)",
      },
      fontFamily: {
        sans: ["Poppins", "sans-serif"],
      },
      spacing: {
        180: "32rem",
      },
    },
  },
  plugins: [],
};`

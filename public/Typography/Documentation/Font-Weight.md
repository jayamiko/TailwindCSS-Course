# TYPOGRAPHY TAILWINDCSS

## Font Weight TailwindCSS

```css
font-thin	//font-weight: 100;
font-extralight	//font-weight: 200;
font-light	//font-weight: 300;
font-normal	//font-weight: 400;
font-medium	//font-weight: 500;
font-semibold	//font-weight: 600;
font-bold	//font-weight: 700;
font-extrabold	//font-weight: 800;
font-black	//font-weight: 900;
```

## Configurasi Custom

Setting file tailwind.config.js

```js
module.exports = {
  theme: {
    fontWeight: {
      hairline: 100,
      "extra-light": 100,
      thin: 200,
      light: 300,
      normal: 400,
      medium: 500,
      semibold: 600,
      bold: 700,
      extrabold: 800,
      "extra-bold": 800,
      black: 900,
    },
  },
};
```

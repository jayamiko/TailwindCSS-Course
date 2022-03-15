# TYPOGRAPHY TAILWINDCSS

## Letter Spacing TailwindCSS

```css
tracking-tighter //letter-spacing: -0.05em;
tracking-tight	//letter-spacing: -0.025em;
tracking-normal	//letter-spacing: 0em;
tracking-wide	//letter-spacing: 0.025em;
tracking-wider	//letter-spacing: 0.05em;
tracking-widest	//letter-spacing: 0.1em;
```

## Configurasi Custom

Setting file tailwind.config.js

```js
module.exports = {
  theme: {
    letterSpacing: {
      tightest: "-.075em",
      tighter: "-.05em",
      tight: "-.025em",
      normal: "0",
      wide: ".025em",
      wider: ".05em",
      widest: ".1em",
      widest: ".25em",
    },
  },
};
```

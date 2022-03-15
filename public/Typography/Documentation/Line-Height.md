# TYPOGRAPHY TAILWINDCSS

## Line Height TailwindCSS

```css
leading-3	//line-height: .75rem; /* 12px */
leading-4	//line-height: 1rem; /* 16px */
leading-5	//line-height: 1.25rem; /* 20px */
leading-none	//line-height: 1;
leading-tight	//line-height: 1.25;
leading-snug	//line-height: 1.375;
leading-normal	//line-height: 1.5;
leading-relaxed	//line-height: 1.625;
```

## Configurasi Custom

Setting file tailwind.config.js

```js
module.exports = {
  theme: {
    lineHeight: {
      "extra-loose": "2.5",
      12: "3rem",
    },
  },
};
```

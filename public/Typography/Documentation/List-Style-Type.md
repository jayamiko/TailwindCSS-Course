# TYPOGRAPHY TAILWINDCSS

## List Style Position TailwindCSS

```css
list-none	//list-style-type: none;
list-disc	//list-style-type: disc;
list-decimal	//list-style-type: decimal;
```

## Configurasi Custom

Setting file tailwind.config.js

```js
module.exports = {
  theme: {
    listStyleType: {
      none: "none",
      disc: "disc",
      decimal: "decimal",
      square: "square",
      roman: "upper-roman",
    },
  },
};
```

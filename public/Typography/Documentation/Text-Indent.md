# TYPOGRAPHY TAILWINDCSS

## Text Indent (Paragraph) TailwindCSS

```css
indent-0	//text-indent: 0px;
indent-px	//text-indent: 1px;
indent-0.5	//text-indent: 0.125rem; /* 2px */
indent-1	//text-indent: 0.25rem; /* 4px */
indent-1.5	//text-indent: 0.375rem; /* 6px */
...
```

## Configurasi Custom

Setting file tailwind.config.js

```js
module.exports = {
  theme: {
    textIndent: {
      128: "32rem",
    },
  },
};
```

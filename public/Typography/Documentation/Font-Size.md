# TYPOGRAPHY TAILWINDCSS

## Font Size TailwindCSS

```css
text-xs // font-size:0.75rem(12px), line-height:1rem(16px)
text-sm // font-size:0.875rem(14px), line-height:1.25rem(20px)
text-base // font-size:1rem(16px), line-height:1.5rem(24px)
text-lg // font-size:1.125rem(18px), line-height:1.75rem(28px)
text-xl // font-size:1.25rem(20px), line-height:1.75rem(28px)
```

## Configurasi Custom

Setting file tailwind.config.js

```js
module.exports = {
  theme: {
    fontFamily: {
      fontSize: {
        xs: ".75rem",
        sm: ".875rem",
        tiny: ".875rem",
        base: "1rem",
        lg: "1.125rem",
        xl: "1.25rem",
        "2xl": "1.5rem",
        "3xl": "1.875rem",
        "4xl": "2.25rem",
        "5xl": "3rem",
        "6xl": "4rem",
        "7xl": "5rem",
      },
    },
  },
};
```

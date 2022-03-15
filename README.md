# TailwindCSS

Adalah Framework CSS yang mengutamakan utiliyt yang dikemas dengan class seperti "flex, pt-4, text-center" dan "rotate-90" yang dapat disusun untuk membangun desain apapun, langsung dari markup (HTML)

## Install dan Konfigurasi

### Software Requirements

- Web Browser
- Code Editor : Visual Studio Code
- VS Code Extensions :
  - TailwindCSS IntelliSense
  - Live Preview
  - PostCSS Language Support
- Package Manager : NPM (Node.Js)
- Terminal : powershell, cmd, gitbash, dll

### Install TailwindCSS CLI

- Pastikan sudah terinstal Node JS dan Folder untuk project
- Inisialisasi NPM dengan

```sh
npm init
```

- Install TailwindCSS di devDepedencies

```sh
npm i -D tailwindcss
```

(Jika Node Js < versi 16) Instll juga :

```sh
npm i -D postcss autoprefixer
```

- Lalu Inisialisasi TailwindCSS untuk memulai

```sh
npx tailwindcss init
```

- Membuat Folder Public dan src di root project
- Membuat Folder css di dalam folder src (optional)
- Pindahkan index.html kedalam folder public
- Membuat file input.css didalam src/css
- Menambahkan code di file input.css

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

- Run di terminal

```sh
npx tailwindcss -i ./src/css/input.css -o ./public/css/output.css --watch
```

- Daftarkan output.css ke dalam index.html

```html
<link rel="stylesheet" href="css/output.css" />
```

- Membuat shortcut untuk npx tailwindcss... di dalam file package.json

```json
"script":{
    "build-tailwindcss":"npx tailwindcss -i ./src/css/input.css -o ./public/css/output.css --watch"
}
```

- Jika project sudah selesai, bisa meminimize size file output.css dengan cara menjalankan via terminal :

```sh
npx tailwindcss -o ./public/css/final.css --minify
```

- Jangan lupa final.css daftarkan di index.html
- SELESAI

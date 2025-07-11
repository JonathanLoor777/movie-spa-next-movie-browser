# Movie Browser (NextJs)

<div style="text-align: center;">
    <img src="/public/logo.svg" alt="Movie Browser Logo" width="200" />
</div>

## Descripción

**Movie Browser** es una aplicación web diseñada para explorar y buscar información sobre películas. La aplicación está desplegada y accesible en el siguiente enlace: [Movie Browser en Vercel](https://movie-spa-next-movie-browser.vercel.app/).

## Estructura de carpetas
/
├── .env.local
├── .env.local.example
├── .gitignore
├── eslint.config.mjs
├── next-env.d.ts
├── next.config.ts
├── package.json
├── postcss.config.mjs
├── README.md
├── tsconfig.json
├── .next/
├── public/
│   ├── logo.svg
│   └── placeholder.png
├── src/
│   ├── app/
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   ├── movie/
│   │   │   └── [id]/
│   │   │       └── page.tsx
│   ├── components/
│   │   ├── MovieCard.tsx
│   │   └── SearchBar.tsx
│   ├── interfaces/
│   │   └── movie.ts
│   ├── services/
│   │   └── movie.ts
│   └── app/
│       └── globals.css

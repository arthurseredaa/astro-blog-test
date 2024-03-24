# Basic Astro blog project
- Static generation
- Typescript support
- DOM manipulations for theme and greetings
- Dynamic routing for posts and tags
- Astro islands for interactivity

## 👀 Pages screenshots
![Hello_ world](https://github.com/arthurseredaa/astro-blog-test/assets/55348317/c9070b19-b84c-4a1d-9cee-c9b3edf1acaf)
![Blog](https://github.com/arthurseredaa/astro-blog-test/assets/55348317/f23f9e60-34d8-4830-90c7-bc01c4cc7e55)
![Blog page](https://github.com/arthurseredaa/astro-blog-test/assets/55348317/7f4f28bf-07c0-4463-816c-de84f523fa66)
![About Me](https://github.com/arthurseredaa/astro-blog-test/assets/55348317/eabb9121-b148-43b3-8430-ab66f008061b)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

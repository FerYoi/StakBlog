# Next js Blog Boilerplate with Tailwind CSS 
### Features

Blog feature:

- 🎈 Syntax Highlighting with Prism.js
- 🤖 SEO metadata and Open Graph tags
- ⚙️ JSON-LD for richer indexing
- 📖 Pagination
- 🌈 Include a FREE minimalist blog theme
- ⬇️ Markdown
- 💯 Maximize lighthouse score

Developer experience first:

- 🔥 [Next.js](https://nextjs.org) for Static Site Generator
- 🎨 Integrate with [Tailwind CSS](https://tailwindcss.com)
- 💅 [PostCSS](https://postcss.org) for processing [Tailwind CSS](https://tailwindcss.com)
- 🎉 Type checking [TypeScript](https://www.typescriptlang.org)
- ✏️ Linter with [ESLint](https://eslint.org)
- 🛠 Code Formatter with [Prettier](https://prettier.io)
- 🦊 SEO metadata, [JSON-LD](https://developers.google.com/search/docs/guides/intro-structured-data) and [Open Graph](https://ogp.me/) tags with [Next SEO](https://github.com/garmeeh/next-seo)
- ⚙️ [Bundler Analyzer](https://www.npmjs.com/package/@next/bundle-analyzer)

Built-in feature from Next.js:

- ☕ Minify HTML & CSS
- 💨 Live reload
- ✅ Cache busting

### Philosophy

- Minimal code
- SEO-friendly
- 🚀 Production-ready

### Requirements

- Node.js and npm

### Nextless.js SaaS Boilerplate

### Premium Themes

### Getting started

Run the following command on your local environment:

```
git clone --depth=1 https://github.com/FerYoi/StakBlog.git my-project-name
cd my-project-name
npm install
```

Then, you can run locally in development mode with live reload:

```
npm run dev
```

Open http://localhost:3000 with your favorite browser to see your project.

```
.
├── _posts            # Your blog posts
├── public            # Static files
│   ├── assets
│   │   └── images
│   │       └── posts # Images used in your blog posts
└── src
    ├── pages         # Next.js pages
    ├── styles        # Your blog CSS files
    └── templates     # Blog templates
```

### Customization

You can easily configure Next js Boilerplate. Please change the following file:

- `public/apple-touch-icon.png`, `public/favicon.ico`, `public/favicon-16x16.png` and `public/favicon-32x32.png`: your blog favicon, you can generate from https://favicon.io/favicon-converter/
- `public/assets/images/logo.png`, `public/assets/images/logo-32x32.png`: your blog logo
- `src/styles/main.css`: your blog CSS file using Tailwind CSS
- `src/utils/Config.ts`: configuration file like blog name, url, etc.
- `src/templates/Main.tsx`: blog theme

### Deploy to production

You can see the results locally in production mode with:

```
$ npm run build
$ npm run start
```

The generated HTML and CSS files are minified (built-in feature from Next js). It will also removed unused CSS from [Tailwind CSS](https://tailwindcss.com).

You can create an optimized production build with:

```
npm run build-prod
```
### License

Licensed under Hertec, Copyright © 2022
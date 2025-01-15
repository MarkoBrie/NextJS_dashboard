Next.js dashboard

  pnpm run dev
    Starts the development server.

  pnpm run build
    Builds the app for production.

  pnpm start
    Runs the built app in production mode.

You can begin by typing:

  cd nextjs-dashboard
  pnpm run dev

**Project folder structure**
```
├── app
│   ├── lib
│   └── ui
├── public
├── next.config.ts
```

- /app: Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.
- /app/lib: Contains functions used in your application, such as reusable utility functions and data fetching functions.
- /app/ui: Contains all the UI components for your application, such as cards, tables, and forms. To save time, we've pre-styled these components for you.
- /public: Contains all the static assets for your application, such as images.
- Config Files: You'll also notice config files such as next.config.js at the root of your application. Most of these files are created and pre-configured when you start a new project using create-next-app. You will not need to modify them in this course.



Full project tree
```
├── README.md
├── app
│   ├── layout.tsx
│   ├── lib
│   │   ├── data.ts
│   │   ├── definitions.ts
│   │   ├── placeholder-data.ts
│   │   └── utils.ts
│   ├── page.tsx
│   ├── query
│   │   └── route.ts
│   ├── seed
│   │   └── route.ts
│   └── ui
│       ├── acme-logo.tsx
│       ├── button.tsx
│       ├── customers
│       │   └── table.tsx
│       ├── dashboard
│       │   ├── cards.tsx
│       │   ├── latest-invoices.tsx
│       │   ├── nav-links.tsx
│       │   ├── revenue-chart.tsx
│       │   └── sidenav.tsx
│       ├── global.css
│       ├── invoices
│       │   ├── breadcrumbs.tsx
│       │   ├── buttons.tsx
│       │   ├── create-form.tsx
│       │   ├── edit-form.tsx
│       │   ├── pagination.tsx
│       │   ├── status.tsx
│       │   └── table.tsx
│       ├── login-form.tsx
│       ├── search.tsx
│       └── skeletons.tsx
├── next-env.d.ts
├── next.config.ts
├── node_modules
│   ├── @heroicons
│   │   └── react -> ../.pnpm/@heroicons+react@2.2.0_react@19.0.0/node_modules/@heroicons/react
│   ├── @tailwindcss
│   │   └── forms -> ../.pnpm/@tailwindcss+forms@0.5.9_tailwindcss@3.4.16/node_modules/@tailwindcss/forms
│   ├── @types
│   │   ├── bcrypt -> ../.pnpm/@types+bcrypt@5.0.2/node_modules/@types/bcrypt
│   │   ├── node -> ../.pnpm/@types+node@22.10.1/node_modules/@types/node
│   │   ├── react -> ../.pnpm/@types+react@19.0.0/node_modules/@types/react
│   │   └── react-dom -> ../.pnpm/@types+react-dom@19.0.0/node_modules/@types/react-dom
│   ├── @vercel
│   │   └── postgres -> ../.pnpm/@vercel+postgres@0.10.0_utf-8-validate@6.0.5/node_modules/@vercel/postgres
│   ├── autoprefixer -> .pnpm/autoprefixer@10.4.20_postcss@8.4.49/node_modules/autoprefixer
│   ├── bcrypt -> .pnpm/bcrypt@5.1.1/node_modules/bcrypt
│   ├── clsx -> .pnpm/clsx@2.1.1/node_modules/clsx
│   ├── next -> .pnpm/next@15.0.3_react-dom@19.0.0_react@19.0.0__react@19.0.0/node_modules/next
│   ├── next-auth -> .pnpm/next-auth@5.0.0-beta.19_next@15.0.3_react-dom@19.0.0_react@19.0.0__react@19.0.0__react@19.0.0/node_modules/next-auth
│   ├── postcss -> .pnpm/postcss@8.4.49/node_modules/postcss
│   ├── react -> .pnpm/react@19.0.0/node_modules/react
│   ├── react-dom -> .pnpm/react-dom@19.0.0_react@19.0.0/node_modules/react-dom
│   ├── tailwindcss -> .pnpm/tailwindcss@3.4.16/node_modules/tailwindcss
│   ├── typescript -> .pnpm/typescript@5.7.2/node_modules/typescript
│   ├── use-debounce -> .pnpm/use-debounce@10.0.4_react@19.0.0/node_modules/use-debounce
│   └── zod -> .pnpm/zod@3.23.8/node_modules/zod
├── package.json
├── pnpm-lock.yaml
├── postcss.config.js
├── public
│   ├── customers
│   │   ├── amy-burns.png
│   │   ├── balazs-orban.png
│   │   ├── delba-de-oliveira.png
│   │   ├── evil-rabbit.png
│   │   ├── lee-robinson.png
│   │   └── michael-novotny.png
│   ├── favicon.ico
│   ├── hero-desktop.png
│   ├── hero-mobile.png
│   └── opengraph-image.png
├── tailwind.config.ts
└── tsconfig.json
```
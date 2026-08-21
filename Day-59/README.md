# My App

A minimal, production-ready Next.js (App Router) starter, ready to deploy on Vercel.

## Features

- Next.js 14 App Router
- Custom 404 (`app/not-found.js`) and error boundary (`app/error.js`)
- SEO + social sharing metadata (`app/layout.js`)
- `.env.example` for environment variable setup
- MIT licensed

## 🚀 Local Setup

```bash
git clone https://github.com/yourname/my-app.git
cd my-app
npm install
cp .env.example .env.local
npm run dev
```

Visit http://localhost:3000

## 🛠 Environment Variables

Copy `.env.example` to `.env.local` and fill in real values. Never commit `.env.local`.

## 🌐 Deployment (Vercel)

1. Push this repo to GitHub.
2. Go to https://vercel.com → New Project → Import from GitHub.
3. Select this repo and click Deploy.
4. Add any environment variables from `.env.example` in the Vercel project settings.

Live URL: _add your deployed URL here once live_

## 📄 License

MIT — see [LICENSE](./LICENSE).

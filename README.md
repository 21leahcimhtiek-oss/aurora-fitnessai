# FitMind AI

> Your AI-powered personal trainer

## Features
- Workout generation
- Form analysis tips
- Nutrition tracking
- Progress photos
- Recovery planner

## Stack
- Next.js 14 (App Router) + TypeScript
- Tailwind CSS
- OpenAI GPT-4o-mini
- Stripe Subscriptions
- Vercel deployment

## Quick Start

```bash
npm install
cp .env.example .env.local
# Fill in API keys
npm run dev
```

## Environment Variables
Copy `.env.example` to `.env.local` and configure:
- `NEXT_PUBLIC_APP_NAME`
- `NEXT_PUBLIC_APP_URL`
- `OPENAI_API_KEY`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`
- `STRIPE_PRICE_PRO_MONTHLY`
- `STRIPE_PRICE_PRO_YEARLY`
- `DATABASE_URL`

## Pricing
| Plan | Price |
|------|-------|
| Free | $0/mo |
| Pro  | $12/mo or $99/yr |

## Deployment
1. Push your changes to GitHub.
2. Import the repository into Vercel.
3. Add all variables from `.env.example` in Vercel project settings.
4. Confirm build command is `npm run build`.
5. Deploy and verify application health.

## License
MIT (c) 2026 Aurora Rayes LLC

## Aurora Ecosystem Positioning
This repository is part of the Aurora ecosystem of focused AI products, aligned to shared reliability and product-quality standards.

## No-Key-First Experience
Aurora products prioritize a no-key-first onboarding path so users can start with core functionality before adding external API keys or credentials.


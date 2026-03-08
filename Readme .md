# ATX Fantasy Pro Starter

This is a deployable starter for a real ATX Fantasy product.

## Includes
- Next.js app
- Live odds API route (`/api/odds`)
- Stripe subscription checkout route (`/api/checkout`)
- Supabase SQL schema
- Vercel cron starter
- Original static Safari demo at `/public/demo.html`

## Setup
1. Copy `.env.example` to `.env.local`
2. Add your The Odds API, Supabase, and Stripe keys
3. Run `npm install`
4. Run `npm run dev`
5. Deploy to Vercel

## Notes
- The Odds API supports JSON odds feeds and American odds formatting.
- Supabase Auth and database can power users, picks, and subscriptions.
- Stripe Checkout supports subscription flows.

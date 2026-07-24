# Blue Barn

Customer site for Blue Barn (Campbells Creek, Victoria).

- Live: https://bluebarn.com.au
- Vercel project: `blue-barn` (team: Crypto Coffee's projects)
- Supabase project: `blue-barn` (ref: kzaphelbwfzldfpycibg)

## Status
About ~20% built. Vercel was previously deployed **without Git**. This folder is the local source of truth going forward.

## Owner admin
Sign-in: https://bluebarn.com.au/#/signin  
Password is stored in Supabase function `public.moderator_secret()` (updated Jul 2026).

## Next steps
1. Connect this GitHub repo to the Vercel project
2. Restore / rebuild editable source (React + Vite SPA talking to Supabase)
3. Keep secrets in Supabase + local `.env.local` only

## Working in Cursor
Open this folder only: `C:\Users\Justin\Clients\blue-barn`

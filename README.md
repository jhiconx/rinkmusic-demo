# RinkMusic public demo

All three portals, account concept, Products & pricing, The Glide Lab, and seven HTML guides.

## Run or deploy source
Use Node 22.13+ or 24. Run `npm install`, then `npm run build`. `npm run dev` opens the development server. Import this folder as a Vite project in Vercel; use the included vercel.json.

## Already-built demo
The dist folder contains the complete static build and a static Vercel route configuration. Deploy dist directly with no build step. Do not use its configuration as the source-root configuration.

## Demo boundaries
No login is required to explore. IndexedDB stores sample changes and uploaded audio only in each visitor’s browser; data does not sync across devices and is lost if site storage is cleared. No live sign-up, billing, keytag verification, rink control, or AI provider is connected. Instagram connection is restricted to eligible professional accounts. The assistant uses the same HTML guide content as the help pages.

Store products use direct retailer links. In lib/store-products.ts, affiliateUrl is null until approved affiliate links are supplied. No commissions are currently tracked. Prices on the Products page are the supplied published/local/historical examples, not current checkout quotes.

## Verification
The Vite production build passed. The original hosted implementation passed route, persistence, upload, isolation and guide checks. A browser runtime was unavailable for testing this portable version; its browser-storage flows still need a browser smoke test.

## Deployment status
Vercel project creation returned rinkmusic-demo (prj_znzc0GGhGy7QAxBbgiGXoBG3YgwH). Reading the project in team_7bI17Ow4F7BO57nGnZSDofr9 failed with 403 forbidden. No Vercel deployment was completed.

GRAM Miner — Starter Demo

This is a static Telegram Mini App prototype.
It is a virtual-points game only. Points are stored in the user's browser localStorage:
- they are device-local and can be edited/reset by the user
- they are NOT secure, shared, withdrawable, or cryptocurrency
- do not launch this demo as a real rewards/crypto product

Files:
- index.html
- style.css
- app.js

Next steps:
1. Publish these files on a static HTTPS host such as GitHub Pages.
2. In BotFather, open your bot > Mini Apps and configure the app URL using the published HTTPS URL.
3. Before public launch, add a backend (e.g. Supabase) and verify Telegram WebApp initData on a trusted server. Never trust client-submitted user IDs or balances.
4. Add privacy policy, support/contact details, abuse prevention, and age-appropriate disclosures before wider release.
5. Never put the BotFather token or Supabase service_role key in frontend files.

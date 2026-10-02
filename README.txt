ROYAL SANDBOX ONLINE — CONNECTED PROTOTYPE

Files
- index.html: mobile browser game prototype

Features
- Supabase-backed private room codes
- Shareable ?room=CODE links
- Realtime room updates between two phones
- Two player slots
- Unlimited gold/gems display and all prototype cards unlocked
- Mobile card selection and arena deployment
- Shared synchronized unit placements

Deploy on GitHub Pages
1. Replace the old index.html with this index.html.
2. Commit the change to main.
3. Settings > Pages > Deploy from a branch > main > /(root).
4. Open the GitHub Pages URL.
5. Phone 1 creates a room and shares its link.
6. Phone 2 opens the link and taps Join.

SECURITY
This prototype uses the browser-safe Supabase publishable key.
The current prototype database policies are intentionally permissive.
Do not store passwords, emails, secret keys, or sensitive information in the rooms table.
Before public release, replace the prototype RLS policies with authenticated/room-scoped policies.

NOTE
This is an original browser prototype, not the official Clash Royale client/server.
The current realtime implementation synchronizes room membership and card deployments.
Full authoritative combat simulation, tower damage, win conditions, matchmaking, and anti-cheat
would be subsequent development steps.

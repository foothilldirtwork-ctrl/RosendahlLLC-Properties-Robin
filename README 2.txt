# Batman Rental Balance Ledger

## What is included
- iPhone-friendly Progressive Web App (PWA)
- Works offline after first load
- Properties / tenants / rent status
- One-tap Mark Rent Paid
- Maintenance and urgency tracking
- Accounting / income / expenses / annualized costs
- Security deposit tracking and configurable interest calculation
- JSON backup/restore
- CSV accounting export
- No server or database required for the basic version

## Important
The basic version stores data in the browser on each phone. That means **your iPhone and your manager's iPhone do not automatically share the same data**.

For two phones to use one shared ledger, the next step is adding a cloud database/authentication layer (Supabase or Firebase). Do not put private tenant information into a public shared database without authentication and proper security rules.

## Netlify
1. Log into Netlify.
2. Choose **Add new project / Deploy manually**.
3. Drag the entire contents of this folder into the Netlify deploy area (not the ZIP itself if Netlify asks for a folder).
4. Open the resulting HTTPS site on your iPhone.
5. In Safari tap Share -> Add to Home Screen.
6. Repeat on the manager's iPhone.

## Data safety
Use Dashboard -> Backup regularly. Keep the JSON backup somewhere safe.

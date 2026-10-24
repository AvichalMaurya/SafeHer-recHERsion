# SafeHer-Women Safety Web App

A mobile-friendly safety web app (single `index.html`, no build step, no dependencies).

Features
- Phone number + password login, first-time safety profile
- SOS siren (tap twice) and Silent SOS, with SMS alert to police station and trusted contacts
- Send live location, emergency call list
- Cyber crime complaint (identity theft, privacy breach, online threats, other)
- PIN lock, Quick exit (calculator disguise)
- Fake incoming call, check-in timer, cab safety pack
- Evidence vault (notes and photos with timestamps)
- Help directory (helplines, legal aid, counselling)

## Limitations (prototype)
- Data is stored in the browser (localStorage) on the user's device only.
- Alerts open the phone's SMS app pre-filled; the user taps Send. Automatic alerts need a backend with an SMS gateway.
- Helpline numbers last checked October 2026. Verify before real use.

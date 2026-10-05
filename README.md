# RoadDex Update 12

Supabase-backed global catalogue/search foundation.

## What changed
- Vehicle catalogue now loads from Supabase instead of treating the hardcoded browser list as the main source of truth.
- Search can call a server-side fuzzy catalogue search with local fallback.
- Search accepts chassis codes, aliases, nicknames, alternate-brand guesses, and common misspellings.
- Added a clean "Not in catalogue / can't find it" path so players are not pushed into making a bad ID.
- Added 19 generation-level catalogue entries, including Honda Beat, Suzuki Cappuccino, Mazda Cosmo JC, Fisker Ocean, BMW i3 I01, Nissan Xterra N50, Ford Bronco 6th gen, Mazda CX-5 KF, Volvo S60 P3, Lincoln Corsair, Toyota Corolla 11th gen, Lexus IS XE30, and others.
- Catalogue is now 67 generation-level entries in the current test seed, with 107 aliases.
- Existing Update 11 community identification/voting and the stable V9 capture/reframe flow are preserved.

## Search examples
- `Honda AZ1` -> Autozam AZ-1
- `cappucino` -> Suzuki Cappuccino
- `N50` -> Nissan Xterra
- `mk3 supra` -> Toyota Supra A70
- `GC8` -> Subaru Impreza GC-family
- `foxbody` -> Ford Mustang Fox Body

## Deploy
Replace the repository-root `index.html`, `README.md`, and `CHANGELOG.md` with the files in this package and commit to `main`.
Vercel should deploy automatically from GitHub.

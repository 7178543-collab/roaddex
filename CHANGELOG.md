# Changelog

## Update 12
Global catalogue and forgiving search foundation.

- Supabase is now the catalogue source of truth for the hosted client.
- Added server-side fuzzy search plus client-side fallback search.
- Expanded the seed catalogue from 48 to 67 generation-level entries.
- Added 107 searchable aliases, including wrong-brand guesses and chassis-code shortcuts.
- Added "Not in catalogue / can't find it" as an explicit identification path.
- Preserved Update 11 shared identification/voting behavior.

## Update 11
Community identification and voting are live against the shared Supabase backend.

The server, not the browser, decides when community consensus resolves a sighting.

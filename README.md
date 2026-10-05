# RoadDex Update 11

Shared community-identification test build.

## What changed
- Identification Board entries are tappable for every tester.
- Testers can propose a generation-level vehicle ID for another player's unresolved sighting.
- Testers can vote Agree / Disagree / Unsure on proposals.
- Review progress is visible per sighting.
- Server-side consensus rule: 5 distinct reviewers participate; a proposal with 3 Agree votes resolves the sighting automatically.
- Sighting owners and proposal authors cannot vote on their own item/proposal.
- A reviewer can Agree with only one proposal per sighting.
- Accepted IDs automatically update the original sighting and remove it from the unresolved board.
- Added "Vehicle not in catalogue" requests.
- Signup now explicitly redirects confirmed users back to the hosted RoadDex origin.

## Hosting
For Vercel drag-and-drop deployment, upload the contents of the RoadDex_V11_Vercel package or use its index.html as the site root.

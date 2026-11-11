# Ahanaf Orko Autopilot: notes for Claude

Cron-based auto-poster for Ahanaf Orko's Facebook Page, Instagram (@_ahanaf.orko), YouTube
(@AhanafOrko) and TikTok (@ahanaforko). Separate from the xegency bot (`e:\social-manager\social-media`,
different accounts, different tokens). Never mix their secrets or content.
Runs on GitHub Actions (repo `777-xevill/orko-autopost`, public, branch `main`) so it keeps posting when the PC is off.
Same code and rules as the xegency bot: free tools only, no tokens in git, secrets in GitHub Secrets
(`python -m bot secrets`). Setup steps: SETUP.md. Content plan: docs/CONTENT.md.
TikTok goes through Buffer's free plan (needs a Buffer account connected to @ahanaforko).
Local `.env` holds this repo's own secrets and is git-ignored.

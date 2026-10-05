# Parallel

A browser-based life simulator with careers, family succession, relationships,
property, investments, social activities and yearly undo.

## Play locally
Open index.html in a modern browser. The complete game is included in this
standalone file; no build tools or installation are required.

## Website entry point
Serve index.html as the website entry point. All scripts and styles are embedded.
The .nojekyll file allows plain static hosting on GitHub Pages.

## Save your progress
Use Save to download your life and Load to restore it. Save files stay with the
player and are not included in this repository. Optional device recovery is
browser-local; it does not transfer between laptops or website addresses.
Download your current life before moving from a local copy to the online game.

## Release 2026.10.05.1
5 October 2026: phone recovery status, background checkpoint attempts and visible release notes. Existing saves remain compatible.

## Cloudflare deployment
Worker: life-parallel. Production branch: main. No build command is needed for the standalone game. Deploy with npx wrangler@4 deploy using wrangler.jsonc. .assetsignore excludes deployment configuration and documentation from static serving. No API credentials belong in this repository.

The game source is embedded in index.html. The version and What's new notes are shared with the laptop edition. Check the visible version after each deployment. Device saves do not move between website addresses; use downloaded saves to transfer progress.

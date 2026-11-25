# clarkestudios.com

The Clarke Studios home page, served by GitHub Pages at https://clarkestudios.com/ (DNS on Cloudflare).

- `index.html`, `404.html`, `assets/`: the studio site. Fonts (Fraunces, Instrument Sans; SIL Open Font License) are hosted here so the site makes no third-party requests.
- `/.well-known/apple-app-site-association`: lets Kitchen Table: Five Hundred invite links (`/five-hundred-site/join/…`) open the app and its App Clip. Don't move or rename it.
- `app-ads.txt`: authorizes Google AdMob to sell ads in Rust & Shine (publisher pub-7657316151978846). AdMob crawls it at the root of the developer website, so keep it at https://clarkestudios.com/app-ads.txt.
- Game pages live in their own repos and appear under this domain: `five-hundred-site` → `/five-hundred-site/`, `periapsis-site` → `/periapsis-site/`.

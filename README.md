# arx-laboratories-llc.github.io

The **one** public website for Arx Laboratories, served by GitHub Pages at
https://arx-laboratories-llc.github.io/.

**Rule: every public page for any Arx Laboratories app goes in this repo.**
Privacy policies, terms, support pages, landing pages, `app-ads.txt`. Don't
create a new repo per app, because a separate repo's Pages site lives under a
sub-path, and anything that has to sit at the domain root (like
`app-ads.txt`) can only be served from here.

## Layout

| Path | What |
|---|---|
| `/app-ads.txt` | AdMob authorised sellers, shared by all apps on the account. Must stay at the root. |
| `/index.html` | Developer landing page. This root URL is the "Website" in Play Console for every app. |
| `/<app>/` | One folder per app: `index.html`, `privacy.html`, `terms.html`, and any others. |

Current apps:

- **TCGBox**: `/tcgbox/`, privacy policy at
  https://arx-laboratories-llc.github.io/tcgbox/privacy.html, terms at
  https://arx-laboratories-llc.github.io/tcgbox/terms.html
  (source of truth: `distribution/legal/privacy.html` in the private
  `ghero101/TCGBox` repo; copy it here when it changes).

## app-ads.txt

One line per ad network. AdMob's is
`google.com, pub-2833622142266414, DIRECT, f08c47fec0942fa0`. A new app on the
same AdMob account needs no change. A new mediation network does need its
line added here.

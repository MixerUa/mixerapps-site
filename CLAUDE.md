# mixerapps.dev — project rules (read every session)

## Mandatory rules

1. **The owner is not a programmer.** Any step they must do by hand (Cloudflare DNS, GitHub settings, tokens) is written as simple numbered steps: "Open site X → click button Y (it is at …) → paste into field Z: …". Every technical term (DNS, A-record, CNAME, proxy) gets a one-line plain-language explanation at first use. Communicate in Russian.
2. **Back up to GitHub immediately.** Every file created or changed here is committed and pushed to `github.com/MixerUa/mixerapps-site` in the same step — never deferred. The owner has no other backup.

## Content rules

- This is a showcase of the owner's **own** apps under the MixerApps brand — NOT a development studio. No order forms, no "services", no "hire us".
- Name is always **Oleksandr Mykusevych**, brand **MixerApps**, domain **mixerapps.dev** — exact spelling everywhere.
- Only facts confirmed by the owner. No invented team, founding dates, user counts, reviews.
- **Tenora legal pages must never be moved or changed** (they are registered in Google Play Console). Only link to:
  - https://mixerua.github.io/tenora-legal/
  - https://mixerua.github.io/tenora-legal/privacy-ru.html
  - https://mixerua.github.io/tenora-legal/data-deletion.html
- Store links only from the owner — never searched by app name. No link = honest status badge ("Coming soon" / "In development").
- Languages: English (default) and Russian, switcher on every page.

## Tech

Plain static HTML/CSS, no build step, hosted on GitHub Pages, DNS on Cloudflare (edited manually by the owner).

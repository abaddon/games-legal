# games-legal

Public legal pages for games published on Google Play by Stefano Longhi.

Live: <https://abaddon.github.io/games-legal/>

| Page | URL |
|---|---|
| Half Case privacy policy (en-GB + it) | <https://abaddon.github.io/games-legal/half-case/privacy.html> |
| Half Case terms of service (en-GB) | <https://abaddon.github.io/games-legal/half-case/terms.html> |

The privacy URL is the one entered in Play Console (App content > Privacy policy). The terms URL is
the one asked for under App content > Trader status declaration ("the link to the Terms of Service
for each of your apps"). Do not change either without changing the Console field in the same sitting.

## Rules

- Static HTML only. No JavaScript, no external CSS, no web fonts, no analytics, no cookies. A privacy
  page must not make third-party requests.
- The text of `half-case/privacy.html` must match the copy in the private repository
  `abaddon/games-company`, file `legal/allegati/privacy-policy-half-case-<date>.html`. Compare with
  `sha256sum`. The same rule applies to `half-case/terms.html` and
  `legal/allegati/terms-of-service-half-case-<date>.html`.
- A change of wording needs a new version line and date at the top of the page, and the same change in
  the private repository.

# Realmfront Legal

Privacy policy and licence credits for **Realmfront: Conquest** (`com.goethe47.realmfront`),
hosted as a static site so Google Play Console and the game itself can link to them.

## Publishing

Enable GitHub Pages for this repo (Settings → Pages → Source: `main` branch, `/` root):

```
https://goethe47.github.io/Realmfront-Legal/
```

Use that URL as the **Privacy Policy** link in Play Console. The credits page lives at
`https://goethe47.github.io/Realmfront-Legal/licenses.html` and is the link to use from
the game's own credits.

## Contents

- `index.html` — the privacy policy
- `licenses.html` — third-party data, music, sound, fonts and software, with their licences
- `styles.css` — dark deck, parchment sheet and gold rules, matching the game

## Before this goes live

The privacy policy describes an **ad-supported build**, which is what the closed test will
ship. LevelPlay is not in the game yet, so check these off as the integration lands:

- [ ] LevelPlay is actually in the build, and the ad formats match what the policy says:
      a banner in the reserved strip at the bottom, rewarded video by choice, and an
      occasional full-screen advertisement between matches.
- [ ] The list of ad networks under "Advertising" matches the adapters actually included.
      Right now the page names only Unity; add any other network you enable.
- [ ] The consent screen described under "Your choice about personalised advertising"
      is really shown in the EEA, the UK, Switzerland and the US states that require it.
- [ ] Play Console → Data safety is filled in to match this page: advertising data
      collected, no in-app purchases, no account.
- [ ] The date at the top of both pages is the date you publish.

There are **no in-app purchases** in this game by decision: everything that would be sold
is earned by playing or by watching a rewarded advertisement. If that ever changes, both
this page and Data safety change with it.

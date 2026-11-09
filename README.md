# To My Wife 💗

A single-file romantic surprise website: a secret PIN lock (hint: *our monthsary*),
then a menu of little pages — a gift surprise, a garden tree full of hidden heart
messages, our playlist, a love letter, and a fireworks finale.

## Open it

Just double-click `index.html`, or open it from the live site:

**https://cesspanganiban211-spec.github.io/to-my-wife/**

## Customize

Everything lives in one `const CONFIG` block near the bottom of `index.html`
(search for `const CONFIG`):

| key | what it changes |
| --- | --- |
| `pin` / `pinHint` | the secret 4-digit code and its hint |
| `from` / `to` | your name and her name |
| `surprise` | the surprise page message (paste your own text) |
| `flowers` | each heart in the tree + its hidden message |
| `songs` | the playlist (title/artist + link) |
| `letter` | the love letter |
| `apologies` | the 20 gentle apologies |
| `finale` | the last message + fireworks |

## GitHub Pages

1. Repo → **Settings → Pages**
2. Under *Build and deployment*, choose **Deploy from a branch**
3. Pick branch `main`, folder `/ (root)`, then **Save**
4. The site goes live at `https://<user>.github.io/to-my-wife/`

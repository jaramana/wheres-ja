# Where's Ja?

A parody page inspired by a Chappelle's Show sketch. Ask "Ja" about any crisis, treaty, or policy and get an official take from the cheapest AI available.

Not Ja Rule. Not affiliated. Ja was not reached for comment.

## Use it

- Open the page. Without a key, takes come from the offline Ja-Generator 3000.
- For AI takes, create a free key at [console.groq.com/keys](https://console.groq.com/keys).
- Click the brain button (bottom right), paste the key, and save. The page confirms whether Groq accepted it.
- The key stays in your browser. It is never part of this repo.

## How it works

| Part | Detail |
| --- | --- |
| Files | One file, `index.html`. No build step. |
| AI | Groq's cheapest chat model for your key, found automatically |
| Fallback | Offline mad-libs when there's no key or Groq fails |
| Length | Capped at 50 words (`maxWords` in the script) |
| Portrait | A `ja.jpg` next to `index.html` replaces the silhouette. It's gitignored. |

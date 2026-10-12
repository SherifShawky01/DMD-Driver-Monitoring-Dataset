# Our First Year

A small retro platformer for a first engagement anniversary. She plays through four levels: How We Met, Falling for You, Our Adventures, and The Night You Said Yes. In each level she collects 3 hearts, and every heart opens a memory. The last level replays the proposal, then shows a letter and the number of days since she said yes.

It's a single file (`index.html`) with no build step, no images and no dependencies. The pixel art and the music are both made in code.

## Make it yours

Open `index.html` and edit the `CONFIG` block at the top of the `<script>`:

- `herName`, `hisName`
- `engagementDate`: the `YYYY-MM-DD` date of the proposal, used for the "days since you said yes" counter
- `levels[].title`, `subtitle` and 3 `memories` per level (shown left to right as she collects the hearts)
- `proposal.question` and `proposal.answer`: the speech bubbles in the final scene
- `letter`: the paragraphs on the final screen
- `signature`

English and Arabic both work.

## Try it locally

Open `index.html` in a browser. Desktop controls: arrow keys to move, Space to jump.

## Deploy

**Vercel (website):** import this repo, set **Root Directory** to `anniversary-game`, choose framework preset "Other" and deploy.

**Vercel (CLI):**

```bash
cd anniversary-game
npx vercel --prod
```

**No account needed:** drag the `anniversary-game` folder onto https://app.netlify.com/drop.

Send her the link. It plays best on a phone, held either way. Ask her to turn the sound on.

# Family Patterns Lab

An interactive psychoeducational resource for recognizing unhealthy family dynamics, strengthening boundaries, interrupting inherited patterns, and building healthier relationships.

## The game layer

The Lab is structured as a playable quest rather than a set of lessons:

- **Quest trail** — the 17 modules are quests across three worlds (Unlearn, Heal, Grow). Nothing is locked; each cleared quest pays **+40 XP**.
- **Player HUD** — level (1–8, from *Pattern Spotter* to *Story Rewriter*), an XP bar, and per-world progress bars.
- **Clue cards** — inside each quest, the teaching points start blurred as clue cards; tapping reveals them one at a time. Finding them all pays **+10 XP**.
- **Power moves** — each quest asks the visitor to pick one concrete move they would actually try (**+10 XP**), stored with their progress.
- **Training Arcade** — the practice tools keep score: scenario rounds pay **+20 XP** per first correct answer, with a combo counter.
- **Challenge Arena** — the knowledge check pays **+15 XP** per correct answer and ends with a star rating (stars, not grades).
- **Trophy shelf** — 12 badges (world clears, Reflector, Scenario Ace, Script Smith, Trailblazer at 500 XP, and more), plus a rotating **daily quest** worth **+30 XP**.
- Reflections, the script builder, the support circle, the change-stage check, and the journal also pay XP the first time they are completed.

All game state lives in the same `localStorage` record as progress and reflections (`fpl-data`). Progress made before the game layer existed is backfilled with retroactive XP on first load, so returning visitors keep credit for quests already explored. The Chinese edition (`zh/`) mirrors the same system （经验、等级、徽章、每日任务）。

## Use

Open `index.html` in any modern browser. No build step, server, account, analytics, or external asset is required.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and this README to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose `main` and `/ (root)`, then save.

## Privacy

Progress and reflections are stored only in the visitor's browser using `localStorage`. The visitor can export reflections as a text file or clear all site data.

## Educational note

This resource provides general psychoeducation and guided reflection. It does not offer diagnosis, treatment, emergency support, or individualized clinical advice.

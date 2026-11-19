# Nada's Case: story book + online activities (Skills Bank, The Alpha Leader)

One HTML file, English and Arabic (RTL), no install, no sign-in. Calm "executive" look for managers.

## What is inside
| Block | Day | Time | What it is |
| --- | --- | --- | --- |
| **The Story** (book) | before / any time | 5-8 min read | Illustrated flip-book of Nada's case: cover, Meet Nada, the morning (8:00, 8:30, the escalation email, 9:15), the four people (one page each), your role. Replaces the printed booklet. Opens from the start screen and from the **Story** button on every screen, at the page that fits the activity |
| **Part 1 · Nada's Morning** | Day 1 | ~12 min | Five decisions, three meters (trust, composure, alignment), consequences, credibility gaps, evidence for the SWOT, a profile, and a 14-day mission |
| **Activity 2 · Nada's SWOT** | Day 1 | ~25 min | Digital version of the original activity: emotional journal (2 moments, same 6 columns as the printed sheet), SWOT from 12 pieces of evidence (plus the evidence collected in Part 1), then the participant's own triggers and SWOT (private) |
| **Activity 5 · You're the Mentor** | Day 2 | ~30 min | Four people x three tasks: ability, willingness and style per task, scored against the answer key of your original cards (4 points a task, 48 total) |
| **Part 2 · Two weeks later** | Day 2 | ~8 min | Check-in on the 14-day mission, then DISC read and the best opening line for each of the four coaching conversations (Activity 7 cards). 12 points |

Activity 5 replaced the old "style per person" round in Part 2, because your key assesses readiness per task.

## Publish (GitHub Pages)
Upload `index.html`, `.nojekyll` and the `img` folder; Settings > Pages > Deploy from branch (main, root). Open the published address, not a preview viewer.

## Run it
- **Players:** open the link, type a name, choose a block. With a session code the choices are shared with the trainer; without one everything still works.
- **Trainer:** Trainer Dashboard, code 2026 (hides the interface only). Live counts per decision, SWOT placements (with the suggested answer marked), journal answers, per-task style choices (answer key marked), projector view with a tab per topic and a discussion prompt, CSV export.
- Players only publish answers (about 20 small messages for all blocks); no live connection needed on their side.

## Pictures
Characters are vector illustrations drawn in code (no stock photos, so no licensing question on public hosting). To use your own pictures, put `nada.png`, `ahmed.png`, `sara.png`, `sherif.png`, `rana.png`, `manager.png` in the `img` folder.

## Please check before the session
1. **Story text** follows "Nada's Case (For Trainer)". I split it into pages and added only short guide and link text. The Arabic is my translation: have a native reviewer read it.
2. **Activity 5 answer key** is copied from your cards (per task). Style scoring: exact = 2, an adjacent style = 1 (my addition).
3. **Activity 2 SWOT suggestions** are my suggestions (there is no answer key in the materials). Four pieces are marked as debate and accept two placements. Edit `SWOTF` in the code to change them.
4. **Part 1 and Part 2** content (decisions, openings, DISC cues) is mine, based on the case and the Activity 7 cards. Review the "best" options.
5. **Activity 7 cards vs the case:** Sara and Rana are described a little differently (case and Activity 5: new, values independence, careful; Activity 7: energetic idea person). Part 2 uses the Activity 7 cards for the DISC cues; the book and Activity 5 use the case.

## Known limits
- Tested with simulated devices and a test relay, not on real phones or the live ntfy.sh relay. The public relay is not confidential: fictional case only.
- The mission and check-in live in the player's browser; switching device loses the mission name.
- Activity 2 and 5 are individual on one device; for teams, one device per team and the trainer's projector view for the group results.

# Nada's Case: the booklet as an interactive book, plus the online activities (Skills Bank, The Alpha Leader)

One HTML file, English and Arabic (RTL). Brand look of the Alpha Leader booklet: dark teal, mint, amber, diamonds, the Skills Bank logo.

## The book = the printed booklet
- **Same 8 pages, same text** as the booklet PDFs you sent (English and Arabic). Nothing removed. Page order is the reading order of the folded booklet: cover, Meet Nada, Morning Reflections, Team Meeting Challenges, Individual Team Dynamics (Ahmed), Sara and Sherif, Rana and Your Role, back cover. (The PDFs are print layouts, so their page order differs; the book follows the story.)
- **Same pictures:** Nada's photo from the booklet cover (cover and "Meet Nada" page); Ahmed, Sara, Sherif and Rana from your case cards, beside each character's paragraph. The cover reproduces the booklet cover (Skills Bank | Alpha Leader lockup, diamond photo, title diamond). The back cover is one colour with the Skills Bank logo. Page numbers carry the Skills Bank logo.
- Two-page spreads with a page turn on desktop, single pages on phones (swipe or arrows, keyboard arrows, a Contents menu).
- Opens from the start screen and from the **Story** button on every screen, at the page that fits the activity.
- On the role page the four buttons start Part 1, Activity 2, Activity 5 and Part 2.

### Text fidelity (please read)
Kept word for word, including the original wording oddities ("some concerns were arisen ... raises concerns", "not enough neither for her manager or her team", "Nada, finished her meeting", "Nada rarely give her directions"). Only formatting was normalised: spaces before punctuation, "seeksfreedom" to "seeks freedom", "10 Am" to "10 AM", a missing closing quotation mark, and the broken "fi/fl" characters of the PDF text. Decide if you want the wording itself polished (the Trainer doc version is cleaner).
The Arabic PDF is an image, so I typed the Arabic from the pages: please proofread it once against the PDF.

## Blocks inside the same HTML
| Block | Day | Time |
| --- | --- | --- |
| The Story (book) | before / any time | 5-8 min |
| Part 1 · Nada's Morning (5 decisions, 3 meters, SWOT evidence, 14-day mission) | Day 1 | ~12 min |
| Activity 2 · Nada's SWOT (emotional journal, SWOT of 12 pieces of evidence, own SWOT) | Day 1 | ~25 min |
| Activity 5 · You're the Mentor (4 people x 3 tasks, per-task readiness, key from your cards, 48 points) | Day 2 | ~30 min |
| Part 2 · Two weeks later (mission check-in, DISC read, opening lines, 12 points) | Day 2 | ~8 min |

In Arabic mode the UI uses the Arabic names of the booklet (ندى، أحمد، سارة، شريف، رانا، آدم).

## Publish (GitHub Pages)
Upload `index.html`, `.nojekyll` and the `img` folder; Settings > Pages > Deploy from branch (main, root). Open the published address, not a preview viewer.

## Run it
Players open the link, type a name, choose a block (a session code is optional). Trainer: Trainer Dashboard, code 2026 (hides the interface only). Live counts per decision, SWOT placements, journal answers, per-task style choices with the answer key marked, projector view with a tab per topic, CSV export.

## Please check
1. **Photos:** they are the stock photos already used in your Nada case files. They are published inside the HTML on a public site: confirm you are happy with that. You can swap any of them via the `img` folder.
2. **Activity 5** scoring follows your cards (exact style = 2, adjacent = 1 is my addition). **Activity 2** SWOT suggestions and **Part 1 / Part 2** decisions are mine; review them.
3. Sara and Rana are described a little differently in the case and in the Activity 7 cards; Part 2 uses the Activity 7 cards for the DISC cues.

## Known limits
Tested with simulated devices and a test relay, not on real phones or the live ntfy.sh relay (public, not confidential). The mission check-in lives in the player's own browser.

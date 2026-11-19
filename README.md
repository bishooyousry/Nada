# Nada's Case: online case simulation (Skills Bank, The Alpha Leader)

One HTML file, English and Arabic (RTL), no install, no sign-in. Built for managers: calm light interface, realistic inbox, call, meeting and calendar scenes, quiet sounds, no game effects.

## Publish (GitHub Pages)
Create a repo, upload `index.html` and `.nojekyll`, then Settings > Pages > Deploy from branch (main, root). Open the published address, not a preview viewer.

## Run it
- **Players:** open the link (or the page + the 5-character code), type a name, choose Part 1 or Part 2. Without a code the simulation works on its own (nothing is shared).
- **Trainer:** Trainer Dashboard, access code 2026 (hides the interface only, not real security). Copy the player link, watch the group's choices live, open the Projector view for the discussion, export a CSV.
- Players only publish their answers; they do not need a live connection. Roughly 8 small messages per player for both parts.

## Part 1: Nada's Morning (Day 1, about 12 minutes)
Four moments, five decisions. Each decision moves three meters (team trust, Nada's composure, alignment) and shows the consequence, any credibility gap, and one piece of evidence for Nada's SWOT.

| Scene | Decision | Best option | Links to |
| --- | --- | --- | --- |
| 08:00 Inbox | Reply to the escalation (D1) | B: pause, check facts, reply with a date | Self-regulation, credibility |
| 08:00 Inbox | Name the main trigger (D1b) | No right answer | Emotional triggers (Activity 2) |
| 08:30 Manager call | Respond to the favouritism complaint (D2) | B: ask for specifics, own the process | Credibility gaps (slide 14) |
| 09:15 Team meeting | Answer the KPI worry (D3) | B: explain the "why", take concerns up | Cascading goals, whole picture |
| 10:00 Calendar | Use 20 minutes before four coaching talks (D4) | B: reset, write the outcome per person | Coaching preparation |

End of Part 1: a profile (Composed Leader / Composed with one blind spot / Steady in places, reactive in others / Running on reflex), the evidence list for the SWOT in Activity 2, three discussion questions, and a 14-day mission (spot your trigger, start with the whole picture, ask for feedback).

## Part 2: Two weeks later (Day 2, about 10 minutes)
Opens with a check-in on the 14-day mission (same device and browser). Then Nada prepares four coaching conversations (cards from Activity 7): Round 1 leadership style per person, Round 2 DISC read, Round 3 the best opening line (one person per screen). 20 points: 8 style, 4 DISC, 8 openings.

| Person | Style (best / workable) | DISC | Best opening |
| --- | --- | --- | --- |
| Ahmed | S3 / S4 | D | Short, factual, results and agreed outcome |
| Sara | S1 / S2 | I | Recognition first, then three dated steps |
| Sherif | S3 / S2 | S | Safety, observation, listen first at his pace |
| Rana | S3 / S4 | C | Specific evidence, clear criteria, decision boundaries |

**Check this answer key before the session.** The style answers are my reading of the character cards (competence and commitment), not an existing key. Three of four land on S3 on purpose: it leads to "style says how much direction and support, DISC says how to talk". Change the values in `PEOPLE` (`style.best`, `style.ok`) if your key differs.

## Facilitation notes
1. After the credibility and self-regulation content, run Part 1 (individual, silent). Use the Projector view to open the discussion: which default behaviour costs trust most, which trigger shows up most.
2. Move into Activity 2 (SWOT): each player's result screen lists the evidence.
3. End Day 1 with the mission. At the start of Day 2 (after the Situational and DISC videos), run Part 2 as retrieval practice and warm-up for the Coaching Lab.
4. For 4-5 teams or 12-20 people, nothing changes: the simulation is individual and the dashboard aggregates.

## Known limits
- Not tested on real phones or with the live ntfy.sh relay; tested with simulated devices only. Do a two-device check first.
- The public relay is not confidential: fictional case only.
- Mission and check-in are stored in the player's own browser. If someone switches device, Part 2 asks the check-in without the mission name.
- Character cards (Activity 7) and the Nada case text differ slightly (Sara and Rana). Part 2 follows the cards because they carry the DISC cues.

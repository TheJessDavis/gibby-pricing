# The Gibby · Price a Class

A pricing calculator for teachers at The Gibby. Add up your materials, plug in what you want to earn, score your class on the tier rubric, and see the split break down live.

**Live tool:** open `index.html` in a browser, or visit the GitHub Pages URL if this repo has Pages enabled.

## What it does

- Adds up materials into a total and per-student cost
- Suggests a ticket price from your target pay (the total for the whole class, not per student)
- Scores your class on 5 factors (technique, prep, instruction intensity, training required, materials cost) to pick a tier and price range
- Shows the split live: materials off the top, then 60/40 on what's left
- Warns when materials eat too much of the ticket or the price falls outside the tier range
- Shows earnings at minimum, planned, and full enrollment so you can pressure-test the numbers before you post

## The split

- **Materials get paid back off the top.** The cost of materials comes out of class revenue before anyone takes a cut.
- **60% of what's left goes to the teacher.**
- **40% stays with The Gibby** to cover space and admin.

## Tiers

| Score | Tier | Range |
|---|---|---|
| 5 | Open Studio Time | $10 to $25, depending on materials provided and length |
| 6 to 7 | Tier 1 · Intro | $25 to $45 |
| 8 to 11 | Tier 2 · Intermediate | $45 to $65 |
| 12 to 15 | Tier 3 · Advanced | $65 to $100+ |

## Hosting

It's a single static HTML file. No build step, no dependencies. Host on GitHub Pages, drop it on any static host, or open the file locally.

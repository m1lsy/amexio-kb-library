# Process log

Newest entry on top. Copy the template at the bottom for each new version.

---

## v0.1 KB Drift (2026-11-13)

**Goal:** Test whether a mood-based interface, instead of a search bar, can surface books and library events people were not looking for.

**Inspiration:** Whichbook (mood and emotion page): sliders that filter books, and large clear covers in a grid.

**Prompt given to Claude:**
> Make my first prototype for KB royal library feature, inspired by whichbook.net/mood-emotion. I like the mood emotion page and the ability to filter and how the books are large and clear on the grid. Make me something inspired by this. Also find a way to focus on spontaneous and serendipity for people to discover things they weren't looking for like events at library and such.
(Plus the full project brief as context.)

**What was built:**
- Four mood sliders: Light/Heavy, Calm/Intense, Familiar/Strange, Alone/Together
- A single grid mixing books and library events, ordered by closeness to the chosen mood
- A "Stay close / Surprise me" dial that pushes unrelated items up, flagged with a "Detour" badge
- A detail card with a "Why this showed up" line and a "Follow the thread" button that moves the sliders to the linked item
- "Drift somewhere new" randomises everything; privacy note says nothing is stored

**Design decisions and why:**
- Events share the grid with books, with a different look, so discovery of non-book items happens by accident
- Hand-written reasons simulate AI suggestions without needing an API or a backend
- No search bar, to answer the research question literally

**Limitations:** 15 sample items only; events are invented; reasons are hand-written; no user testing yet.

**Feedback / test results:** _(to fill in)_

**Decision / next step:** _(to fill in)_

**Links:** live demo _(https://m1lsy.github.io/amexio-kb-library/prototypes/v0.1-kb-drift/)_ | screenshot `screenshots/v0.1-kb-drift.png` | commit tag `v0.1-kb-drift`

---

## Template

## vX.Y Name (date)
**Goal:**
**Inspiration:**
**Prompt given to Claude:**
**What was built / changed:**
**Design decisions and why:**
**Limitations:**
**Feedback / test results:**
**Decision / next step:**
**Links:**

# Azul: Queen's Garden — Rules summary (source of truth for the app)

**Source:** official English rulebook, Next Move Games / Plan B Games (© 2021, 2025), 6 pages
`https://cdn.svc.asmodee.net/production-nextmove/uploads/sites/4/2026/09/EN-AZUL-QG-Rulebook-2025_compressed.pdf`
(page numbers below = printed page numbers in that PDF). The "de-…" file on lib.sze.hu turned out to contain the
**same English text** (no German translation to cross-read). Icon-only information was read from the rendered pages.

**Second check (2026-11-20):** RulesPal (rulebook transcription), Board's Eye View, Geeks Under Grace, Zatu and the BGG
game page were read. None of them states the per-hexagon points in Phase 2, the wheel order, or the joker counts —
they only restate the rulebook. A search-engine summary claimed "each item is scored once per game and points rise
each round", but no page backed that up, so it is **not** used.

Tags: **[TEXT]** = stated in rulebook text; **[IMG]** = read from a rulebook illustration/icon;
**UNVERIFIED** = not stated explicitly, inferred, or unreadable → check the physical rulebook/components.

## ⚠ Differences from the brief (things the brief mentioned that are NOT in this rulebook)
- **"Smashed tiles" / smashed penalty** — does not exist in the rulebook. The real penalties are listed in section 11.
- **"Dual Matching Mode"** — does not exist. The only variant is the **"Game Variant"** (flip scoring board/wheel, R-V1…V3).
- **Which colors/patterns the rotary wheel scores each round** — the rulebook does **not** list this; it is printed on the
  physical wheel/board. The app therefore lets players record the 3 scored items per round (see O1).
- **Tiebreaker** — none. Tied players **share** the victory (R-E3).

---

## 1. Components / terms
- R-C1 [TEXT p2/3] 6 colors × 6 patterns; each of 108 colored tiles is a "hexagon" = pattern + color. 36 garden expansions
  also show a hexagon when face-up (p3 "Hexagon").
- R-C2 [TEXT p3] **Pattern value** = both its **cost** (to place) and its **points**: tree 1, bird 2, (3-butterfly) 3,
  (4-petal flower) 4, (leaf sprig) 5, (6-bell flower) 6. [IMG p3]. Names for patterns 5 and 6 are not given → UNVERIFIED (app uses numbers).
- R-C3 [IMG p6 example] Colors on the evaluation track: light blue, dark purple, lilac, yellow, light green, dark green. Color names are the app's own.
- R-C4 [TEXT p2] Per player: 1 garden board, 1 storage, 1 fountain board, 3 jokers, 1 scoring marker.
- R-C5 [TEXT p5] Jokers are **not limited**; use a substitute if supply runs out.

## 2. Setup
- R-S1 [TEXT p2] Each player takes garden board, storage, fountain board (in middle of garden), 3 jokers on empty storage spaces.
- R-S2 [TEXT p2] Scoring board (central icon visible = normal game side), rotary wheel on starting position, evaluation marker at top of evaluation track.
- R-S3 [TEXT p2] Scoring marker on the **15th space** of the scoring track → **start score 15**.
- R-S4 [TEXT p2] Bag with all 108 tiles. 36 garden expansions shuffled into 4 face-down round stacks of **5 (2p) / 7 (3p) / 8 (4p)**.
- R-S5 [TEXT p2] Round 1 stack in the middle (display area); fill its top expansion with exactly 4 random tiles. Remaining expansions form the supply (shield token on top).
- R-S6 [TEXT p2] First player marker in the display area. First round starter = **youngest player**.
- R-S7 [TEXT p2] Tower and jokers placed beside scoring board; point tokens set aside.

## 3. Round structure
- R-R1 [TEXT p3] The game lasts **4 rounds**. Each round: Phase 1 Players' actions (until all passed) → Phase 2 Scoring → Phase 3 Prepare next round (not in round 4).
- R-R2 [TEXT p3] Play is **clockwise**. Each round starts with the starting player.
- R-R3 [TEXT p5] Phase 3: turn the wheel clockwise to the next position; discard remaining tiles on face-down expansions in the display into the tower; return all remaining display expansions face down to the supply; place next round stack and fill its top with 4 tiles; owner of first player marker places it near the stack and starts.
- R-R4 [TEXT p5] If the bag runs short, refill it from the tower; if still short, play on with fewer/no tiles (empty expansions go face up).

## 4. Turn actions (Phase 1)
On your turn choose exactly one: A) Acquire, B) Place a tile, C) Place a garden expansion, D) Pass. [TEXT p3]

### A) Acquire (drafting)
- R-A1 [TEXT p3] Choose a **pattern** (take ALL hexagons of that pattern with different colors) **or** a **color** (take ALL hexagons of that color with different patterns) from the display area — tiles and expansions alike.
- R-A2 [TEXT p3] If two or more identical hexagons (same pattern+color) are in your selection, take only one (your choice).
- R-A3 [TEXT p3] Everything taken goes to your storage: **12 spaces for tiles, 2 for garden expansions**. If it doesn't all fit, that selection is not allowed.
- R-A4 [TEXT p3] If you took ≥1 tile from the current round stack: move the stack's top expansion (with remaining tiles on it) next to the stack into the display; then refill the new top expansion with exactly 4 tiles from the bag.
- R-A5 [TEXT p3] Any empty expansion (no tiles) in the display is turned face up (shows a pavilion + a hexagon) and becomes takeable via a matching pattern/color selection.

### B) Place a tile
- R-P1 [TEXT p4] Pick a tile from storage and pay its cost (= pattern value, shown on the top of your garden board).
- R-P2 [TEXT p4] **Paying:** discard that many hexagons from storage **including the tile being placed**. The discarded hexagons must either **all show the same pattern (different colors)** OR **all be the same color (different patterns)**. Identical hexagons cannot both be in the payment.
- R-P3 [TEXT p4] Discarded tiles → tower; discarded expansions → bottom of supply, face down.
- R-P4 [TEXT p4] **Jokers:** may replace any needed hexagon in the payment (one joker each), but you must have at least the hexagon you place (a joker can't be placed in the garden). Used jokers return to the supply.
- R-P5 [TEXT p5] **Legal space:** a free space (not occupied by hexagon or garden element) either (a) with **no adjacent hexagons**, or (b) adjacent to ≥1 hexagon, in which case the tile's **pattern OR color matches at least one** adjacent hexagon.
- R-P6 [TEXT p5] **Group:** ≥2 adjacent hexagons with identical patterns **or** identical colors, **but not both**. One hexagon can belong to one pattern group and one color group.
- R-P7 [TEXT p5] **Forbidden:** you may not create or extend (directly or by connecting hexagons) a group that would contain **2 identical hexagons** (same pattern AND color).

### C) Place a garden expansion
- R-X1 [TEXT p5] Expansions give 5 or 7 extra spaces. Either pay its cost from storage like a tile (R-P1…P4), **or** take a **face-down** expansion (7 spaces) from the supply by **spending exactly 6 points** on the scoring track (score can't go negative).
- R-X2 [TEXT p5] Place on a free expansion area around your fountain board, any orientation, following the same placement rules as tiles (R-P5…P7).
- Face-up expansion cost: its pattern value (it shows a hexagon). Cost-by-pattern is assumed same as tiles → UNVERIFIED wording ("its cost", p5, refers to p4).

### D) Pass
- R-D1 [TEXT p5] You **may** pass if you don't want to acquire/place; you **must** pass if you can't do any action.
- R-D2 [TEXT p5] When passing you may discard any number of hexagons from storage and score each discarded hexagon's value as **minus points**.
- R-D3 [TEXT p5] **First player to pass** takes the first player marker and moves their scoring marker **back 1 space (−1)**.
- R-D4 [TEXT p5] A player who passed takes no more turns this phase. Phase 1 ends when all have passed.

## 5. Jokers & garden elements (fountain board)
- R-J1 [TEXT p5] Completely surrounding a **fountain, statue, bench or pavilion** earns jokers from the supply, placed immediately in your storage; jokers that don't fit are lost.
- R-J2 [IMG p5] Joker amounts shown under the 4 icons, in text order (fountain, statue, bench, pavilion): **1, 2, 2, 3**. The icon→element mapping is inferred from order → **UNVERIFIED** (the app asks the player to enter the number of jokers rather than computing it).
- R-J3 [TEXT p3] 3 jokers at start (see R-S1).

## 6. The rotary wheel / Phase 2 round scoring
- R-W1 [TEXT p5] Starting with the first player, each player scores the round. The rotary wheel shows **3 scored patterns or colors** this round.
- R-W2 [TEXT p5] For **each hexagon in your garden matching** a scored pattern or color you score points; the same hexagon can score twice (pattern and color).
- R-W3 **UNVERIFIED** — the rulebook says "a number of points" and does not state the amount per hexagon. Strong inference from "Each [pattern] has … a number of points" (R-C2): points = the **pattern value** of the hexagon (1–6). Confirm on the board.
- R-W4 [TEXT p5] Then each player scores **+1 per visible pavilion** in their garden.
- R-W5 **UNVERIFIED / not in rulebook** — which 3 items the wheel shows in each of the 4 rounds. See O1.
- R-W6 [TEXT p5] The scoring track is continuous; use point tokens to track totals above 100/60 etc.
- R-W7 **UNVERIFIED (inference from setup illustration p2)** — the ring around the wheel shows **12 hexagons, alternating
  color / pattern**, the wheel has **3 prongs**, and tick marks I / II / III / IIII mark the round positions
  ("next position indicated by the lines", R-R3). 4 rounds × 3 = 12 → each color and pattern is most likely scored
  **exactly once per game**. The app greys out items already picked in earlier rounds as a hint, but does not block them.
- R-S4b [IMG p2] The strip on the scoring board reads "II … 5 · III … 7 · IIII … 8" = expansions per round stack by player count (confirms R-S4).

## 7. End of game & final scoring
- R-E1 [TEXT p6] Game ends after all players have passed in the **4th round**. The usual end-of-round scoring (Phase 2) happens, then final scoring.
- R-E2 [TEXT p6] **Storage:** each remaining **joker +1**; each remaining tile or expansion **−(its pattern value)** (tree −1, bird −2, …).
- R-E3 [TEXT p6] **Winner:** highest score. **Tie → tied players share the victory** (no tiebreaker).
- R-E4 [TEXT p6] **Evaluation track:** move evaluation marker through the 6 colors, then the 6 patterns (top to bottom). For each evaluation, every player scores **each group of ≥3** hexagons matching it (groups of 2 score nothing). No limit on number of groups per evaluation. A group scores the **sum of the pattern values of its hexagons** (values on the right of the scoring board). [TEXT+IMG p6 example: blue 1+2+3+6=12; five trees 1×5=5; pattern group 3+3+3=9]
- R-E5 [TEXT p6] Bonus: **+6 for each group of 6 hexagons** (normal game).
- R-E6 [IMG p6] A single hexagon is counted in its color group and its pattern group separately (the example scores a hexagon in both) — consistent with R-P6.

## 8. Game Variant (flip boards)
- R-V1 [TEXT p6] Turn the scoring board to the central-icon side… (rulebook wording: "so the central icon is visible" — same wording as normal setup R-S2) **UNVERIFIED which side is which**: wording is identical to the normal setup, so the physical flip must be confirmed on the box.
- R-V2 [TEXT p6] In the variant, **patterns score differently in Phase 2** — values not printed in the rulebook → **UNVERIFIED** (app: manual entry).
- R-V3 [IMG p6] Variant group bonuses at final scoring: group of **4 → +3, 5 → +5, 6 → +7** (read from the bonus strip; verify). Replaces the normal "+6 for 6".

## 9. Score keeping
- R-K1 [TEXT p2/5] Start on space 15; one continuous track; players use 60/… tokens for totals beyond one lap.

## 10. Quick-reference answers used by the FAQ (all derived from above)
- Same pattern **and** color twice in a group → illegal (R-P7).
- Same pattern **or** color adjacent → legal, forms a group (R-P5/P6).
- Two tiles matching on color **and** pattern (identical) next to each other → illegal (R-P7).
- Place with no neighbours → always legal (R-P5a).

## 11. All penalties (there is no "smashed" tile)
| Event | Effect | Rule |
|---|---|---|
| First player to pass | −1 | R-D3 |
| Discard hexagons when passing | −value each | R-D2 |
| Buy face-down expansion | −6 exactly | R-X1 |
| End: leftover tile/expansion in storage | −pattern value each | R-E2 |
| Jokers beyond storage space | lost (no points) | R-J1 |

## 12. Open questions (ask the owner / check the physical box)
- **O1** Which colors/patterns does the wheel score in each round, and in the variant? (not in rulebook)
- **O2** Points per matching hexagon in Phase 2 — confirm = pattern value (R-W3).
- **O3** Is there a minimum score of 0 for penalties other than buying an expansion? Rulebook only says it for the −6 purchase (R-X1).
- **O4** Joker rewards 1/2/2/3 ↔ fountain/statue/bench/pavilion mapping (R-J2).
- **O5** Variant: which side of the scoring board, Phase 2 values, and 4/5/6 bonus values (R-V1…V3).

## UNVERIFIED index
R-C2 (names of patterns 5–6), R-X2 (expansion cost wording), R-J2, R-W3, R-W5, R-W7, R-V1, R-V2, R-V3, plus all of O1–O5.
Fastest way to close R-W3/R-W5/R-W7/O1/O2: a close-up photo of the physical scoring board (both sides) and the wheel.

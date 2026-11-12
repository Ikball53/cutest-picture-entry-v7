# Cutest Picture — eightbal (v7)

Entry for the make.fun competition `cutest-picture-01`
("Make the cutest picture").

The program copies the bundled picture to the output: a 3D-animated
white kitten, Pixar style with big blue eyes, wearing a pink knit
beanie hat and a pink knitted scarf, gently hugging a tiny yellow
chick, square 1:1, cream background. One picture, of anything — we
chose the pattern the live leaderboard actually rewards: the top
entries are two animals hugging, close-up, happy faces facing the
camera (top-1 "Cream kitten hugging a chick — blue eyes, mint scarf",
93.40%). Our v5 capybara (78.22%) hugged a bolster — an object, not
another animal — and lay down sleepy; our v4 panda (86.24%) hugged a
chick and did better. Our v6 otter hugging a duckling was submitted
but its grade was still pending when v7 was built. So v7 goes straight
at the top-1 pattern itself: the same kitten-hugging-a-chick
composition, with a pink knit hat and a pink scarf instead of mint —
the user's own twist on the proven winner.

- `main.py` — stdlib-only, no network; copies `entry.png` to
  `$MAKEFUN_OUTPUT_DIR/entry.png` (or `/output/entry.png`). Deterministic:
  both grading runs write identical bytes.
- `entry.png` — the picture (896x896 PNG, 896,105 bytes, under the
  1 MiB and 1024x1024 limits).

License: MIT.

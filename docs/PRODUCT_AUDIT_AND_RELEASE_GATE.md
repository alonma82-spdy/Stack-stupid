# Stack Stupid: product and quality audit (2026-10-23)

## Acceptance standard
The user-supplied four-panel concept image is the visual specification for all four screens: title, first catch, high tower/combo, and game over. The current SVG/vector placeholder animals are **not accepted artwork**. Never describe them as matching the reference.

## Confirmed current implementation
- HTML5 canvas game on GitHub Pages
- Touch movement, falling characters, height, score, perfect catches, combo, three hearts, best score
- Synthesized music/purr and mute button
- Procedural skyline and wide blanket
- Placeholder vector animals, not furry reference characters
- No production ads or in-app purchases

## Critical gaps, prioritized
P0. Produce a cohesive set of transparent, high-resolution, furry character assets (gray tabby kitten, orange kitten, puppy, panda, bunny) with at least five poses each. Maintain exact face/fur identity across poses. Use real raster artwork, not emojis or SVG primitives.
P0. Build production title screen using approved 3D logo, animal stack, blanket, city backdrop and glossy buttons.
P0. Implement four visually faithful screens and compare screenshots side by side with approved reference at iPhone viewport sizes.
P0. Verify gameplay, rendering, and audio in mobile Safari, including slow devices and screen resizing.
P1. Use character sprite atlases and consistent shadow/lighting; falling, landing squash/stretch, idle breathing, reactions, and topple animation.
P1. Proper game states: menu, playing, paused, game over, restart. Never have multiple active animation loops.
P1. Wide moving blanket, reliable collisions, camera follow, true stability/tipping physics, recoverable near-misses.
P1. Improve music and sound with real licensed/created audio; purr on every catch; mute persists.
P2. Balanced perfect/near-miss/combo scoring, collectible cosmetics, 30-second missions, weekly challenges, progression and daily reward.
P2. Instrument telemetry: run duration, first-catch success, miss rate, median tower height, replay rate, D1/D7 retention, sound toggle.
P3. Ads and $1.99 no-ads purchase only after compliant store/payment integration; never show nonfunctional purchase controls as real checkout.

## Gameplay test criteria
- First animal always catchable from blanket.
- Every catch visibly lands and plays purr; a missed animal loses exactly one heart.
- Scoring deterministic and best score saved.
- Difficulty ramps without unwinnable drops.
- Tower balance visibly influences risk and rewards.
- Pause/resume works; audio does not duplicate after restart.
- No blank sprites on first load or after returning from background.

## Retention experiments
A: Perfect landing bonus + escalating audiovisual combo feedback.
B: Cosmetic animal unlock every 3 successful runs, with a preview of next unlock.
C: One short daily challenge and visible personal best.
D: Risk/reward: wobble warning and save bonus without arbitrary punishment.
Test separately; use actual replay and retention data. No claim of addictiveness before measurement.

## Release gate
Do not claim finished unless all four visual states are verified against the reference and gameplay tested on iPhone. The reference image itself is NOT an animation asset pack.

# Morse Boy v0.6.0

Package prepared 2026-10-15. The approved ROM is unchanged.
Created by dansciurus (Big D), with ChatGPT assistance.

## Included experience

- A separate splash and a three-entry main menu: Decoder,
  Receive RX and Transmit TX. Startup music continues from splash to menu.
- Learn RX with 13 cumulative, freely selectable stages; Practice RX with
  letters/digits, distinct choices, replay, free hints, feedback, streaks and
  three battery-style lives.
- The approved two-orientation hollow decoder chart, stable live footer,
  fixed input timing and single-START menu return. Four consecutive dashes
  are capped at O; other valid four-element letters remain available.
- TX Speed with randomized letters and aligned optional Morse hints.
- TX Words with 64 manually cycled words, large targets and a 36-character
  large received transcript that preserves mistakes and omits word-gap spaces.
- TX Scratch with 144 cells, real word spaces, wrapping, safe FULL behavior
  and responsive full-page clearing.
- Shared 05–99 WPM controls in TX, default 15 on a fresh session; speed changes
  respect character boundaries. START stops keying and returns to the menu.
- Coherent RX hint/answer placement and complete-target TX word transitions.

## Acceptance and limits

The developer completed BGB visual/gameplay acceptance. Nineteen automated
suites pass against this exact ROM, including 492 calibrated TX cases,
stress checks retaining a four-tick sampled sidetone limit, RX rendering
budgets, menu/music continuity, Scratch clearing and frozen decoder pixels.
Sub-frame injected digital samples and frame-polled emulator buttons are
separate test methods; neither certifies physical input on original hardware.
Scratch visual-clear measurements were approximately 77–93 ms in PyBoy.

BGB human acceptance and automated results do not certify original hardware,
all handhelds, every emulator version, or subjective sound quality. No source,
tests, development symbols or private recordings are included. See the guide
for capacity limits and the verified handheld remap, and distribution status
for the sharing terms.

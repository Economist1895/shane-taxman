# Shane the Taxman
A turn-based browser RPG. No dependencies, no build step — just open in a browser and play.

**Play now: https://economist1895.github.io/shane-taxman/**

## How to play
Open `index.html` in any modern browser, or visit the link above. Everything — including all the pixel art — is in that one file.

Shane Soh commands from the sidelines. Pick 3 officers from a roster of 11, set your party order, and fight through 3 rotations of bureaucratic combat. HP carries over between rotations. MP partially restores.

## Features
- 11 playable characters with distinct kits
- 3 difficulty modes (Easy, Normal, Hard)
- Turn-based combat with status effects, buffs, debuffs, stuns and revives
- Shane has 2 commander skills usable at any point during your turn
- Procedurally drawn pixel-art sprites and office backdrops (no image files)
- 16-bit JRPG presentation: skill banners, hit effects, boss intro, animated HP bars
- Fully responsive — plays on mobile, tablet and desktop

## Characters
| Name | Role | Identity |
|------|------|----------|
| Ryan Li | Investigator | Attacker / Self-sustain |
| Karishma Jayakumar | Customer Service Officer | Healer / Reviver |
| Sylvester Sim | Legal Associate | Attacker / Control |
| Jade Chen | Policy Officer | Debuffer / Buffer / AOE |
| Shaun Tan | Tax Specialist | Tank / Debuffer |
| Annie Khoo | Outreach Officer | AOE Debuffer / Drain |
| Bethany Su | AI Lead | AOE Attacker / Debuffer / Healer |
| Jiawei Tan | Software Developer | Attacker / Self-sustain / Reviver |
| Richmond Yeo | Auditor | Attacker / Debuffer |
| Angel Jasmine Loh | Procurement Officer | Support / Attacker |
| Jasper Samuel | Seconded Officer | Attacker / Support / Reviver |

## Tech
One file: `index.html`. Vanilla JS, no frameworks. Sprites and backgrounds are drawn in code on `<canvas>`. No external dependencies beyond a Google Fonts import for the Press Start 2P and VT323 typefaces.

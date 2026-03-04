# Translation Progress

See also: [Glossary](translation-glossary.md)

## Files

| # | File | Est. Strings | Status |
|---|------|-------------|--------|
| 1 | `main.js` (root) | ~293 | ✅ Done |
| 2 | `index.html` | ~104 | ✅ Done |
| 3 | `src/items.js` | ~562 | ⬜ Pending |
| 4 | `src/enemies.js` | ~788 | ⬜ Pending |
| 5 | `src/locations.js` | ~764 | ⬜ Pending |
| 6 | `src/dialogues.js` | ~265 | ⬜ Pending |
| 7 | `src/crafting_recipes.js` | ~292 | ⬜ Pending |
| 8 | `src/display.js` | ~284 | ⬜ Pending |
| 9 | `src/skills.js` | ~135 | ⬜ Pending |
| 10 | `src/traders.js` | ~121 | ⬜ Pending |
| 11 | `src/active_effects.js` | ~48 | ⬜ Pending |
| 12 | `src/combat_stances.js` | ~20 | ⬜ Pending |
| 13 | `src/character.js` | ~18 | ⬜ Pending |
| 14 | `src/misc.js` | ~10 | ⬜ Pending |
| 15 | `src/activities.js` | ~8 | ⬜ Pending |
| 16 | `src/trade.js` | ~1 | ⬜ Pending |
| 17 | `src/game_time.js` | ~3 | ⬜ Pending |

## Translation Rules

1. Always check the glossary before translating a term
2. Translate display strings only — not internal code keys/identifiers
3. Preserve all JS syntax exactly (no added/removed brackets, commas, etc.)
4. Item/enemy names used as lookup keys stay in Chinese — only the `name:` display field is translated
5. Run `npm test` after each file commit

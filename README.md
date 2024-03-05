# aave-rf-updates-generator

Converts a reserve factor markdown table (`table.md`) into most of the payload & test Solidity code.

Before starting populate `table.md` (check out `table.md.example`). Then:
- `yarn payload` to generate payload code
- `yarn test` to generate test code
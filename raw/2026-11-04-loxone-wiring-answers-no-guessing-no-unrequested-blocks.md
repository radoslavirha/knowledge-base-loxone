---
date: 2026-11-04
type: note
repos: []
source: chat
author: radoslav
---

# Loxone wiring answers: no guessing, no unrequested blocks

## Context
On 2026-11-03 and 04 an agent invented a "T" input, added a second Stairwell block the user never agreed to, and offered a 120 s delay from one dip. The user called out each one, angrily.

## Fact
For Loxone wiring answers:

- Check the block's docs before naming inputs or parameters (Context7 `/websites/loxone_enen_kb`).
- Separate measured, documented and guessed. If there is no known solution, say so instead of proposing another design as a fix.
- Base numbers on data, not one event. Do not add blocks or numbers the user did not ask for. Never treat silence as agreement.
- Always draw the full wiring with every block and setting, not a fragment, and keep the diagram readable.
- Simple native blocks over long PicoC.

## How to apply
Before sending Loxone wiring, check each block name and setting against the docs, or mark it untested.

## v1.0.2 — 2026-11-13

📋 CHANGES
• Fixed: "syntax error near '<\1>'" in modules/framework/loader.lua on escrowed builds.
• Fixed: "callback 'FM-Spawn:sv:getSelectorState' does not exist" (caused by the loader error above).
• Fixed: framework loader and adapters (QBox, QBCore, ESX) are now excluded from escrow so ox_lib require can read them.
• Fixed: loader now returns the adapter that server/main.lua expects (name, GetLastPosition, IsDead, GetProperties).
• Improved: framework auto-detection now loads the matching adapter and falls back to standalone if none is found.
• Improved: a missing adapter function now falls back safely instead of erroring.
• Added: clear console message if a framework adapter fails to load.

## v1.0.1 — 2026-10-05

📋 CHANGES
• Update Checker Added
• Unescrowed config file
• some major bug fix

# FM-Spawn Changelog

## v1.0.0 — 2026-10-05

✨ NEW
• Script launch


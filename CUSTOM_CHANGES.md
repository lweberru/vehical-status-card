# Custom changes (Fork)

This fork contains additional features not present in upstream `ngocjohn/vehicle-status-card`.

## Functional changes
- Indicator tooltips show the **current state value** by default.
- Range info items support a header with **icon, title, and tooltip**, and hide the internal state icons when a header icon is provided.
- Mini map supports **MapTiler theme selection** via `maptiler_style` and applies it to both the inline mini map and the popup map card.

## Editor changes
- Mini map editor exposes `maptiler_style` as a dropdown.
- Range info editor exposes header fields (icon/title/description/tooltip).

## Build / HACS changes
- Release builds are emitted to `dist/vehicle-status-card.js` for HACS compatibility.

## Notes
- Keep this file updated when adding fork-specific changes.

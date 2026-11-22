# Echoes of Eternity

**Chapter I: The First Awakening** is a small, original browser RPG prototype with a classic handheld-inspired presentation and turn-based battles.

## Play

Open [`index.html`](index.html) in a modern browser. The game uses Canvas and browser local storage; no build tools or dependencies are required.

Once GitHub Pages is enabled for the repository, the game will be available at:

`https://vhisham-singh.github.io/echoes-of-eternity/`

## Controls

- **WASD / Arrow keys:** Move around Willowbrook
- **Space / Enter:** Talk, examine, and advance dialogue
- **Esc:** Open or close the menu
- **Shift+S:** Save progress
- **Battle buttons:** Fight, cast Lumen, use a Potion, or attempt to run

Progress is stored locally in the browser. The Save Game menu action stores your current progress on that device.

## Chapter I objective

Meet Elder Rowan, investigate the ancient well, and recover the lost forest sigil. Random Hollow Wolf encounters can occur while exploring after speaking with Rowan.

## Review and learning criteria

When reviewing the prototype, consider:

- **Playability:** Can a new player discover the controls, speak to Rowan, complete the objective, and understand when encounters begin and end?
- **Combat balance:** Are enemy damage, Ari's HP/MP, Lumen's cost, Potion healing, rewards, and escape chance fair?
- **Accessibility:** Is text readable, are controls explained, and can important actions be used without relying only on color or timing?
- **Reliability:** Does saving and reloading preserve progress? Do menu, dialogue, battle, victory, and defeat states behave consistently?
- **Mobile usability:** Do the layout and controls work on small screens? (Touch controls are a useful area for future feedback.)
- **Learning value:** Can a beginner follow the inline HTML, CSS, and JavaScript and identify where movement, rendering, quests, and combat are implemented?

Please share feedback with steps to reproduce, expected behavior, actual behavior, browser/device, and any suggested adjustment. User criteria should guide future changes; no user-specific criterion has been assumed in this prototype.

## Publishing

To publish with GitHub Pages, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save. GitHub will show the published URL in the Pages section after deployment.

To publish a versioned release, open **Releases → Draft a new release**, choose a tag such as `v0.1.0`, add a title and summary, then publish. This repository does not yet have a release created.

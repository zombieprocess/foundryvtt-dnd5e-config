# foundryvtt-dnd5e-config
Version control for the configs we use, and particularly keep track of the modules and their setup.

| Organization and layout based on this project:   |
| ------ |
|  https://github.com/jbowensii/FOUNDRYVTT-DnD5e-Base-Game-Configuration |

## Foundational approach

- D&D Beyond Character sheets are the place of record for characters
- At the beginning of a session we should sync into Foundry/Forge VTT
- At the end of a session (or before we play next) we ensure D&D Beyond player character sheets are updated.
- No secrets are stored in the config files (apiKey, passwords, user accounts, etc.)

### directory structure and file summary

```shell
$ tree -F -L 3 foundryvtt-dnd5e-config/
foundryvtt-dnd5e-config/
├── foundry-settings-export.json          <== Server config export
├── modules/                              <== Module configs exports
│   ├── compendium-folders/
│   │   ├── compendium-folders.json
│   │   └── README.md
│   └── midi-qol/
│       └── fvtt-midi-qol-settings.json
└── README.md                             <== This README

3 directories, 5 files
```

## Modules

### Base Foundry Enhancements :building_construction:

These modules modify Foundry but pretty much fix components that are not mature or address some shortcomings.

<details>
  <summary>Click to expand</summary

- `Compendium Folders` - organizes Compendium content
- `Changelogs & Conflicts`
- `Dice Tray` - Adds a dice tray under the chat
- [`Forien's Copy Environment`](https://foundryvtt.com/packages/forien-copy-environment/) - Export/Import global server configs
- `Foundry Community Macros`
- `lib - Color Settings` - module dependency
- `libWrapper` - module dependency
- `Pings` - longpress mouse button to "ping" a place on a map, shift+click to snap the camera to the location
- `PopOut!` - Pop any window out of the game into it's own dedicated window, great for having notes open
- `Search Anywhere`
- [`Navigation Presets`](https://foundryvtt.com/packages/navigation-presets) - organizes maps, scenes, and chapters/groups
- `Module Compatibility Checker` - See settings > Manage Modules > `Button`
- `Minimal UI` - Does just that, collapses tray for abilities and macros, same for logged in users, drops the Foundryvtt icon which just takes up space.
- `Selective Show` - **DO NOT NEED in v10** - function is added into core
- `Settings Extender` - module dependency
- `socketlib` - module dependency
- [`tagger`](https://foundryvtt.com/packages/tagger) - creates tags on game objects/assets which enables more elegant automations
- `Token Mold` - fix and improve token creation from actors with templates
- `Tokenizer` - Edit/Add frames around tokens
</details>

---

### DnD 5e and Game Automation | Ease of Play :crossed_swords:
These modules are what makes Foundry use Dungeons and Dragons 5e rules and includes automations or improvements for players making things run much smoother.
<details>
  <summary>Click to expand</summary>

- `Active Token Effects`
- `Active-Auras`
- `Better Rolls for 5e`
- `Beyond20 companion module`
- `Combat Enhancements` - modification for combat tracker to include HP tracking, clears targets on "next turn"
- `Combat Ready!` - Helps combat flow better with notifications like "Next Up" and if you want timers for turns.
- `Dfreds Convenient Effects` - scripted macros and effects for abilities, mechanics and spells which can be added to players and npcs.
- `Dfreds Droppables` -
- `DNDBeyond Character Sheet for 5E` - Reskin of the default character sheet
- `DNDBeyond NPC Sheet` - Reskin of the default NPC sheet
- `FXMaster` - Adds additional effects, like weather, environment and matching sounds, pull these in on demand.
- `Group Initiative` - Group monster rolls
- `Health Estimate` - Lets people know approximate health of tokens that are not their own
- `Initiative Double Click` - enables fixing Initiative rolls/ordering during combat
- `Item Macro`
- `Automatic Automations` | `Sequencer` | `JB2A` (Tightly coupled)
  - `Dynamic Active Effects SRD` -
  - `Dynamic Effects using Active Effects`
- `Let Me Roll that For You` (LMRTFY) - prompts for roll, like saving throws
- `MidiQOL` | `Dynamic Active Effects` (DAE) | `Times Up` (Tightly coupled) - high level of automation and effects
  - `Midi SRD`
  - `Token Magic Effects`
- `Mob Attack Tool` - Combine attacks from many creatures into one
- [`Monks Active Tiles`](https://foundryvtt.com/packages/monks-active-tiles) - Enables tile automations like teleporting, traps, etc.
- `Perfect Vision` - **MIGHT be going away in v10** because this is in the core
- `Splatter` - blood Splatter on "bloodied" and death
- [`Token Attacher`](https://foundryvtt.com/packages/token-attacher) - Enables easier token/tile management and automations like vehicles and things that move

</details>

---

### GM Addons to make game prep easier :world_map:
These modules are focused around the GM, creating new content or running a session.

<details>
  <summary>Click to expand</summary>

  - `Moulinette Core`
    - `Moulinette Game Icons (module)`
    - `Moulinette Image Search (module)`
    - `Moulinette Scenes (module)`
    - `Moulinette Sound & SoundPad (module)`
    - `Moulinette Tiles (module)`

</details>

---

### Integrations with other tools/sites :hammer_and_wrench:
These modules are for bridging and integrating with other tools, like D&D Beyond or The Forge VTT.
<details>
  <summary>Click to expand</summary>

  - [`D&D Beyond Importer`](https://foundryvtt.com/packages/ddb-importer) - Mature DDB import and sync tool. Patreon supported. Can sync players back to D&D Beyond.
  - `The Forge: More Awesomeness` - forge module dependency, need API key to configure storage use

</details>

---

### Evaluating/Testing :sparkles:
These modules are being evaluated and may be used permanently or removed depending on how well they add to the experience.
<details>
  <summary>Click to expand</summary>

- `Argon - Combat HUD` (active)
- `Combat Carousel` (active) - adds alternative combat tracker
- `Combat Utility Belt` - (installed but disabled) - might not need it anymore with other automations
- `Dice So Nice!` (installed but disabled)
- `DnD5e UI` (installed but disabled) - Creates nice cards in chat, tab icons change which might require some getting used to
- `Forien's Quest Log` (installed but disabled)
- [`multilevel Tokens`](https://foundryvtt.com/packages/multilevel-tokens/) - Adds several helpful token automation features around multi level maps.
- [`Less Fog`](https://github.com/trdischat/lessfog) (installed but disabled)
- `tabletopaudio` (installed but disabled) - integration with the website https://tabletopaudio.com/ - can create audio streams players can tune in to

</details>

---

### Future stuff :soon:
This module list is needed for future improvements or evaluated to replace one of our existing tools. For example we don't have flying in our campaign yet, so we don't need to worry about levels/height. The top three on the list will make this easier.
<details>
  <summary>Click</summary>

- Better Roofs
- Levels
- Wall Height
- Monk's Tokenbar (LMRTFY alternative?)
- DDB Gamelog (DND Beyond)
- Status Icons

</details>

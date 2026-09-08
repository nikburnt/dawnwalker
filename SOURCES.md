# Sources and data limitations

Data snapshot: **8 September 2026**. Retrieved pages and structured source snapshots are retained locally in `research/`; they are not included in the published site repository. The planner makes no catalogue requests while running.

## Game rules

- [Bandai Namco — Community Bulletin Board #11: Skills & Power](https://en.bandainamcoent.eu/dawnwalker/news/community-bulletin-board-11-skills-power): three skill trees, shared skill points, training time, manuals for human skills and vampiric Corruption. This official article establishes the rules but does not provide a complete release-version table for every rank.
- [Official The Blood of Dawnwalker page](https://en.bandainamcoent.eu/dawnwalker/the-blood-of-dawnwalker): game context and official materials.
- [PowerPyx — Trophy Guide & Roadmap](https://www.powerpyx.com/the-blood-of-dawnwalker-trophy-guide-roadmap/): human Ultimates require 35 points in regular **perks** in the corresponding tree, plus 4 points to learn the Ultimate. Active Ability points do not meet this requirement. Vampiric Ultimates require Corruption 15. Only one Ultimate can be selected per tree.
- [PowerPyx — All Skill Manual Locations](https://www.powerpyx.com/blood-of-dawnwalker-all-skill-manual-locations/): manuals and additional copies. The guide does not establish initial availability for every rank, so uncertain manual requirements are shown as an upper bound.
- [KeenGamer — How to Get Ability Slots](https://www.keengamer.com/articles/guides/how-to-get-ability-slots-in-the-blood-of-dawnwalker/): Master Fencer, Forbidden Sigils and Vrakhiri Might; 2/3/4 total slots at costs of 1/1/2 SP. Known Vrakhiri Might Corruption thresholds are 4/7/11.
- [PC Gamer — The Blood of Dawnwalker review](https://www.pcgamer.com/games/rpg/the-blood-of-dawnwalker-review/): 16 segments per full day. The conversion of 30 days to 480 segments is a reference, not a mandatory training budget.

## Skill tables

- [Dawnwalker Codex — Skills](https://dawnwalkercodex.com/skills): primary source for individual SP and time costs, rank counts and decoded descriptions. Data from 88 individual skill pages was saved. Missing numerical costs remain unknown; `null` is never silently treated as zero.
- [GamesDB — Dawnwalker Skills](https://gamesdb.gg/dawnwalker/skills): additional descriptions, dependencies and game illustrations. Several decoded tables incorrectly accumulate absolute values, so those values are not used as ready-made character totals.
- [MetaBot — Build Planner](https://metabot.gg/en/dawnwalker/build-planner): the original calculator, names, dependencies, Ultimate flags and manual links. Its uniform one-point costs and artificial character-level gates were not carried over.
- [MetaBot — Skills](https://metabot.gg/en/dawnwalker/skills): original game icons for individual skills. Retrieved image addresses are retained in the local research records.

The normalized catalogue contains **90 skills / 274 ranks**: 63 perks and 27 abilities. The saved tables provide SP costs for 266 ranks. Astral Communion and Compel Soul are included as abilities without a common slot, but their costs and progression remain unconfirmed. GamesDB may incorrectly accumulate their bonuses; those numbers are excluded from numerical totals.

Some Codex ability descriptions are empty. Their original text is supplemented from GamesDB with a warning retained in the catalogue metadata. These values should be checked against the game; they are not independently verified damage formulas.

## Wiki cross-check: 8 September 2026

[Dawnwalker Database Wiki — Skills](https://dawnwalkerdatabase.wiki/skills/) supplied additional leads. Its official screenshots and linked gameplay guides were checked before changing progression. Several wiki summaries assign effects to the wrong names (including Witchcraft Mastery and the two blood buffs), so the existing source-backed descriptions were retained.

The update adds information to 27 skills, including 22 acquisition notes. Every affected catalogue entry retains its supporting source as metadata. Acquisition routes are collapsed under **How to obtain · location spoilers**.

| Addition | Evidence and treatment |
|---|---|
| Nourishing Blood II / III | Corruption 3 / 8, read directly from the [official panel](https://static.bandainamcoent.eu/high/dawnwalker/the-blood-of-dawnwalker/02-news/DAWNWALKER-community-bulletin-board-11/SC2-VAMPIRIC.jpg). Marked as a prerelease reference. |
| Last Stand | +100% Weapon Damage below 30% Health; retained as a conditional bonus. [GamesRadar gameplay guide](https://www.gamesradar.com/games/action-rpg/blood-of-dawnwalker-perks-skills-abilities/) and [Gamer Guides](https://www.gamerguides.com/the-blood-of-dawnwalker/guide/getting-started/character-development/best-swordmastery-perks-and-abilities). |
| Runic Bulwark | 15% random-Hex chance on a Perfect Block. [GamesRadar](https://www.gamesradar.com/games/action-rpg/blood-of-dawnwalker-perks-skills-abilities/). |
| Renounce Death | 10 seconds of Immortality and Lifesteal, once per combat. [GamesRadar](https://www.gamesradar.com/games/action-rpg/blood-of-dawnwalker-perks-skills-abilities/). |
| Tactical Mastery | Active Abilities cost 1 fewer charge, minimum 1. [Gamer Guides](https://www.gamerguides.com/the-blood-of-dawnwalker/guide/getting-started/character-development/best-swordmastery-perks-and-abilities). |
| Swordmastery acquisition | Seven initial/upgrade routes; Dirty Trick rank I needs no manual. [PC Gamer](https://www.pcgamer.com/games/rpg/blood-of-dawnwalker-swordmastery-ability-manual-locations/). |
| Witchcraft acquisition | Ten routes, including Anca's early unlocks. Burning Blood and Mercurial Fervour need no first manual; Life Lock replaces its first manual with a quest reward, retained as an acquisition requirement. [PC Gamer](https://www.pcgamer.com/games/rpg/blood-of-dawnwalker-witchcraft-ability-manual-locations/). |
| Vrakhir acquisition | Five routes. Scarlet Shield, Shadowstorm and Blood Surge rank I are direct blood rewards requiring no SP. The planner therefore counts no training time for receiving them; quest time is outside the training budget. Later ranks retain catalogue costs and Corruption requirements. [PC Gamer](https://www.pcgamer.com/games/rpg/blood-of-dawnwalker-vrakhir-blood-abilities/). |

The three blood rewards replace the generic first-rank 1 SP entries with zero; the source and reason are retained in their catalogue metadata. Starting availability does not establish free training for other skills, so their existing training costs were not changed. Unconfirmed costs remain: **8 SP entries, 19 training-time entries and 73 Corruption entries**. The last count includes special unlocks whose numeric threshold is unknown. These remain uncertain in the calculator.

Exact numbers for Aether Cascade, Entwined Torment and Lethal Crescendo were not independently established in this pass. Some fan sites also list casting costs, but rank scaling and conflicting descriptions prevent their use as a reliable combat-cost formula. These values remain unconfirmed.

## Effect accumulation

Values represent the state after the selected rank. A new rank replaces the previous value of the same statistic and retains other previously unlocked statistics. Examples from the saved tables:

| Skill | Rule |
|---|---|
| Endless Effort | Maximum Stamina +25/50/75/100%; ranks do not add together |
| Fate's Favour | IV retains the 18% Critical Hit chance from III and adds 25% Weapon Critical Damage |
| Perfect Block | IV retains +60% Stamina Restoration from III and grants +100% Activation Charge Restoration |
| Pack Mule | Carry Weight +30/+60/+100, without repeated addition |
| Sustained Focus | Charge capacity 2/2/3/4; one full charge at combat start from II onward |
| Forbidden Sigils / Master Fencer / Vrakhiri Might | 2/3/4 total slots |
| Lasting Malediction | IV retains +40% Duration and adds a conditional extension |
| Renewed Focus | III retains +30% passive Restoration and adds +50% Restoration from Attacks |
| Unholy Fervour | Charge refund chance 20/40%, not 60% |
| Bewitching Influence | Retains the 15% buying discount, 15% selling bonus and then special offers |
| Growing Momentum | +4% Damage per Attack up to +20%; II adds -8% Stamina cost per Attack up to -50% |

Permanent modifiers and conditional bonuses remain separate. Precision depends on changing Attack directions, Counterattack on a Perfect Block, Crimson Feast on Human Blood, Wild Blood on Animal Blood and Unnatural Resilience on an active Witchcraft Ability. Cross-source stacking, resistances, equipment and final damage per hit are not modeled without a confirmed formula.

## Values still requiring verification

- Most individual vampiric Corruption thresholds. Known thresholds are included; unconfirmed thresholds remain unknown.
- Initial ranks available without a manual for some skills. Published panels were used for the first two ranks of Endless Effort, Omniblock, Stinging Blade, Vigour, Witchcraft Mastery and Second Skin I; four ranks of Sustained Focus; and three ranks of Bewitching Influence. Other manual-based perks may have unknown initial availability. These published reference values determine manual counts; the calculator does not track manuals already collected in a playthrough.
- Zero training time for the first two ranks of the four basic Swordmastery perks was taken from published panels. Other missing time costs remain unknown.
- Final Witchcraft Mastery rank: the current Codex table lists 1 segment, while an official prerelease screenshot shows 2. The current catalogue value is used; the discrepancy is retained in the source metadata.
- Font of Life and Mandrake Ward: catalogues disagree on numerical effects, so the summary describes them qualitatively. Their acquisition requirements remain in the catalogue.
- Some numerical Ultimate parameters, bonuses per place of power or soul, bonus stacking formulas and durations of certain temporary effects.
- Individual vendor prices, actual Health and charge costs of casting each Active Ability, exact base Cooldowns and equipment statistics.

Costs use catalogue values only. The manual cost editor and per-skill unlock editor have been removed. Legacy cost overrides and unlock flags in older browser saves and JSON imports are ignored; learned ranks and other compatible build settings are retained. New exports omit both fields. Manuals are calculated beyond catalogue starting ranks. Quest rewards are planned requirements, and optional resource limits continue to check point/time budgets and known Corruption thresholds. Source URLs, per-skill references, warnings and animation attribution remain in the catalogue, animation metadata and this document; they are not displayed in the main interface.

## Visual references

The three saved game-panel screenshots determine perk rows, branch junctions, Ultimate ordering and the two ability columns. Node centres and connection paths now share a fixed 1320 × 850 canvas and one uniform scale, preventing the previous independent horizontal/vertical stretching. Full skill details appear in an interactive card on hover or keyboard focus; no permanent sidebar is reserved. Left click raises one rank and right click lowers one. Prerequisite learning, dependent removal and slot losses are previewed for confirmation before changing the build. Hover cards and separately opened skill dialogs use content-driven height with viewport-bounded maximums; only the description scrolls when needed. On devices with a fine primary pointer and hover, the hover card omits the bottom training-cost and rank-button panel. A compact Equip / Unequip button remains for learned slotted abilities. Touch devices and separately opened dialogs retain the full training controls.

- [Xbox Wire — Hands-on preview](https://news.xbox.com/en-us/2026/07/07/the-blood-of-dawnwalker-hands-on-preview/): official Witchcraft panel screenshot.
- [Shacknews — Ability slots](https://www.shacknews.com/article/150542/how-to-unlock-more-ability-slots-the-blood-of-dawnwalker): Vampirism panel.
- [Hack the Minotaur — Skill trees guide](https://hacktheminotaur.com/blood-of-dawnwalker/blood-of-dawnwalker-skill-trees-complete-guide/): Swordmastery panel.

The ability-icon import previously picked related-ability thumbnails or blank placeholders. **26 icons** were replaced with the distinct texture URLs explicitly present in the corresponding MetaBot skill pages, checked against their titles and the saved game asset names. Soul Reaping has no original icon in the saved Codex or MetaBot record; its tree node uses a question mark labelled **Icon unavailable**. This visual correction does not change rank effects, costs, prerequisites or existing builds.

### Header logo and manual acquisition links

The Character Planner title is a separate image-generated companion wordmark (`public/ui/character-planner-logo.png`), with the official game wordmark supplied as its typography and material reference. The original game logo is unchanged. Perks, Abilities and Ultimate perks headings are centered above their sections. The header wordmark is the unmodified official horizontal logo from the [PlayStation game page](https://www.playstation.com/en-us/games/the-blood-of-dawnwalker/), stored as `public/ui/dawnwalker-logo.png` (2858 × 592). Its promotional metadata identifies the image as `LOGO`. [Original PNG](https://image.api.playstation.com/vulcan/ap/rnd/202601/2919/61e47ed014809c32ec5a65e213e13c079e0e64f819fe176b.png). It is scaled in CSS and embedded in the offline file. The [Bandai Namco media gallery](https://en.bandainamcoent.eu/dawnwalker/the-blood-of-dawnwalker/media) also supplies a stacked emblem-and-wordmark variant; the horizontal variant is used to keep the header compact. Logo provenance is retained in local `research/header-manuals` records.

Skill Points, training time and Corruption are presented as compact icon–value–label rows in the tree toolbar, alongside the learned count, zoom and Fit tree. Labels hide based on the available tree width, retaining accessible text and hover titles. Manuals has its own dropdown, populated from the same selected-build manual totals as the summary. It preserves uncertain quantities as upper bounds and shows an empty state when no additional books are needed.

The dropdown's **Locations & vendors** URLs are copied from the actual manual links in the saved MetaBot skill pages; all 49 manual-bearing skills have an exact link. The mapping is kept in `app/manual-links.json`, with its source-page provenance and HTTP/title checks in local `research/header-manuals` records. All 49 pages returned HTTP 200 with the matching manual title on 8 September 2026. Known acquisition-guide links come from the existing per-skill acquisition metadata. The dropdown exposes these links intentionally; unrelated research references and animation attribution remain in documentation.

### Skill-card content and manual requirements

Skill cards display only ranks above the selected rank, directly in the scrollable description, with no acquisition accordion, rank accordion or introductory cost explanation. Current ability values remain visible when learned. A direct link to the skill’s manual appears at the bottom, using the same verified manual URL as the toolbar dropdown. Full acquisition notes remain in the catalogue; available guides are linked from the Manuals dropdown. Unknown per-rank book requirements retain their question mark and an explanatory hover label.

Each training-cost row now shows one manual where the catalogue establishes that its rank exceeds the skill's starting availability. Ranks within that availability show no manual requirement. Unknown starting availability displays `?` beside the book in both rank rows and the next-rank cost, consistent with the upper-bound manual total.

Fate's Favour has a confirmed manual item, but the saved Codex and GamesDB records do not give its initial manual-free ranks. The [Fextralife perk page](https://bloodofdawnwalker.wiki.fextralife.com/Fate%27s_Favour) and [manual page](https://bloodofdawnwalker.wiki.fextralife.com/Fate%27s_Favour_Manual), checked on 8 September 2026, also do not identify the required ranks. Its rank requirements therefore remain unconfirmed rather than being inferred from the existence of a manual, the perk tier, or the number of readable book parts. Source responses are retained locally in `research/manual-rank-indicators`.

### Resource icons

Skill Points (sun and crescent), Manuals (open book) and Time (hourglass) use the actual glyphs visible in the [official Xbox Wire gameplay screenshot](https://xboxwire.thesourcemediaassets.com/sites/2/2026/07/The-Blood-of-Dawnwalker-Screenshot-26-199957e4b246b93ca127.jpg) from the [7 July hands-on preview](https://news.xbox.com/en-us/2026/07/07/the-blood-of-dawnwalker-hands-on-preview/). The resource bar, build-cost summary and skill-card training costs share these icons. Skill cards display glyphs beside numeric costs; resource labels remain available to screen readers and as hover hints.

No separate original texture files were found. The unmodified 1920 × 1080 screenshot is bundled once and displayed through three clipped SVG viewports: Skill Points `(1536, 29, 32, 32)`, Manuals `(1354, 619, 29, 25)` and Time `(1615, 469, 12, 23)`, expressed as `(x, y, width, height)` in source pixels. An explicit rectangular clip path excludes adjacent screenshot pixels even when the glyph has a different aspect ratio from its icon box. The hourglass is trimmed by two source pixels on each side. Lighten blending suppresses the dark interface background. These are screenshot regions, not reconstructed vectors or claimed texture exports; sharpness is limited by the source capture. The source image, coordinates and SHA-256 are recorded locally in `research/resource-icons/provenance.json`.

### Skill-tree tab emblems

The Swordmastery, Witchcraft and Vampirism tabs use the neutral emblems shown in the game's Character menu. Swordmastery (sword) and Vampirism (fangs) come from the same [Xbox Wire screenshot](https://xboxwire.thesourcemediaassets.com/sites/2/2026/07/The-Blood-of-Dawnwalker-Screenshot-26-199957e4b246b93ca127.jpg) as the resource glyphs, at `(326, 121, 38, 38)` and `(553, 121, 38, 38)`. Witchcraft comes from the neutral tab in the [Swordmastery gameplay screenshot published by Hack the Minotaur](https://hacktheminotaur.com/wp-content/uploads/2026/07/blood-of-dawnwalker-swordmastery-skill-tree.webp), at `(152, 113, 40, 42)`.

Coordinates are `(x, y, width, height)` in the original 1920 × 1080 images. Both images are bundled unmodified, and the shared glyph renderer clips each emblem to its exact source rectangle. The existing tab selection highlight is preserved. Source URLs and file hashes are recorded locally in `research/tree-tab-icons/provenance.json`.

### Animated ability previews

All **27 abilities** include the gameplay GIF from their corresponding Fextralife page, starting with [Artery Strike](https://bloodofdawnwalker.wiki.fextralife.com/Artery_Strike). Each animation metadata entry retains its direct source link. Page HTML, original GIFs, original asset URLs and file hashes were saved locally on 8 September 2026. Perk illustrations retain their existing sources.

The GIFs were converted to silent H.264 MP4 clips for compact offline playback, preserving the sequence and timing and adding at most one border pixel for even video dimensions. Original GIFs total 64.09 MiB; the converted videos total 7.89 MiB. The first frame is included as a static poster. Only the selected ability mounts a player; system **Reduce Motion** disables automatic playback. Native controls provide pause, seeking and full screen. These animations are visual demonstrations, not evidence of rank values, training costs or damage formulas.

This is a fan-made tool. Game icons and illustrations belong to their respective rights holders; no open licence is claimed. The planner is not affiliated with or endorsed by Rebel Wolves or Bandai Namco.

### Build links and codes

Sharing uses the versioned `DW1-` format: a fixed registry of 90 skill IDs, 3 bits per rank, ordered ability slots and resource settings. The 55-byte payload includes a CRC-16 checksum and is encoded as URL-safe Base64 without padding (78 characters including the prefix). Its field order is fixed in `app/build-code.ts`. Imports validate the checksum, rank limits, prerequisites, Ultimate restrictions, equipment and resource ranges before replacing a build. Budgets may remain below planned costs, matching the resource editor. Original purchase order is not shared; the summary lists allocated ranks.

The code lives in the link fragment and is decoded locally. Loading a link adds the previous saved build to Undo and consumes the fragment so later refreshes retain edits. Local browser storage remains compatible with earlier saved builds; the public sharing UI uses links and codes instead of JSON files. Tests cover every rank of all 90 skills, all slot positions, resource boundaries, an independently generated binary fixture and malformed codes. Browser interaction testing has not been performed.

### Mouse node interaction

On devices with a fine pointer and hover support, skill nodes have no persistent selected state or pressed-toggle semantics. The hover highlight clears when the pointer leaves. Hover opens the skill card; left and right clicks keep their rank actions without leaving a node selected. The Selected legend is hidden in this mode. Touch selection, keyboard focus, learned/equipped styling, prerequisites and focus restoration from dialogs remain available. Pointer capability changes are observed without a page reload.

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
- Font of Life and Mandrake Ward: catalogues disagree on numerical effects, so the summary describes them qualitatively. Their acquisition requirements remain visible as read-only notes.
- Some numerical Ultimate parameters, bonuses per place of power or soul, bonus stacking formulas and durations of certain temporary effects.
- Individual vendor prices, actual Health and charge costs of casting each Active Ability, exact base Cooldowns and equipment statistics.

Costs use catalogue values only. The manual cost editor and per-skill unlock editor have been removed. Legacy cost overrides and unlock flags in older browser saves and JSON imports are ignored; learned ranks and other compatible build settings are retained. New exports omit both fields. Manuals are calculated beyond catalogue starting ranks. Quest rewards are planned requirements, and optional resource limits continue to check point/time budgets and known Corruption thresholds. Source URLs, per-skill references, warnings and animation attribution remain in the catalogue, animation metadata and this document; they are not displayed in the main interface.

## Visual references

The three saved game-panel screenshots determine perk rows, branch junctions, Ultimate ordering and the two ability columns. Node centres and connection paths now share a fixed 1320 × 850 canvas and one uniform scale, preventing the previous independent horizontal/vertical stretching. Full skill details appear in an interactive card on hover or keyboard focus; no permanent sidebar is reserved. Left click raises one rank and right click lowers one. Prerequisite learning, dependent removal and slot losses are previewed for confirmation before changing the build. Training controls remain fixed at the bottom of the card.

- [Xbox Wire — Hands-on preview](https://news.xbox.com/en-us/2026/07/07/the-blood-of-dawnwalker-hands-on-preview/): official Witchcraft panel screenshot.
- [Shacknews — Ability slots](https://www.shacknews.com/article/150542/how-to-unlock-more-ability-slots-the-blood-of-dawnwalker): Vampirism panel.
- [Hack the Minotaur — Skill trees guide](https://hacktheminotaur.com/blood-of-dawnwalker/blood-of-dawnwalker-skill-trees-complete-guide/): Swordmastery panel.

The ability-icon import previously picked related-ability thumbnails or blank placeholders. **26 icons** were replaced with the distinct texture URLs explicitly present in the corresponding MetaBot skill pages, checked against their titles and the saved game asset names. Soul Reaping has no original icon in the saved Codex or MetaBot record; its tree node uses a question mark labelled **Icon unavailable**. This visual correction does not change rank effects, costs, prerequisites or existing builds.

### Resource icons

Skill Points (sun and crescent), Manuals (open book) and Time (hourglass) use the actual glyphs visible in the [official Xbox Wire gameplay screenshot](https://xboxwire.thesourcemediaassets.com/sites/2/2026/07/The-Blood-of-Dawnwalker-Screenshot-26-199957e4b246b93ca127.jpg) from the [7 July hands-on preview](https://news.xbox.com/en-us/2026/07/07/the-blood-of-dawnwalker-hands-on-preview/). The resource bar, build-cost summary and skill-card training costs share these icons. Skill cards display glyphs beside numeric costs; resource labels remain available to screen readers and as hover hints.

No separate original texture files were found. The unmodified 1920 × 1080 screenshot is bundled once and displayed through three clipped SVG viewports: Skill Points `(1536, 29, 32, 32)`, Manuals `(1354, 619, 29, 25)` and Time `(1615, 469, 12, 23)`, expressed as `(x, y, width, height)` in source pixels. An explicit rectangular clip path excludes adjacent screenshot pixels even when the glyph has a different aspect ratio from its icon box. The hourglass is trimmed by two source pixels on each side. Lighten blending suppresses the dark interface background. These are screenshot regions, not reconstructed vectors or claimed texture exports; sharpness is limited by the source capture. The source image, coordinates and SHA-256 are recorded locally in `research/resource-icons/provenance.json`.

### Animated ability previews

All **27 abilities** include the gameplay GIF from their corresponding Fextralife page, starting with [Artery Strike](https://bloodofdawnwalker.wiki.fextralife.com/Artery_Strike). Each animation metadata entry retains its direct source link. Page HTML, original GIFs, original asset URLs and file hashes were saved locally on 8 September 2026. Perk illustrations retain their existing sources.

The GIFs were converted to silent H.264 MP4 clips for compact offline playback, preserving the sequence and timing and adding at most one border pixel for even video dimensions. Original GIFs total 64.09 MiB; the converted videos total 7.89 MiB. The first frame is included as a static poster. Only the selected ability mounts a player; system **Reduce Motion** disables automatic playback. Native controls provide pause, seeking and full screen. These animations are visual demonstrations, not evidence of rank values, training costs or damage formulas.

This is a fan-made tool. Game icons and illustrations belong to their respective rights holders; no open licence is claimed. The planner is not affiliated with or endorsed by Rebel Wolves or Bandai Namco.

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

The normalized catalogue contains **90 skills / 274 ranks**: 63 perks and 27 abilities. The saved tables provide SP costs for 266 ranks. Astral Communion and Compel Soul are abilities without a common slot. The supplied game cards below resolve their upgrade costs and ranks II–IV, correcting incorrectly accumulated GamesDB values. The additional first-rank screenshot confirms Astral Communion I at +0.4% per place of power. Their per-use bonuses are not multiplied into character totals because use counts are not tracked.

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
| Witchcraft acquisition | Ten routes, including Anca's early unlocks. Burning Blood and Mercurial Fervour need no first manual; The guide describes a Life Lock quest unlock; the later user-supplied game card below instead shows a manual requirement at every rank. [PC Gamer](https://www.pcgamer.com/games/rpg/blood-of-dawnwalker-witchcraft-ability-manual-locations/). |
| Vrakhir acquisition | Five routes. Scarlet Shield, Shadowstorm and Blood Surge rank I are direct blood rewards requiring no SP. The planner therefore counts no training time for receiving them; quest time is outside the training budget. Later ranks retain catalogue costs and Corruption requirements. [PC Gamer](https://www.pcgamer.com/games/rpg/blood-of-dawnwalker-vrakhir-blood-abilities/). |

The three blood rewards replace the generic first-rank 1 SP entries with zero; the source and reason are retained in their catalogue metadata. Starting availability does not establish free training for other skills, so their existing training costs were not changed. After the user-supplied game cards below, unconfirmed costs remain: **0 SP entries, 7 training-time entries and 73 Corruption entries**. The last count includes special unlocks whose numeric threshold is unknown. These remain uncertain in the calculator.

Exact numbers for Aether Cascade and Entwined Torment were not independently established in the wiki pass; they are now verified by the user-supplied game cards below. Lethal Crescendo remains unconfirmed. Some fan sites also list casting costs, but rank scaling and conflicting descriptions prevent their use as a reliable combat-cost formula. These values remain unconfirmed.

## User-supplied Witchcraft game cards: 8 September 2026

Twenty original screenshots cover **20 Witchcraft perks / 49 ranks**. Their descriptions, effects, rank counts, SP costs, training time and leading availability icons were transcribed and compared with the catalogue. All SP and time costs matched, including **1 segment for Witchcraft Mastery IV**. The user confirmed that no Witchcraft manuals had been read before these captures.

- **Anytime:** Forager, Bewitching Influence, Herbal Remedies I, Medicus I, Amalgam, Herbal Remedies II and Medicus II. Their effects now remain in the Night summary. The other 13 captured perks are **Day only**; card labels and effect filtering use the same per-skill rule.
- **Manual-free starting ranks:** Forager I, Unnatural Resilience I, Forbidden Sigils I, Witchcraft Mastery I–II and Bewitching Influence I–III. The first Forbidden Sigils row has a prerequisite lock; its later rows have book icons. The remaining 12 captured regular perks require a manual for every rank. Ultimate locks remain separate from manuals. This establishes book requirements for all 17 captured regular perks and removes 39 previously unknown per-rank requirements.
- **Witchcraft Mastery:** the card shows 110 additional Damage, with a 50% chance from II and 100% at IV. III retains the prior 50% effect. The displayed 110 is recorded as observed in this character's card; its possible scaling with other statistics has not been established and no universal damage formula is inferred.
- **Entwined Torment:** the first Witchcraft Ability used in combat targets 2 enemies.
- **Aether Cascade:** +20% Witchcraft Ability Damage for each Witchcraft Ability used, up to +100%, resetting after combat. The summary retains this as a conditional effect rather than permanent Damage.
- **Runic Bulwark:** the card confirms the existing 15% random-Hex chance on a Perfect Block. Its rank row now preserves the game's “Unlocks Ultimate” wording.

The unmodified PNGs, hashes, transcriptions, original comparison snapshots and the player's manual baseline are retained under local `research/user-game-screenshots/2026-09-08`. Catalogue additions are reproducible from `research/user-game-screenshots/verified-skills.json` and take precedence over web tables only for the observed fields. Each affected skill carries its screenshot reference and verified fields as metadata. Screenshots and local research records are not published. **Font of Life is unchanged at the user's request.** The ability cards supplied afterwards are documented below.

## User-supplied Witchcraft ability cards: 8 September 2026

Seventeen additional screenshots cover all **10 Witchcraft abilities / 40 ranks**, including paired scroll positions. The user explicitly confirmed that **Compel Soul I, Astral Communion I and Burning Blood I are already learned from the start**. New builds, cleared builds, restored local builds and imported links retain these three ranks. They cost no SP, training time or manuals and cannot be removed; their upgrades remain optional. Burning Blood is learned without automatically occupying an equipped slot.

- **Compel Soul:** ranks II–IV grant −1% / −1.5% / −2% permanent Witchcraft Ability Cooldown per soul, with 1 SP and no training time each. The additional first-rank screenshot directly confirms −0.5% per soul at I. The character's current use count is not imported.
- **Astral Communion:** ranks II–IV grant +0.8% / +1.2% / +1.6% permanent Witchcraft Ability Damage per place of power, with 1 SP and no training time each. An additional screenshot directly shows the learned rank-I row at **+0.4% per place of power**. All four per-place rates are now verified from the game cards.
- **Burning Blood:** displayed Damage per second is 66 / 68 / 70 / 79; durations are 10 / 12 / 14 / 16 seconds. On-death transfer starts at III. Its three paid upgrades cost 1 / 2 / 3 SP and 1 / 1 / 2 training segments.
- **Life Lock:** reflection is 100 / 120 / 160 / 200%, blocking 2 / 3 / 3 / 4 hits for 90 seconds. **Every rank shows a book icon**, so the previous first-rank manual exemption is removed. The guide's quest route remains an acquisition note, without replacing the observed manual requirement.
- **Soul Reaping:** 40 / 47 / 55 / 62 Lifesteal per second over 18 / 24 / 30 / 36 seconds. III transfers 20% of received Damage to the target; IV transfers 40% and heals 500 on the target's death.
- **Ravenous Flock:** displayed Area Damage is 110 / 121 / 132 / 143, ending after 1 / 2 / 3 / 4 hits, with 100% Critical Hits on the target. Duration is **20 seconds at every rank**, replacing the decoded 4 / 4 / 8 / 8-second values.
- **Soul Stigma, Unholy Vitality and Cycle of Ruin:** full rank text, durations, transfers, healing and final-rank conditions match the game cards. Each rank requires a manual. Unholy Vitality and Cycle of Ruin work passively only while equipped.
- **Mercurial Fervour:** ranks cost 1 SP each with **no training time**. Only I is available without a manual; it is not initially learned. It uses no common slot.

The cards also establish the following displayed combat values. These are shown separately from SP and training costs; no equipment scaling, perk-adjusted casting cost, usage count or complete damage formula is inferred.

| Ability | Cooldown | Activation Charges | Health cost |
|---|---:|---:|---:|
| Burning Blood | 30 s | 1 | 15% |
| Life Lock | 30 s | 2 | 10% |
| Soul Reaping | 45 s | 2 | 15% |
| Ravenous Flock | 45 s | 2 | 40% |
| Soul Stigma | 35 s | 1 | 35% |

No hourglass cost is shown on Compel Soul, Astral Communion or Mercurial Fervour upgrade rows; their training time is recorded as zero. The user explicitly clarified the independent cost symbols: a leading book means a manual is needed, while SP and any training time appear in parentheses at the end. Additional Mercurial Fervour and Cycle of Ruin captures confirm that their current cost tables already match this interpretation. The three learned first ranks are directly visible as filled diamonds in the additional captures, retained under local `research/user-game-screenshots/2026-09-08/witchcraft-starting-ranks`. Zero-time rows omit the hourglass in the skill card. Originals, hashes, combined transcriptions, comparison snapshots and evidence limits are retained locally under `research/user-game-screenshots/2026-09-08/witchcraft-abilities`. The existing catalogue generator applies the verified ability fields after web additions. This batch left Font of Life and all other trees unchanged. Swordmastery was subsequently checked in the batch below.

## User-supplied Swordmastery game cards: 8 September 2026

The 34 initial screenshots and two supplemental captures cover all **29 Swordmastery skills / 96 ranks**: 19 regular perks, three Ultimates and seven abilities. Long cards were combined across their overlapping scroll positions, including three captures for Dirty Trick. All cards show **Anytime**. The original PNGs, hashes, independent transcriptions, player context and comparisons are retained locally under `research/user-game-screenshots/2026-09-08/swordmastery` and `swordmastery-update`. They feed the existing verified catalogue overrides without publishing the screenshots.

- **Manuals:** the user confirms one Charge manual had been read before these screenshots. Charge I therefore still requires a manual in a new build; its hollow diamond reflects the captured playthrough. Every Charge rank costs one manual. Dirty Trick needs manuals only at II–IV; the other five Swordmastery abilities need one at every rank.
- **Perk manual availability:** Endless Effort, Omniblock, Stinging Blade, Vigour, Fate's Favour, Fleet of Foot, Pack Mule, Perfect Block, Perfect Riposte and Second Skin I have two initial ranks without manuals. Master Fencer has one; Sustained Focus has four. The other seven regular perks require a book at every rank. Prerequisite and Ultimate locks are distinct from book icons. Together with the earlier Witchcraft cards, this resolves all **66 previously unknown per-rank book requirements** in the catalogue.
- **Dirty Trick I:** the filled diamond shows a learned rank, and the user confirms it is learned by default. It joins the three starting Witchcraft abilities at zero SP, training time and manuals. New, cleared, restored and imported builds keep all four ranks; none is automatically equipped. Dirty Trick upgrades cost 1 / 2 / 3 SP, 1 / 1 / 2 training segments and one manual each.
- **Dirty Trick effects:** observed Damage is **110 / 137 / 165 / 192**, replacing the decoded placeholder. Stun ends after 3 / 4 / 5 / 6 hits, affects an area from III, and lasts 15 / 20 / 25 / 30 seconds. Active Ability Damage vulnerability is 10 / 20 / 30 / 50%. IV reduces the charge cost of Active Abilities used on stunned enemies by one, minimum one. These are displayed character-card values; no equipment scaling formula is inferred.
- **Training time:** the first two ranks of Endless Effort, Omniblock, Stinging Blade and Vigour show SP without an hourglass, confirming zero time. Sustained Focus costs one time segment at all four ranks. Every other visible Swordmastery SP/time entry matches the previous table; the already-learned Dirty Trick I cost is established by user context instead of an unlearned cost row.
- **Long-card effects:** Charge III/IV retain 2-second Stun and 100% Bleed chance, adding 66% Bleed Duration; IV restores one charge on kill. Artery Strike IV doubles its 50% Decapitation chance on bleeding enemies. Broad Swing III/IV adds 10% Damage per enemy hit. Adrenaline Rush keeps its 6-second duration at every rank. Swiftness IV gives 30% Attack Speed, 5% Critical Hit chance and no Stamina cost on Critical Hits for 12 seconds. Walking Fortress IV restores 25% of a charge, reduces cooldowns by two seconds after either block type, and discounts the next ability within five seconds of a Perfect Block, minimum one charge. Complete rank descriptions remain in the cards; these equipped, conditional effects are not added to permanent perk totals.
- **Ultimates:** Last Stand confirms +100% Weapon Damage below 30% Health; Sword Sage resets Active Ability Cooldowns on an enemy kill; Tactical Mastery reduces charge costs by one, minimum one. Each costs 4 SP and 2 training segments, with no manual. Their rank rows preserve the game's "Unlocks Ultimate" wording.

| Ability | Displayed Cooldown | Activation Charges |
|---|---:|---:|
| Dirty Trick | 30 s | 1 |
| Broad Swing | 40 s | 2 |
| Charge | 20 s | 1 |
| Artery Strike | 25 s | 2 |

No Health cost is shown for these four abilities. Casting resources are displayed separately from learning costs, without applying an unverified perk-scaling formula. Adrenaline Rush, Swiftness and Walking Fortress work passively only while equipped in the Active Abilities panel; they retain their ability slots and angled frames. All Witchcraft/Vampirism records and image/video assets are unchanged by this Swordmastery update.

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
- Manual requirements are resolved for all manual-bearing skills by the game cards and player context above. The calculator counts the books required for the selected ranks from their initial availability; it does not track books already collected or read in a playthrough.
- Zero training time for the first two ranks of the four basic Swordmastery perks was taken from published panels. Other missing time costs remain unknown.
- Final Witchcraft Mastery rank: the user's release-game card confirms 1 segment, resolving the previous conflict with the official prerelease screenshot showing 2.
- Font of Life and Mandrake Ward: catalogues disagree on numerical effects, so the summary describes them qualitatively. Their acquisition requirements remain in the catalogue.
- Some numerical Ultimate parameters, bonuses per place of power or soul, bonus stacking formulas and durations of certain temporary effects.
- Individual vendor prices, casting costs and cooldowns not covered by the nine observed active cards above, perk/equipment scaling, and equipment statistics.

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

Fate's Favour's initial manual-free ranks were absent from the saved Codex, GamesDB and Fextralife records. The later user-supplied Swordmastery card above resolves the gap: I–II have prerequisite locks, while III–IV require books. The user had not read its manuals before the capture. This confirms two manual-free initial ranks; the number was not inferred from the existence of a book or its number of readable parts. Earlier source responses remain retained locally in `research/manual-rank-indicators`.

### Unlearned rank rows and node frames

Unlearned rank rows follow the supplied game-card layout. Their left marker is a book when a manual is required, a hollow diamond when no manual or other requirement blocks that rank, or a lock for other unmet requirements. Unknown manual requirements retain a question mark beside the book. SP and any nonzero or unknown training-time cost appear in parentheses at the end of the effect text, with each parenthesized value kept together while wrapping. The separate cost footer and visible rank-number boxes have been removed from these rows; rank numbers remain available to screen readers. The separate touch/dialog training controls retain their existing cost summary.

Perk nodes use circular outer and inner frames. Ability nodes retain the existing angled shape, including abilities that work passively while equipped. Hover, learned, equipped and locked colors and interactions remain unchanged. The source icons and screenshots are unchanged; only their frames and card layout are updated.

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

Sharing uses the versioned `DW1-` format: a fixed registry of 90 skill IDs, 3 bits per rank, ordered ability slots and resource settings. The 55-byte payload includes a CRC-16 checksum and is encoded as URL-safe Base64 without padding (78 characters including the prefix). Its field order is fixed in `app/build-code.ts`. Imports validate the checksum, rank limits, prerequisites, Ultimate restrictions, equipment and resource ranges before replacing a build. Legacy codes are checked against their original ranks and slots before Dirty Trick I and the three free starting Witchcraft ranks are added; the DW1 wire format is unchanged. Budgets may remain below planned costs, matching the resource editor. Original purchase order is not shared; the summary lists allocated ranks.

The code lives in the link fragment and is decoded locally. Loading a link adds the previous saved build to Undo and consumes the fragment so later refreshes retain edits. Local browser storage remains compatible with earlier saved builds; the public sharing UI uses links and codes instead of JSON files. Tests cover every rank of all 90 skills, all slot positions, resource boundaries, an independently generated binary fixture and malformed codes. Browser interaction testing has not been performed.

### Mouse node interaction

On devices with a fine pointer and hover support, skill nodes have no persistent selected state or pressed-toggle semantics. The hover highlight clears when the pointer leaves. Hover opens the skill card; left and right clicks keep their rank actions without leaving a node selected. The Selected legend is hidden in this mode. Touch selection, keyboard focus, learned/equipped styling, prerequisites and focus restoration from dialogs remain available. Pointer capability changes are observed without a page reload.

# Sources and data limitations

Skill data snapshot: **8 September 2026**; quest data snapshot: **9 September 2026**. Retrieved pages and structured source snapshots are retained locally in `research/`; they are not included in the published site repository. The planner makes no catalogue requests while running.

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
| Vrakhir acquisition | Five routes from [PC Gamer](https://www.pcgamer.com/games/rpg/blood-of-dawnwalker-vrakhir-blood-abilities/). The previous inference that three blood rewards waived the first SP cost is superseded by the user-supplied game cards below: all five skull unlocks show 1 SP and no training time. Quest time is outside the training budget. |

The later user-supplied game cards take precedence over these guide-based inferences. All **274 SP costs and 274 training-time costs** are now established. Mandrake Ward is the only remaining unknown Corruption requirement. Five skull unlocks have no displayed numeric threshold and are modeled separately from unknown Corruption; acquiring them is a planned special requirement, followed by the observed 1 SP training cost.

Exact numbers for Aether Cascade, Entwined Torment and Lethal Crescendo were not independently established in the wiki pass; they are now verified by the user-supplied game cards below. Fourteen ability cards also establish displayed casting values. These observations do not establish a universal combat-cost or equipment-scaling formula.

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

## User-supplied Vampirism game cards: 8 September 2026

Thirty-eight original screenshots cover **29 Vampirism skills / 87 ranks**, including all ten abilities. Piercing Shriek spans four scroll positions and Scarlet Shield spans three. All supplied cards show **Night only**. Mandrake Ward is absent and unchanged. Together with the earlier batches, 88 skills and 272 ranks now have direct user-supplied game-card evidence.

- **Voracious Bite I** is shown learned and the user confirms it is learned by default. It joins the four existing starting abilities at zero SP, time and manuals, survives Clear and legacy build imports, and cannot be removed. It uses no common slot and appears in the Night ability summary automatically.
- **Special skull unlocks:** Shadowstorm, Piercing Shriek, Blood Surge, Mesmerise and Scarlet Shield I explicitly cost **1 SP and zero training time**. The user confirms that their skull requires drinking Vrakhir blood, distinct from a numbered Corruption gate. `bloodUnlock` records this distinction while the numeric field remains unset; these five entries are not counted as unknown thresholds. Earlier acquisition guides remain as route notes. The three prior zero-SP blood-reward entries are corrected to one SP. The planner does not track completed blood acquisitions.
- **Damage values:** Voracious Bite shows 156 / 190 / 224 / 257 Damage and restores 60 / 80 / 100 / 120% of a Health Segment. Blood Surge deals 224 / 280 / 336 / 392 Area Damage in 3 / 4 / 5 / 6 metres, with 784 / 952 / 1,120 / 1,288 Damage to bosses. Death from Above deals 728 / 840 / 952 / 1,064 Damage to bosses and tough enemies. Shred IV deals 112 Damage when Bleed is reapplied. These replace decoded placeholders with observed card values, without inferring equipment scaling.
- **Lethal Crescendo:** +20% Claw Damage for each enemy killed or Boss Health Segment depleted, stacking until combat ends. This is a conditional Night effect with no invented stack cap. Renounce Death confirms 10 seconds, and Sanguine Renewal confirms the Voracious Bite cooldown reset.
- **Wild Blood and Crimson Feast:** animal/human blood buffs last **3 world-time segments**. The duration is shown in their effect conditions and is separate from training time or combat seconds. Higher ranks retain earlier distinct bonuses.
- **Long descriptions:** the full reflection, duration and final-rank extension of Piercing Shriek, the block chances and healing of Scarlet Shield, and the highest-rank bonuses of Mesmerise and Death from Above are preserved. Crimson Rush, Scarlet Shield and Shred work passively only while equipped. Voracious Bite, Shapeshift and Death from Above use no common slot.
- **Training:** Shapeshift costs 1 SP and no time at every rank. Death from Above IV confirms its irregular 2 SP / 1 segment cost. All other visible costs match the previous tables except the three corrected initial blood rewards. The seven previously unknown time entries are resolved; the default Voracious Bite I cost comes from user context rather than an unlearned price row.

| Skill | Corruption by rank |
|---|---|
| Nourishing Blood | 0 / 3 / 8 |
| Wild Blood; Crimson Feast | 2 / 5 / 10 |
| Hastened Corruption | 1 / 4 / 6 |
| Vrakhiri Might | 4 / 7 / 11 |
| Lasting Blood | 5 / 10 |
| Endless Ferocity | 6 / 12 |
| Endless Hunger | 0 / 5 / 12 |
| Closing Wounds | 3 / 6 |
| Blood Theft | 4 / 8 / 11 |
| Shadow Dweller | 0 / 11 |
| Dimension Reach | 2 / 6 / 13 |
| Razorsharp Claws | 0 / 4 / 9 / 12 |
| Restless Claws | 1 / 4 / 9 |
| Clawpierce | 2 / 7 / 13 |
| Dancing Claws | 9 / 14 |
| All three Ultimates | 15 |
| Voracious Bite | starting / 3 / 8 / 14 |
| Shadowstorm | skull / 8 / 11 / 14 |
| Piercing Shriek | skull / 7 / 11 / 13 |
| Blood Surge | skull / 10 / 12 / 14 |
| Mesmerise | skull / 9 / 12 / 14 |
| Death from Above | 3 / 7 / 10 / 13 |
| Scarlet Shield | skull / 6 / 10 / 13 |
| Crimson Rush | 3 / 7 / 11 / 14 |
| Shred | 1 / 5 / 9 / 13 |
| Shapeshift | 1 / 6 / 9 / 12 |

Zero denotes the existing initial numeric availability confirmed by a hollow diamond; a skull is a separate special unlock, not a numeric zero or a spent resource. Numeric thresholds continue to be checked in My resources mode and summarized as the maximum required value. Skull rows display a skull marker instead of a fictitious Corruption value. Mandrake Ward's unresolved requirement retains its question mark.

| Ability | Displayed Cooldown | Activation Charges | Health cost |
|---|---:|---:|---:|
| Voracious Bite | 30 s | 1 | none shown |
| Shadowstorm | 90 s | 2 | 15% |
| Piercing Shriek | 30 s | 1 | 20% |
| Blood Surge | 30 s | 3 | 25% |
| Mesmerise | 45 s | 2 | 30% |

All original images, hashes, combined transcriptions, user confirmation and evidence limits are retained locally under `research/user-game-screenshots/2026-09-08/vampirism`. Pre-edit files, diffs, validation and publication records are under `vampirism-update`. The verified override file reproduces the catalogue offline. Swordmastery, Witchcraft, Mandrake Ward and all media assets are unchanged by this batch.

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

- Mandrake Ward's Corruption requirement. Every supplied numeric Vampirism threshold is recorded; the five skull unlocks are modeled as separate special acquisition requirements.
- Manual requirements are resolved for all manual-bearing skills by the game cards and player context above. The calculator counts the books required for the selected ranks from their initial availability; it does not track books already collected or read in a playthrough.
- Zero training time for the first two ranks of the four basic Swordmastery perks was taken from published panels. Other missing time costs remain unknown.
- Final Witchcraft Mastery rank: the user's release-game card confirms 1 segment, resolving the previous conflict with the official prerelease screenshot showing 2.
- Font of Life and Mandrake Ward: catalogues disagree on numerical effects, so the summary describes them qualitatively. Their acquisition requirements remain in the catalogue.
- Effects whose cards omit numerical values, formulas for stacking different effects, and equipment scaling. Per-soul and per-place rates are verified, but usage counts are not tracked.
- Individual vendor prices, casting costs and cooldowns not covered by the fourteen observed active cards above, perk/equipment scaling, and equipment statistics.

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

Perks and active abilities use circular bodies with four cardinal spikes. Only the eight passive abilities in the right columns use plain circular frames. Hover adds a separate golden circular halo, with the dark interior and original artwork retained. The three original frame references are retained in `research/node-frames-and-blood-unlocks`, alongside their hashes. Node size, placement, icons, rank changes and equip behavior are unchanged.


### Vrakhir blood clarification

The user identifies the first-rank skill skull as a requirement to drink a vampire's blood. It appears on the five unlearned ability nodes and their first-rank rows. Their cards have a collapsed **Drink Vrakhir blood** section with acquisition information and a source link. Planning still permits these future acquisitions; completed blood acquisitions are not tracked.

| Ability | Blood or quest route | Evidence |
|---|---|---|
| Scarlet Shield | Ambrus, directly after the fight or by phial | [PC Gamer](https://www.pcgamer.com/games/rpg/blood-of-dawnwalker-vrakhir-blood-abilities/) |
| Shadowstorm | Bakir, directly after the fight or by phial | [PC Gamer](https://www.pcgamer.com/games/rpg/blood-of-dawnwalker-vrakhir-blood-abilities/) |
| Blood Surge | Xanthe, directly after the fight or by phial | [PC Gamer](https://www.pcgamer.com/games/rpg/blood-of-dawnwalker-vrakhir-blood-abilities/) |
| Piercing Shriek | Phial of Brencis's Blood; alternatively Our Rotten Roots, involving Isbrand | [Item description](https://dawnwalkerdb.com/items/phial-of-brenciss-blood), [quest walkthrough](https://www.powerpyx.com/blood-of-dawnwalker-our-rotten-roots-walkthrough/) |
| Mesmerise | Lacra's blood during The Night of Horrors, or her blood phial | [Quest walkthrough](https://www.powerpyx.com/blood-of-dawnwalker-the-night-of-horrors-walkthrough/), [item description](https://dawnwalkerdb.com/items/phial-of-lacras-blood) |

The older PC Gamer wording attributed Mesmerise to eating the mandrake. PowerPyx distinguishes the two actions: Lacra's blood grants Mesmerise; the mandrake grants Mandrake Ward. Only Mesmerise's acquisition wording is corrected here; Mandrake Ward's unobserved rank data remain unchanged. The observed first-rank training prices remain 1 SP and zero time. No free direct-blood acquisition behavior has been verified in this session.

Colored enemy skulls indicate level ranges relative to Coen; red means above his level range according to [PowerPyx](https://www.powerpyx.com/the-blood-of-dawnwalker-trophy-guide-roadmap/). Exact color-to-level differences remain unconfirmed. Enemy indicators are not used as skill costs or Corruption thresholds.

### Resource icons

Skill Points (sun and crescent), Manuals (open book) and Time (hourglass) use the actual glyphs visible in the [official Xbox Wire gameplay screenshot](https://xboxwire.thesourcemediaassets.com/sites/2/2026/07/The-Blood-of-Dawnwalker-Screenshot-26-199957e4b246b93ca127.jpg) from the [7 July hands-on preview](https://news.xbox.com/en-us/2026/07/07/the-blood-of-dawnwalker-hands-on-preview/). The resource bar, build-cost summary and skill-card training costs share these icons. Skill cards display glyphs beside numeric costs; resource labels remain available to screen readers and as hover hints.

No separate original texture files were found. The unmodified 1920 × 1080 screenshot is bundled once and displayed through three clipped SVG viewports: Skill Points `(1536, 29, 32, 32)`, Manuals `(1354, 619, 29, 25)` and Time `(1615, 469, 12, 23)`, expressed as `(x, y, width, height)` in source pixels. An explicit rectangular clip path excludes adjacent screenshot pixels even when the glyph has a different aspect ratio from its icon box. The hourglass is trimmed by two source pixels on each side. Lighten blending suppresses the dark interface background. These are screenshot regions, not reconstructed vectors or claimed texture exports; sharpness is limited by the source capture. The source image, coordinates and SHA-256 are recorded locally in `research/resource-icons/provenance.json`.

### Skill-tree tab emblems

The Swordmastery, Witchcraft and Vampirism tabs use lossless PNG crops of the neutral emblems in the two user-supplied 3840 × 2160 screenshots. No generation, resizing, recoloring, sharpening or background removal is applied; the decoded pixels match the source rectangles exactly. The existing SVG display size, lighten blending and tab selection highlight are retained.

| Emblem | User screenshot | Crop `(x, y, width, height)` | Output |
|---|---|---|---|
| Witchcraft | IMG_6627.JPG | `(322, 241, 84, 84)` | `public/ui/tree-witchcraft.png` |
| Swordmastery | IMG_6627.JPG | `(710, 241, 84, 84)` | `public/ui/tree-swordmastery.png` |
| Vampirism | IMG_6626.JPG | `(1186, 241, 84, 84)` | `public/ui/tree-vampirism.png` |

Original screenshots, crop coordinates and source/output hashes are retained in `research/tree-tab-icons-user-crops`. These replace the earlier 1920 × 1080 web screenshot regions documented in `research/tree-tab-icons/provenance.json`. The old Swordmastery screenshot, no longer needed by the interface, is retained with the research files. The original Xbox Wire screenshot remains bundled for the Skill Points, Manual and Time glyphs.

The Witchcraft ability columns follow the user's corrected order, read left to right and top to bottom: Compel Soul, Astral Communion, Burning Blood, Life Lock, Soul Reaping, Ravenous Flock, Soul Stigma, Unholy Vitality, Cycle of Ruin, Mercurial Fervour. The 8 September correction moves Life Lock to fourth, Soul Reaping to fifth and Unholy Vitality to eighth; skill data and behavior are unchanged.

### Animated ability previews

All **27 abilities** include the gameplay GIF from their corresponding Fextralife page, starting with [Artery Strike](https://bloodofdawnwalker.wiki.fextralife.com/Artery_Strike). Each animation metadata entry retains its direct source link. Page HTML, original GIFs, original asset URLs and file hashes were saved locally on 8 September 2026. Perk illustrations retain their existing sources.

The GIFs were converted to silent H.264 MP4 clips for compact offline playback, preserving the sequence and timing and adding at most one border pixel for even video dimensions. Original GIFs total 64.09 MiB; the converted videos total 7.89 MiB. The first frame is included as a static poster. Only the selected ability mounts a player; system **Reduce Motion** disables automatic playback. Native controls provide pause, seeking and full screen. These animations are visual demonstrations, not evidence of rank values, training costs or damage formulas.

This is a fan-made tool. Game icons and illustrations belong to their respective rights holders; no open licence is claimed. The planner is not affiliated with or endorsed by Rebel Wolves or Bandai Namco.

### Build links and codes

Sharing uses the versioned `DW1-` format: a fixed registry of 90 skill IDs, 3 bits per rank, ordered ability slots and resource settings. The 55-byte payload includes a CRC-16 checksum and is encoded as URL-safe Base64 without padding (78 characters including the prefix). Its field order is fixed in `app/build-code.ts`. Imports validate the checksum, rank limits, prerequisites, Ultimate restrictions, equipment and resource ranges before replacing a build. Legacy codes are checked against their original ranks and slots before Dirty Trick I, Voracious Bite I and the three free starting Witchcraft ranks are added; the DW1 wire format is unchanged. Budgets may remain below planned costs, matching the resource editor. Original purchase order is not shared; the summary lists allocated ranks.

The code lives in the link fragment and is decoded locally. Loading a link adds the previous saved build to Undo and consumes the fragment so later refreshes retain edits. Local browser storage remains compatible with earlier saved builds; the public sharing UI uses links and codes instead of JSON files. Tests cover every rank of all 90 skills, all slot positions, resource boundaries, an independently generated binary fixture and malformed codes. Browser interaction testing has not been performed.

### Mouse node interaction

On devices with a fine pointer and hover support, skill nodes have no persistent selected state or pressed-toggle semantics. The hover highlight clears when the pointer leaves. Hover opens the skill card; left and right clicks keep their rank actions without leaving a node selected. The Selected legend is hidden in this mode. Touch selection, keyboard focus, learned/equipped styling, prerequisites and focus restoration from dialogs remain available. Pointer capability changes are observed without a page reload.

## Typography from the user game screenshots

The 4K `IMG_6625.JPG` screenshot (Endless Effort), the previously supplied full-screen Cycle of Ruin and Scarlet Shield references, and the earlier per-skill captures establish the type hierarchy: regular warm-white body text; semibold golden game terms; gray italic passive and slot notes; uppercase titles and phase labels. Perk titles are gold in all three trees. Ability titles use blue-gray in Swordmastery, purple in Witchcraft and red in Vampirism. Closed-rank body text is gray while its emphasized terms stay gold. Broad Swing and Dirty Trick distinguish the blue-gray ability title from the gold Endless Effort perk title.

[Game Font Library identifies Afacad](https://www.gamefontlibrary.com/games/the-blood-of-dawnwalker) as the game's main UI font. This is an independent identification, consistent with the supplied letterforms, rather than a developer-confirmed font specification. The planner bundles the Latin variable regular and italic faces from [Google Fonts](https://fonts.google.com/specimen/Afacad); [official metadata](https://raw.githubusercontent.com/google/fonts/main/ofl/afacad/METADATA.pb) gives the 400-700 weight range. The original font files remain unmodified and are distributed under the [SIL Open Font License 1.1](https://raw.githubusercontent.com/google/fonts/main/ofl/afacad/OFL.txt). The complete license is included in the standalone HTML and published separately as `Afacad-OFL.txt`.

The implementation uses 400 for descriptions, ranks and italic notes, and 600 for titles and gold terms. Body/rank text is 19 px at 1.45 line height; skill titles are 26 px (24 px on narrow screens), phases 18 px, tree tabs 18-22 px. Colors are visual approximations from the supplied captures, not extracted game configuration values: body `#e7e5df`, unavailable text `#9d9e98`, terms/perk titles `#efbc78`, Swordmastery ability titles `#b7c7d4`, Witchcraft `#bca3d5`, Vampirism `#e57879`.

Gold emphasis is applied to a bounded vocabulary of game terms without altering the catalogue text or numerical values. The passive/slot note is separately italicized without gold terms. All 90 catalogue records and all rank data remain unchanged. The card uses the full catalogue description; Mandrake Ward retains its existing unconfirmed-healing wording rather than exposing its source placeholder. The 213 existing media assets are unchanged. Font URLs are inlined during the offline build; opening the file requires no font service. References, file hashes and checks are retained in local `research/typography`.

## Inline resource icons

Skill descriptions and rank effects place the original hourglass after “time segment(s)” and the original golden charge glyph after “Activation Charge(s)”. In the casting Cost row, charge and health glyphs precede their values. The health glyph appears only for a nonzero casting Health cost. Combat seconds and ordinary healing text do not receive these icons. The charge and health artwork comes from the unmodified user-supplied Burning Blood screenshot, displayed through clipped SVG viewports and embedded for offline use; provenance and coordinates are retained in `research/inline-resource-icons`.


## Swordmastery and Vampirism emphasis and card layout

A second visual audit covers every supplied Swordmastery and Vampirism description and rank: **58 skills, 183 ranks, 241 text fields, 74 original screenshots**. `app/skill-emphasis.json` records the exact gold phrases separately for each description and rank. Ordinary words are not inferred from capitalization or another skill. This includes gold Dodging, Charge, Area, Restoration, Ultimate, Kill, Bosses, Explodes, Fight and Slows where shown, while Time in Blood Theft and Temporary in Hastened Corruption remain plain. Passive/slot notes and Mesmerise's boss restriction remain gray italic. Mandrake Ward has no supplied card and is not counted as verified. Witchcraft retains the preceding corrections. The catalogue, numerical values and progression rules are unchanged.

Four additional user screenshots establish the card grouping: inset preview; diamonds overlapping the preview edge; phase, title and cooldown; description and italic note; casting Cost; a separately scrolling rank list; fixed training-cost and unlock footer. The planner shows the current selected rank followed by future ranks, omitting older learned rows. Aggregate perk effects remain in Build summary. The training strip displays the known training-segment cost within a 16-segment full day, not a predicted current day/night clock. Compel Soul's live cumulative usage total is not copied from the player's save.

Original glyphs are displayed through clipped SVG viewports from four unmodified, embedded screenshots:

| Glyph | Source card | Image dimensions | Viewport x, y, width, height |
| --- | --- | --- | --- |
| Empty Corruption mouth, also used behind a dynamic red threshold | Hastened Corruption | 680 × 582 | 155, 112, 31, 40 |
| Blood-unlock skull | Shadowstorm | 683 × 701 | 22, 267, 36, 54 |
| Yellow, orange and red tough-enemy skulls | Death from Above I | 675 × 721 | 70, 343, 89, 35 |
| Critical Direction chevron | Perfect Riposte | 674 × 576 | 336, 118, 28, 21 |

The empty mouth follows Corruption in the Hastened Corruption text, including before Level. Death from Above keeps all three colored skulls after Tough enemies at every rank; no numerical enemy-level differences are inferred. Perfect Riposte places the red chevron after Critical Direction. Numeric gates, blood unlocks and learned diamonds are distinct. Screenshot filenames, all gold annotations, byte hashes and validation results are retained in local `research/card-layout-and-emphasis`.


## Card footer simplification

At the user’s request, the separate Skill Points / Training time block and its 16-segment strip were removed from skill cards. Training costs remain in the individual upcoming rank rows. Unlock requirements, book links, acquisition guides and the existing rank/equip controls remain available. Catalogue values and calculations are unchanged.


## Retained effects in the learned card row

The learned row now combines the retained effects of all selected perk ranks, using the same effect identities and snapshots as Build summary. When an effect is upgraded, its earlier value is replaced; a different effect remains active. Source rows are displayed in rank order, keeping their original text, source-specific gold emphasis and inline glyphs. Future upgrade rows retain their individual original text and costs. Ability rank descriptions already contain their current effect values and retain that complete text.

For example, Lasting Malediction IV retains III's +40% Duration and adds IV's 20% extension after a Witchcraft Ability. Sustained Focus IV retains II's full Activation Charge at combat start and upgrades capacity to 4 Activation Charges. The correction restores retained text in 37 rank states across 23 perks; the catalogue, numbers, effect calculations, costs and card layout are unchanged. The removed training-cost footer stays removed. Reproductions of both previously incomplete rendered rows, corrected output and regression checks are retained in local `research/cumulative-card-effects`.


## 9 September 2026 — Mobile browser layout

The mobile change adjusts interaction and presentation only. Touching a skill opens a bottom sheet; rank changes use explicit buttons and the existing prerequisite/dependent confirmation model. The game coordinates, prerequisite graph, catalogue, cumulative effects, emphasis and source media are unchanged. Touch navigation adds Perks / Abilities / Ultimates jumps, a 100% initial board scale with an 85% minimum, center-preserving zoom buttons and native scrolling. The compact header, horizontally scrolling equipped slots, safe-area spacing and scrollable card body keep controls reachable on narrow screens. Unlock information scrolls with the card body on touch devices; rank and equip actions remain fixed below it. Mouse hover and left/right click controls remain available.

Validation records are in `research/mobile-browser/`. They distinguish model/navigation tests and actual React server-render checks from native browser interaction and visual testing, which were not run for this change.


## Quest journal: 9 September 2026

The journal includes all **207 entries** from [MetaBot’s quest catalog](https://metabot.gg/en/dawnwalker/quests): 29 main quests, 31 side quests and 147 activities. The [MetaBot planner](https://metabot.gg/en/dawnwalker/planner) exposes 351 day/night action variants. They are grouped by `questSlug`, not counted as separate mandatory quests. Every published record links directly to its MetaBot page.

All 207 individual quest pages were saved and hashed. The extraction keeps listed regions, phase variants, optional/unknown time costs, 338 listed reward entries, item categories and rarity, and separate completion/failure reward outcomes. The source’s “Items involved” cards enrich item metadata only; an involved item is not automatically a reward. Five Catalyst items and both Long sword/Great sword subtypes use their actual source category in the filters. Twenty-one PowerPyx-backed reward entries supplement omitted XP, skill points, skill unlocks, optional legendary loot, the merchant and the time refund. Seven conditional skill/equipment rewards are tied to explicit choices. The source’s outcome numbers are not inferred to mean a specific user choice.

**Relations and limitations.** MetaBot’s 351 planner variants all have empty `prerequisites` and `windows` arrays. They do not establish that all quests are freely available. Region-based “related quests” and the source’s unordered objective cards are never converted into dependencies. MetaBot’s generic failure text sometimes attributes failure to the coronation deadline even when a specific gameplay guide reports no such deadline; that generic statement is not used as a universal rule.

The local collection also contains 83 current quest walkthroughs from the [PowerPyx quest index](https://www.powerpyx.com/the-blood-of-dawnwalker-walkthrough-all-quests/). The curated overlay supplies 75 documented links, 15 decisions, eight explicitly triggered timers and the prologue/finale cutoffs. Each individual link, note, decision, timer and supplemental reward retains its own guide URL. Important distinctions include:

- [The Firebrand](https://www.powerpyx.com/blood-of-dawnwalker-the-firebrand-walkthrough/): Mert’s timer begins with Go to Stoneward Post and lasts 64 segments. His death closes the optional rescue but permits the corpse-and-ring route to the main chain.
- [Shadows in the Woods](https://www.powerpyx.com/blood-of-dawnwalker-shadows-in-the-woods-walkthrough/): the 32-segment deadline starts on finding Sara, not on receiving the overall quest.
- [Distant Shadows](https://www.powerpyx.com/blood-of-dawnwalker-distant-shadows-walkthrough/) branches after What Moves the Dead. Walking Crake back is the documented reliable trigger; the later alternative remains uncertain. Agreeing to talk to Marat opens [A Closer Look](https://www.powerpyx.com/blood-of-dawnwalker-a-closer-look-walkthrough/), with a 16-segment deadline.
- [Old Friends, New Friends](https://www.powerpyx.com/blood-of-dawnwalker-old-friends-new-friends-walkthrough/) expires 32 segments after Rise at Dawn is added to the journal. [Rise at Dawn](https://www.powerpyx.com/blood-of-dawnwalker-rise-at-dawn-walkthrough/) entering the journal is separate from agreeing to march, which is the point of no return.
- [A Mother’s Plea](https://www.powerpyx.com/blood-of-dawnwalker-a-mothers-plea-walkthrough/) needs peaceful village entry. Osha’s [The Heart Wants What It Wants](https://www.powerpyx.com/blood-of-dawnwalker-the-heart-wants-what-it-wants-walkthrough/) can start independently and is required only to finish the Elder’s request.
- [Letters to Lunka](https://www.powerpyx.com/blood-of-dawnwalker-letters-to-lunka-walkthrough/): the four additional sanzhani requests branch from Good Home, not from one another. The special refund requires all five requests and does not reverse a missed family deadline.
- [A Bulwark Against Darkness](https://www.powerpyx.com/blood-of-dawnwalker-a-bulwark-against-darkness-walkthrough/): the two saint-relic routes are alternatives; giving away St. Tyna’s relic does not permanently block the armour. Silk is purchased from a merchant unlocked by Pearly and Precious, rather than awarded free. Quicksilver is available after escaping Home Sweet Home.
- [The Bittersweet Toast](https://www.powerpyx.com/blood-of-dawnwalker-the-bittersweet-toast-walkthrough/): the verified poison window is 48 segments despite longer spoken dialogue. Expiration loses the poison advantage; it does not fail The Gilded Gauntlet.
- [Stronger Than Achilles](https://www.powerpyx.com/blood-of-dawnwalker-stronger-than-achilles-walkthrough/): Coen using the Font grants Font of Life, destroying it grants Ancient Greaves, and Anca using it gives neither of those rewards. [The Night of Horrors](https://www.powerpyx.com/blood-of-dawnwalker-the-night-of-horrors-walkthrough/) treats eating the mandrake and drinking Lacra’s blood separately.
- [General progression](https://www.powerpyx.com/the-blood-of-dawnwalker-100-completion-guide/) and [endings](https://www.powerpyx.com/the-blood-of-dawnwalker-all-endings-guide/): the family deadline does not terminate all side content. Final operations and the dream ending need a prior save for further open-world completion.

**Uncertainty is retained.** Ten quests have unknown MetaBot time values, nine have no recorded start location, and some entries are activity collections or have no listed reward. The source disagrees internally about Bakir’s armour after draining him; the reward note exposes that uncertainty and does not exclude a branch automatically. Runic Enchantment was not added as a reward because the fetched passages did not explicitly establish which quest awards it. No total quest-XP promise, mandatory-route time sum, automatic timer trigger, automatic cascading completion/failure or skill-rank change is computed from these incomplete tables.

The implementation, source snapshots, collection manifests, extraction/enrichment scripts, dependency tests and validation reports are retained locally under `research/quests`. They are not included in the public artifact. Source links and all structured quest data are embedded in the standalone site. Validation covers the data and rendered content, including all 207 detail bodies and their rewards. Actual browser interactions, dialog focus, visual layout and a physical phone remain unverified.
# Shared timeline — 9 September 2026

The Timeline reuses the unchanged 207-entry quest catalog and its phase costs, the unchanged 90-skill/274-rank catalog, and the existing sourced quest connections, choices and timers. Five ranks start learned; 269 further ranks can be scheduled. No universal training-cost formula, automatic XP-to-SP conversion, or guaranteed quest-loot accumulation is introduced.

- [MetaBot 30-Day Planner](https://metabot.gg/en/dawnwalker/planner): 30 days, daylight/night phases with eight segments each, and quest/activity variants. Public page read again on 9 September. Day/night variants are one quest, not independent mandatory completions. The quest values are aggregate estimates; a user can enter remaining work or a route-specific estimate. Missing costs remain uncertain. The reference page's empty prerequisite/window arrays are not used as proof of no restrictions.
- [Bandai Namco — Skills & Power](https://en.bandainamcoent.eu/dawnwalker/news/community-bulletin-board-11-skills-power): skill upgrades consume time and skill points; manual and Corruption requirements are distinct from spending those resources. The source describes activation periods but does not conclusively establish all training-phase restrictions. Timeline training defaults to an explicit “Any time” planning preference and can be set to day/night; it does not silently infer a learning restriction from a skill's activation period.
- [PowerPyx — How to Advance Time](https://www.powerpyx.com/blood-of-dawnwalker-how-to-advance-time/): shrine waiting, time spent by selected actions, and the family deadline. The existing [completion guide](https://www.powerpyx.com/the-blood-of-dawnwalker-100-completion-guide/) remains the source for side quests continuing after the family deadline.
- [PowerPyx — Letters to Lunka](https://www.powerpyx.com/blood-of-dawnwalker-letters-to-lunka-walkthrough/): a single 16-segment reward after all five sanzhani requests. An explicit claim extends the family budget; it does not rewind elapsed timeline time or objective timers and cannot rescue an already missed deadline.

Scheduling is a deterministic planning estimate, not a reconstruction of every in-game quest step. Whole-quest work can occupy several matching phases; a rank is treated as one training action. Waiting for a selected phase or earliest start consumes the calendar. Quest-start, timer and choice milestones are user-entered markers with no extra work cost. Timers are not inferred from quest completion. The three documented quest-failing timers (Sara, Marat, Vladimir) block projected completion at their deadlines; Mert and poison warnings retain the alternate-route / lost-advantage distinction. Duplicate timers cannot restart a deadline and conflicting choice markers cannot replace an earlier save branch silently.

Timeline state has its own local export format. Journal progress can be used as a read-only baseline or ignored for a fresh plan. A skill build can be copied as future training or explicitly recorded as already learned. Neither operation modifies the existing build or journal. Previously learned ranks and duplicate completions are not charged twice.

Validation: 110 model/regression tests, TypeScript, lint, production packaging, and 12 server-rendered scenarios covering all 207 quest rows, 90 skills/274 rank choices, 269 training actions, 60 calendar phases and 480 segments. Portal shells are substituted only for server-rendered dialog content checks; native browser, touch, focus and real-phone interactions have not been exercised for this addition. Local research and validation reports are under `research/timeline/`.


## Quest and timeline presentation — 9 September 2026

All 207 quest entries now have brief English summaries paraphrased from their saved [MetaBot quest pages](https://metabot.gg/en/dawnwalker/quests). Come Hither, Into the Den and Pearly and Precious additionally use their listed objective text. Five placeholder entries (Murohn’s Lair, Sinkhole and the three Tower entries) explicitly state that objective details and rewards are unlisted. No invented objectives are supplied for them.

Reward artwork is joined to actual rewards by exact item URL, never by the mere presence of an “Items involved” card. The 77 linked reward items use 66 distinct original images observed in the source cards. Five additional PowerPyx-sourced loot rewards use their matching MetaBot item artwork: [Imbued Sword of St. Mihai](https://metabot.gg/en/dawnwalker/items/imbued-sword-of-st-mihai), [The Vrakhir](https://metabot.gg/en/dawnwalker/items/the-vrakhir), [Ancient Greaves](https://metabot.gg/en/dawnwalker/items/ancient-greaves), [Coat of Darkened Scales](https://metabot.gg/en/dawnwalker/items/coat-of-darkened-scales), and [Fear of the Wilds](https://metabot.gg/en/dawnwalker/items/fear-of-the-wilds). One of these shares an existing texture; 70 item images are embedded in total. The eight named skill rewards reuse their existing skill-tree artwork. The timeline retains the skill tree’s question-mark fallback for Soul Reaping, whose original icon remains unavailable. Bakir’s Armour has no independently matched image and uses an armour-category symbol. XP, coins, merchants and other non-item rewards use distinct category symbols; skill points and time reuse the existing original game glyphs.

Names, quantities, item types, rarity and recorded choice conditions accompany the images. The journal preview brings matching reward filters to the front; the timeline shows all reward items. These remain possible finds and outcome rewards, with no new assumption that all are cumulative or guaranteed. The source catalog, reward data, quest connections, training costs and save formats are unchanged. Timeline reward previews use the already computed projected choices. Shared game glyph rendering is moved intact from the skill planner so both sections display the same artwork and source coordinates.

Source matches, original image URLs and hashes, summary provenance, pre-edit files and verification reports are retained locally under `research/quest-visuals/`. The portable artifact contains all 288 media assets and both existing fonts. Validation covers all 207 quest detail bodies, all 359 reward entries, filter ordering, mutually exclusive Font rewards, all item-image paths, the 12 timeline render scenarios, 110 regression tests, TypeScript, lint and production packaging. Native browser layout, dialog focus and physical-phone interactions have not been exercised for this presentation update.


## Fixed calendar placement — 9 September 2026

The timeline is now a compact board of 30 day groups, each with eight daylight and eight night segments. This is a presentation and planning change over the same quest, reward, skill, phase and timer data. Action dates are fixed; placement or editing that intersects another reserved segment is rejected. No automatic rescheduling is performed. Phase gaps in a quest stay available for independent work, while explicit waiting reserves its segments. A training rank is one consecutive action.

The existing version-1 export adds an optional calendar layout and per-action start. Old queues migrate at their previously calculated starts and costs. Unplaced actions have no effect on time or projected progress. Zero-time milestones do not consume a segment; unknown time requires an estimate before a new placement. Records beyond the visible 30 days remain editable. Existing imported conflicts remain visible and blocked without moving other records.

Projection applies completion in chronological order, so a long quest does not unlock its successor during a free phase. Finish prerequisites, choices and objective deadlines are rechecked at completion, including triggers recorded while a quest was in progress. Already learned ranks or completed quests retained as reservations are flagged for removal. They cannot grant progress again; fixed reservations are not silently erased.

The compact library previews named rewards and their artwork; selecting or opening the action exposes every reward and recorded condition. All prior sources and media remain unchanged. Model, server-rendered content, type, lint and offline artifact checks are recorded in `research/timeline-board/`. Browser layout, native drag/drop, dialog focus and physical-device interaction have not been exercised for this update.


## Prologue and no-time completion points — 9 September 2026

The calendar now shows one separate prologue day before the 30 main days, using the requested eight daylight/eight night planning layout. Existing main-day dates and the 480-segment family deadline are unchanged. Prologue positions are saved before Day 1 and do not consume or extend that family budget. This display does not revise any catalogued quest time, reward, phase or route.

No-time quests are explicit completion points. The catalog already records All Good Things as zero time in both phases. [Withering Away](https://www.powerpyx.com/blood-of-dawnwalker-withering-away-walkthrough/) and [Live Bait](https://www.powerpyx.com/blood-of-dawnwalker-live-bait-walkthrough/) require its completion; the latter must be finished before [Sacred Covenant](https://www.powerpyx.com/blood-of-dawnwalker-sacred-covenant-walkthrough/). These sources were checked again on 9 September. Their existing prerequisite and cutoff rules were retained.

A completion point is applied before timed work beginning at the same position, regardless of which was added to the plan first. It may share a position inside reserved time and has a visible point preview, phase position and named entry. Multiple zero-time points at one position retain their insertion order. Unknown duration is displayed separately as unconfirmed, not as known zero time. Font sizes and available widths have been increased across the timeline without changing the skill tree or quest journal.

Compatibility, phase arithmetic, the prologue boundary, family budget, All Good Things ordering, same-point Sacred Covenant cutoffs, no-time moves and import checks are recorded in `research/timeline-prologue/`. Native browser drag/drop, focus and physical-device layout remain outside the performed automated checks.


## Direct timeline dragging — 9 September 2026

Dragging placed actions now uses temporary drag state separately from click placement, so it does not insert quest details, resize the calendar or disable other action blocks. Dragging a long block retains the grabbed segment, including continuations across skipped phases. Zero-time points can be moved directly; cancellation and invalid drops leave dates unchanged. Ordinary clicks still open the inspector. This changes interaction only; the calendar model and all catalogues, rules, sources and media are unchanged.

The previous component reproduces the placement-layout regression in a hook-based handler harness. The updated component passes direct-move, cancellation, overlap, point, continuation, library and unplaced-action checks, alongside existing model and server-rendered checks. These checks exercise component callbacks; native browser drag gestures and physical-device behavior remain unverified. Evidence is retained in `research/timeline-drag/`.


## Calendar quest hover preview — 9 September 2026

Placed quest blocks and zero-time quest points now show a hover preview using the existing quest descriptions, metadata and reward presentation. It includes the chosen calendar position and planned cost, with reward artwork and recorded outcome conditions. Continuation blocks show the same quest information. The existing HoverCard primitive handles opening, focus, dismissal and popup positioning without adding an element around the calendar button. The preview closes on pointer press and is suppressed during dragging, click placement and editing. Ordinary clicks still open the editor.

No catalogue, rule, image, font or third-party component was changed. Server-rendered checks cover preview content and suppression, with the popup portal shell replaced for inspection. Existing drag-handler checks still pass. Native hover timing, popup placement and physical-device interaction were not exercised. Evidence is retained in `research/timeline-hover/`.

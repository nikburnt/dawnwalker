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

Some Codex ability descriptions are empty. Their original text is supplemented from GamesDB with a warning in the skill card. These values should be checked against the game; they are not independently verified damage formulas.

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

- Most individual vampiric Corruption thresholds. Known thresholds are included; others can be overridden with actual values or marked as unlocked.
- Initial ranks available without a manual for some skills. Published panels were used for the first two ranks of Endless Effort, Omniblock, Stinging Blade, Vigour, Witchcraft Mastery and Second Skin I; four ranks of Sustained Focus; and three ranks of Bewitching Influence. Other manual-based perks may have unknown initial availability. These are published reference values that can be corrected for your save.
- Zero training time for the first two ranks of the four basic Swordmastery perks was taken from published panels. Other missing time costs remain unknown.
- Final Witchcraft Mastery rank: the current Codex table lists 1 segment, while an official prerelease screenshot shows 2. The current catalogue value is used with an explicit warning.
- Font of Life and Mandrake Ward: catalogues disagree on numerical effects, so the summary describes them qualitatively. Their special unlock must be explicitly marked in My game mode.
- Some numerical Ultimate parameters, bonuses per place of power or soul, bonus stacking formulas and durations of certain temporary effects.
- Individual vendor prices, actual Health and charge costs of casting each Active Ability, exact base Cooldowns and equipment statistics.

Personal overrides are stored separately from the catalogue and exported with the build.

## Visual references

The layout follows game panels: three trees at the top, the perk graph, separate ability columns, diamond rank markers and a selected-skill panel on the right.

- [Xbox Wire — Hands-on preview](https://news.xbox.com/en-us/2026/07/07/the-blood-of-dawnwalker-hands-on-preview/): official Witchcraft panel screenshot.
- [Shacknews — Ability slots](https://www.shacknews.com/article/150542/how-to-unlock-more-ability-slots-the-blood-of-dawnwalker): Vampirism panel.
- [Hack the Minotaur — Skill trees guide](https://hacktheminotaur.com/blood-of-dawnwalker/blood-of-dawnwalker-skill-trees-complete-guide/): Swordmastery panel.

This is a fan-made tool. Game icons and illustrations belong to their respective rights holders; no open licence is claimed. The planner is not affiliated with or endorsed by Rebel Wolves or Bandai Namco.

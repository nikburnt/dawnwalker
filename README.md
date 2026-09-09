# Dawnwalker Planner

**[Open the calculator](https://nikburnt.github.io/dawnwalker/)**

A fan-made skill planner for The Blood of Dawnwalker, with 90 skills, original game icons, rank dependencies, ability slots, and skill point, manual and training-time costs. Daytime, nighttime and conditional effects are kept separate.

The interface, skill descriptions, tooltips and build summaries are in English.

Search all skills by name with **Find a skill** (**Command-K / Ctrl-K**). Trees follow the game menu, with perk branches on the left, Ultimates below and two ability columns on the right. Section headings are centered above their content. Hover or focus an icon for its full interactive card. **Left click** adds a rank; **right click** removes one. Prerequisite learning and dependent removal show all affected ranks and the cost change before confirmation. Cancel keeps the build unchanged. The tree uses the full workspace width with no permanent sidebar. **Fit tree**, zoom, drag and swipe keep the diagram usable across screen sizes without stretching its connections. Skill cards follow the game panel: an inset preview with rank diamonds on its lower edge, phase and name, description and casting Cost, then a separately scrolling list of the current and upcoming ranks. The footer keeps the unlock requirement visible; training costs appear beside each upcoming rank. Mouse hover cards retain Equip / Unequip; rank buttons are also available on touch devices and in separately opened dialogs. Short cards shrink to their content, and previews hide on short screens to leave room for ranks.

## On a phone or tablet

Tap a skill to open its card from the bottom. Tapping a node does not spend points: use **Add rank** or **−** in the card. The rank counter and **Equip / Unequip** stay at the bottom while you scroll the preview, description, current effects, upcoming ranks and unlock guide. **Done** returns to the tree. Prerequisite and dependent-rank confirmations still apply.

Swipe across the game tree to explore it. **Perks**, **Abilities** and **Ultimates** jump to the corresponding area. The tree starts at 100%; its touch zoom never shrinks a medallion below 54 px. The overlaid **− / +** buttons zoom around the visible center, and the reset-view button restores the starting view. The browser's normal pinch zoom remains available. Search can find skills in all three trees.

The header, resources and actions use a compact layout with touch targets of at least 44 px. Equipped slots scroll horizontally when they do not fit. Cards account for the phone's safe areas; short landscape screens allow page scrolling. Resource and import fields use readable 16 px text, and numeric budgets request a number keyboard. Existing saves, build links, costs and desktop mouse controls use the same underlying planner.

All 27 abilities include a silent gameplay preview from Fextralife. Hover an ability to watch it, then use the video controls to pause, seek or enter full screen. With **Reduce Motion** enabled, press Play to start. Clips are included for offline use and link to their source pages.

User-supplied game cards cover 20 Witchcraft perks, all 10 Witchcraft abilities all 29 Swordmastery skills (96 ranks), and 29 Vampirism skills (87 ranks). The update confirms starting/manual ranks, keeps seven Anytime perks active at night, and supplies observed numerical effects, cooldowns and casting costs. The additional first-rank screenshot confirms Astral Communion I at +0.4% Damage per place of power. All book requirements are now established. Charge needs a book at every rank, including I; the player had already read its first book before the screenshot. Dirty Trick now shows the observed 110 / 137 / 165 / 192 Damage, and four Swordmastery cards include cooldowns and charge costs. Vampirism cards establish the Corruption thresholds, special skull unlocks, and Lethal Crescendo at +20% Claw Damage per kill or Boss Health Segment depleted. Font of Life and Mandrake Ward are unchanged.

All SP and training-time costs are known. The five skull unlocks require Vrakhir blood and cost 1 SP with no time at I. Their cards now name the relevant blood and link to acquisition information. Mesmerise requires Lacra's blood; eating the mandrake grants Mandrake Ward. Mandrake Ward is the sole unconfirmed Corruption requirement. Fourteen ability cards include their displayed casting values.

The wiki cross-check adds 22 acquisition routes to the catalogue, four numerical Ultimate effects, Nourishing Blood Corruption gates, and corrections for manual unlocks and direct blood rewards. Acquisition guides are linked from **Manuals** where available.

Dirty Trick I, Compel Soul I, Astral Communion I, Burning Blood I and Voracious Bite I start learned for free. They remain after Clear and are added to older saved builds and shared links. Add further ranks, then equip learned abilities in the available slots. Open the build summary for costs and effects. Planning mode allows future acquisition requirements; **My resources** checks your budgets and Corruption. Manuals are counted from catalogue starting ranks. Quest tracking has its own section and does not change skill ranks or resource budgets.

Builds stay in your browser. **Export** provides a shareable link and a 78-character code; **Import** accepts either. They preserve ranks, equipped slot order and resources. Shared links load automatically, and **Undo** restores the previous build. Damaged codes do not change it. Costs use the catalogue; unconfirmed values are marked with a question mark. Older builds still load, but legacy personal cost overrides and manual unlock flags are ignored. Sources and media attribution are retained in the project documentation and metadata.

This repository contains the ready-to-use static site. All code, fonts, images and videos are embedded in `index.html`; you can also download it and use it offline without a server. GitHub Pages publishes the root of `main`. Replace `index.html` with a new standalone build to update the website.

The header pairs the official game wordmark with an image-generated Character Planner wordmark matching its gold lettering and texture. Build resources sit beside the learned count and zoom controls in compact icon–value–label rows. On narrow screens, labels hide and the icons and values remain. The sliders button opens resources and availability. Open **Manuals** for the selected build’s book list, required copies and links to locations, vendors and acquisition guides.

The current rank has a filled diamond and combines all retained effects. A stronger value replaces the older value of the same effect; different bonuses remain. Older learned rank rows are omitted, and future rows retain their original upgrade text. Future ranks show a book, hollow diamond, prerequisite lock, numbered Corruption mouth or separate blood-unlock skull, with SP and nonzero training-time costs at the end of the text. Reaching the configured Corruption threshold changes its gate to an availability diamond. Direct book links and named blood-acquisition guides remain in the footer. Perks and active abilities use circular bodies with four cardinal spikes. Only the eight passive abilities in the right columns use plain circular frames. Hover adds a separate golden circular halo, with the dark interior and original artwork retained.

The three skill-tree tabs use exact 84 × 84 PNG crops of the neutral Swordmastery, Witchcraft and Vampirism emblems from the user-supplied 4K screenshots. With a mouse, skill nodes highlight only under the pointer. Hover shows their cards; left/right clicks change ranks without leaving a node selected. Keyboard focus remains visible.

Resource icons use the game glyphs from an official screenshot, bundled for offline use. Skill-card training costs use the same icons in place of unit abbreviations.

Skill cards use the Afacad typeface with regular body text, semibold gold game terms and gray italic passive/slot notes. All perk titles are gold; ability titles are blue-gray for Swordmastery, purple for Witchcraft and red for Vampirism. Names, phases and tree tabs use capitals. Descriptions and rank text are 19 px with 1.45 line spacing; titles are 26 px, reduced to 24 px on narrow screens. Unavailable rank text dims while game terms retain their gold emphasis. Full catalogue descriptions appear above the rank rows. A second visual audit attributes gold emphasis separately for all 58 supplied Swordmastery and Vampirism cards and 183 ranks, using 74 screenshots. Aggregate learned perk effects remain in Build summary. Mandrake Ward remains unverified. Both font styles and the SIL Open Font License are embedded in the standalone file.

Afacad is distributed under the [SIL Open Font License](Afacad-OFL.txt).

[Sources, methodology and data limitations](SOURCES.md). Data snapshot: 8 September 2026. Research snapshots referenced in that document are retained locally by the author and are not included in this publication.

Game icons, illustrations and animation footage belong to their respective rights holders. This is not an official product of Rebel Wolves or Bandai Namco.

Game resource icons also appear inside skill descriptions and rank effects: the hourglass after time segments and the golden glyph after Activation Charges. Casting costs show a charge icon and, when Health is spent, the game’s health icon before the values. The original artwork is embedded for offline use.

Vampirism cards use the original Corruption mouth with a red threshold, a distinct blood-unlock skull and the yellow, orange and red skulls after Tough enemies in Death from Above. Corruption mentions and Perfect Riposte’s Critical Direction also retain their screenshot glyphs. These use unmodified embedded source images.


## Quest journal

Switch to **Quests** in the top navigation. The skill build and its undo history stay in place when you switch sections.

- Browse all **207 MetaBot entries** (29 main quests, 31 side quests and 147 activities) in **Chains** or **List** view. **75 documented connections** distinguish required steps, optional branches, alternate routes and materials needed to finish a quest. The nine named groups organize related questlines; arrows are based on documented connections, not region recommendations or walkthrough list order.
- Search by quest, reward or place. Filter by reward category and item rarity; **More filters** adds quest type, region, progress and choices/timing checks. A reward type and rarity must belong to the same item. Matching quests keep their known ancestors visible as **Chain context**. **Respect my reward choices** hides reward alternatives excluded by recorded decisions.
- Mark quests **Not started**, **In progress**, **Completed** or **Failed / missed**. Record the supported decisions inside a quest. **15 choice checks** cover village entry, Mert, Crake, the Font, Lacra, the relic, Court blood rewards, the dream and final routes. Consequences are previewed before saving a conflicting change; other quest statuses are never silently changed. **Undo** restores the last tracker change.
- Open **Your game clock** to enter elapsed days and segments after the prologue. **Eight timers** use explicitly recorded objective triggers. Advancing the tracker clock shows waiting periods and deadlines; checking off a quest does not spend time or start a timer. The 30-day family deadline is not treated as failure of every side quest.
- Rewards include possible quest items, optional loot and outcome rewards. The catalog retains **338 MetaBot reward entries** and adds **21 source-backed entries** from PowerPyx, including skill unlocks and the sanzhani time refund. Conditional rewards stay separate: for example, Font of Life and Ancient Greaves cannot both be obtained from the same Font choice. Raw MetaBot outcome numbers are shown separately because their mapping to the recorded decisions has not been verified.
- Quest progress autosaves under its own browser storage key. Use **Export progress / Import** to move it between devices, or **Clear tracker** to start again; both replacement and clearing can be undone. Skill share links and skill resource budgets remain separate.

All quest data is embedded in **Dawnwalker.html** and works offline. Links open the full guides when online. Unconfirmed locations, time and unlisted rewards remain explicit. The cross-quest checks cover documented cases, not every possible game state. No save-game import or automatic synchronization with the game is provided.


## Timeline

Switch to **Timeline** to schedule quests, activities and individual skill ranks together. Start with **Add action**, or **Add skills from build** to copy the selected ranks in their learning order. The library contains the same 207 quests and activities, plus all 269 ranks above the five free starting ranks. Quest search includes rewards and locations; type and reward filters help choose what to schedule.

- Rearrange the **Queue** with the up/down buttons or the position field. **30-day calendar** shows all 480 segments, with separate colors for quests, activities, training and waiting. Click a day heading to inspect its actions, or a phase to add an action no earlier than that phase. Every edit recalculates later dates.
- Open **Starting point** to set the day, phase and spent segments, or copy the journal clock. **Use current build as already learned** records an explicit baseline; those ranks cost no training time or points, including if already in the queue. The default baseline is the five starting ranks. **Add skills from build** instead treats the selected build as a future target. Neither action changes the skill tree.
- Edit an action's phase, earliest start or time estimate. A blank estimate uses the recorded cost. Whole-quest values are estimates over multiple objectives, so enter only the remaining cost for a partially completed quest. A quest restricted to one phase can occupy successive matching phases, with waiting counted between them. A single training rank waits for enough room in the chosen phase. The training phase is explicitly user-selected; activation periods are not assumed to establish training restrictions.
- **Milestones & other** adds named activities, explicit waiting, quest starts, the eight documented timer triggers and the fifteen choice groups. Milestones add no work time themselves; schedule the associated work separately. A start marker allows optional branches between a quest's start and finish. Timers begin only at recorded triggers, and a second marker cannot reset an existing timer.
- The projected route reuses the journal's dependency and choice checks. Missing prerequisites, failed quests, incompatible phases, duplicate quest versions, duplicate ranks and conflicting save branches are flagged. An expired Sara rescue, Marat conversation or Vladimir quest does not unlock later dependencies. The Mert and poison timers retain their documented outcome/advantage distinction. Font of Life training checks the chosen Font outcome; blood abilities retain alternative-phial guidance.
- Claim the **sanzhani time refund** as an explicit milestone after completing Letters to Lunka and its requests. It adds 16 segments to the family budget once, without rewinding objective timers. A late refund cannot undo the family deadline. Passing the family limit is not treated as failure of all side quests.
- Autosave, **Undo**, and separate **Export plan / Import** preserve the timeline on this device or move it to another. Disable **Use progress, choices and timers from Quests** for a fresh route without clearing the journal. Planning never writes completion or learned ranks back to the other sections.

Unknown time is not silently treated as confirmed zero: subsequent dates and remaining budget are marked as estimates. The calendar shows up to 60 days; later actions remain in the queue. Manual collection, blood acquisition, Corruption and skill-point gains are not automatically simulated. The sources and documented limitations are available inside the planner.


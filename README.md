# Dawnwalker Skill Planner

**[Open the calculator](https://nikburnt.github.io/dawnwalker/)**

A fan-made skill planner for The Blood of Dawnwalker, with 90 skills, original game icons, rank dependencies, ability slots, and skill point, manual and training-time costs. Daytime, nighttime and conditional effects are kept separate.

The interface, skill descriptions, tooltips and build summaries are in English.

Search all skills by name with **Find a skill** (**Command-K / Ctrl-K**). Trees follow the game menu, with perk branches on the left, Ultimates below and two ability columns on the right. Section headings are centered above their content. Hover or focus an icon for its full interactive card. **Left click** adds a rank; **right click** removes one. Prerequisite learning and dependent removal show all affected ranks and the cost change before confirmation. Cancel keeps the build unchanged. The tree uses the full workspace width with no permanent sidebar. **Fit tree**, zoom, drag and swipe keep the diagram usable across screen sizes without stretching its connections. Skill cards follow the game panel: an inset preview with rank diamonds on its lower edge, phase and name, description and casting Cost, then a separately scrolling list of the current and upcoming ranks. The footer keeps the unlock requirement visible; training costs appear beside each upcoming rank. Mouse hover cards retain Equip / Unequip; rank buttons are also available on touch devices and in separately opened dialogs. Short cards shrink to their content, and previews hide on short screens to leave room for ranks.

All 27 abilities include a silent gameplay preview from Fextralife. Hover an ability to watch it, then use the video controls to pause, seek or enter full screen. With **Reduce Motion** enabled, press Play to start. Clips are included for offline use and link to their source pages.

User-supplied game cards cover 20 Witchcraft perks, all 10 Witchcraft abilities all 29 Swordmastery skills (96 ranks), and 29 Vampirism skills (87 ranks). The update confirms starting/manual ranks, keeps seven Anytime perks active at night, and supplies observed numerical effects, cooldowns and casting costs. The additional first-rank screenshot confirms Astral Communion I at +0.4% Damage per place of power. All book requirements are now established. Charge needs a book at every rank, including I; the player had already read its first book before the screenshot. Dirty Trick now shows the observed 110 / 137 / 165 / 192 Damage, and four Swordmastery cards include cooldowns and charge costs. Vampirism cards establish the Corruption thresholds, special skull unlocks, and Lethal Crescendo at +20% Claw Damage per kill or Boss Health Segment depleted. Font of Life and Mandrake Ward are unchanged.

All SP and training-time costs are known. The five skull unlocks require Vrakhir blood and cost 1 SP with no time at I. Their cards now name the relevant blood and link to acquisition information. Mesmerise requires Lacra's blood; eating the mandrake grants Mandrake Ward. Mandrake Ward is the sole unconfirmed Corruption requirement. Fourteen ability cards include their displayed casting values.

The wiki cross-check adds 22 acquisition routes to the catalogue, four numerical Ultimate effects, Nourishing Blood Corruption gates, and corrections for manual unlocks and direct blood rewards. Acquisition guides are linked from **Manuals** where available.

Dirty Trick I, Compel Soul I, Astral Communion I, Burning Blood I and Voracious Bite I start learned for free. They remain after Clear and are added to older saved builds and shared links. Add further ranks, then equip learned abilities in the available slots. Open the build summary for costs and effects. Planning mode allows future acquisition requirements; **My resources** checks your budgets and Corruption. Manuals are counted from catalogue starting ranks, and quests remain acquisition notes.

Builds stay in your browser. **Export** provides a shareable link and a 78-character code; **Import** accepts either. They preserve ranks, equipped slot order and resources. Shared links load automatically, and **Undo** restores the previous build. Damaged codes do not change it. Costs use the catalogue; unconfirmed values are marked with a question mark. Older builds still load, but legacy personal cost overrides and manual unlock flags are ignored. Sources and media attribution are retained in the project documentation and metadata.

This repository contains the ready-to-use static site. All code, fonts, images and videos are embedded in `index.html`; you can also download it and use it offline without a server. GitHub Pages publishes the root of `main`. Replace `index.html` with a new standalone build to update the website.

The header pairs the official game wordmark with an image-generated Character Planner wordmark matching its gold lettering and texture. Build resources sit beside the learned count and zoom controls in compact icon–value–label rows. On narrow screens, labels hide and the icons and values remain. The sliders button opens resources and availability. Open **Manuals** for the selected build’s book list, required copies and links to locations, vendors and acquisition guides.

The current rank has a filled diamond; older learned ranks are omitted. Future ranks show a book, hollow diamond, prerequisite lock, numbered Corruption mouth or separate blood-unlock skull, with SP and nonzero training-time costs at the end of the text. Reaching the configured Corruption threshold changes its gate to an availability diamond. Direct book links and named blood-acquisition guides remain in the footer. Perks and active abilities use circular bodies with four cardinal spikes. Only the eight passive abilities in the right columns use plain circular frames. Hover adds a separate golden circular halo, with the dark interior and original artwork retained.

The three skill-tree tabs use exact 84 × 84 PNG crops of the neutral Swordmastery, Witchcraft and Vampirism emblems from the user-supplied 4K screenshots. With a mouse, skill nodes highlight only under the pointer. Hover shows their cards; left/right clicks change ranks without leaving a node selected. Keyboard focus remains visible.

Resource icons use the game glyphs from an official screenshot, bundled for offline use. Skill-card training costs use the same icons in place of unit abbreviations.

Skill cards use the Afacad typeface with regular body text, semibold gold game terms and gray italic passive/slot notes. All perk titles are gold; ability titles are blue-gray for Swordmastery, purple for Witchcraft and red for Vampirism. Names, phases and tree tabs use capitals. Descriptions and rank text are 19 px with 1.45 line spacing; titles are 26 px, reduced to 24 px on narrow screens. Unavailable rank text dims while game terms retain their gold emphasis. Full catalogue descriptions appear above the rank rows. A second visual audit attributes gold emphasis separately for all 58 supplied Swordmastery and Vampirism cards and 183 ranks, using 74 screenshots. Aggregate learned perk effects remain in Build summary. Mandrake Ward remains unverified. Both font styles and the SIL Open Font License are embedded in the standalone file.

Afacad is distributed under the [SIL Open Font License](Afacad-OFL.txt).

[Sources, methodology and data limitations](SOURCES.md). Data snapshot: 8 September 2026. Research snapshots referenced in that document are retained locally by the author and are not included in this publication.

Game icons, illustrations and animation footage belong to their respective rights holders. This is not an official product of Rebel Wolves or Bandai Namco.

Game resource icons also appear inside skill descriptions and rank effects: the hourglass after time segments and the golden glyph after Activation Charges. Casting costs show a charge icon and, when Health is spent, the game’s health icon before the values. The original artwork is embedded for offline use.

Vampirism cards use the original Corruption mouth with a red threshold, a distinct blood-unlock skull and the yellow, orange and red skulls after Tough enemies in Death from Above. Corruption mentions and Perfect Riposte’s Critical Direction also retain their screenshot glyphs. These use unmodified embedded source images.

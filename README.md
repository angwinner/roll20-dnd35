# roll20-dnd35
An alternate version of the D&amp;D 3.5 character sheet for Roll20

<b>MOTIVATION</b>

My gaming group has experienced some frustrations while playing Dungeons & Dragons version 3.5 on Roll20, and this character sheet redesign is intended to address the most serious issues experienced by players. The first set of issues is centered around the display. My party is often frustrated by switching between tabs or getting stalled because they miss pop-ups spawned by macros. One example from combat is that the character's Armor Class and Hit Points are on the 'Stats' tab, but one must navigate to the 'Weapons' tab to use weapon attack macros. The 'Weapons' tab combines weapon setup and weapon use. In my redesign, all attack actions are on the 'Main' tab while the weapons setup is relegated to the 'More' tab. The same will be true of prepared spells.

The design also replaces pop-up input with either 'Temp' text box input or reusable line items that can be checked/unchecked as needed.

The second and more significant issue is that some of our players eschew the attack macros. Everyone likes and uses the Initiative macro, the Ability check macros, and the Saving Throws. Attack macros are a different story. Inconvenient placement on another tab might factor into their unpopularity, but I think the bigger issue is that people don't know, at a detailed level, what the macro is doing and where it's getting its data from. They don't know which bonuses are already accounted for and which ones they have to type into the attack macro popup. This is a shame because the macros add color text and expedite things like full attacks. (Expeditiousness is an issue in a party of eight players!) Even with the basic melee and ranged attack macros on the 'Stats' page we get a lot of "My attack is this minus 5", or "I don't know if that includes my strength penalty from poison". Manually summing bonuses and penalties like we do around the game table is well enough, but it takes time and some of our players are prone to mistakes. As long as we have Roll20 available, we may as well use it to double-check our arithmetic.

My redesign addresses this issue by introducing a roll-centric paradigm where each roll has a (big, candy-colored) die, plus adjustments, plus a temp adjustment. This way, the roll appears as the user expects it, i.e. d20 + 8 + 1. The list of adjustments is always expandable via a superimposed carat, and includes contributions from all sources. Each adjustment can be toggled on or off. User defined adjustments, like Bardic Music, will always be visible, while other adjustments, such as from status conditions, will only be visible on the list when the condition applies.

This roll-centric approach offers transparency to the users, easy editing without having to update macros, and flexibility to accomodate homebrew rules. Also, because each adjustment to the roll has an abbreviation, it allows the DM to mouse over the inline roll result and audit the adjustments applied.

Other features include some responsive web design for one- or two-column format, because a narrow window can be handy when sharing screen space with the map window, and a selection of colors for the dice/macro buttons.

This character sheet takes its large-scale organization, tab structure, and expand/contract carats from Diana P.'s Version 2.7.9 12/7/20

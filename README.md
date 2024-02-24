# tabletop-anytool
A suite of flexible and efficient tools for running tabletop RPGs

Licence: MIT Licence

Project aim: a lightweight webapp that should be a DM's or player's main tool for running or playing games.
It is a customisable toolbox of various useful widgets.
(It's really a learning project)

The main design goals are as follows:
- High degree of interface flexibility/customisation (as every DM and player has different needs)
- Heavy use of hotkeys + keyboard input, as people seldom have a large amount of table space to use a mouse and a trackpad is slow
- Efficiency of use. Once you have it set up, you should be able to set things up so that your most frequent actions take *no more* than 4 keypresses
- Scrolling (through long textboxes or through piles of tabs) is the enemy. Manual searching is the enemy. Everything must be instantly searchable.
- Compatibility with other information systems, and not tying a user to this one. A user should not need to use this project specifically to read their own notes.
- Provide premade widgets (made out of standard components) that are appropriate for particular system rulesets, such as an initiative tracker or monster statblock.
- To do as much for the user as possible while also never getting in the way or bogging them down.

Implementation plans:
- Hotkey defaults designed around a laptop keyboard, with one hand. Taking advantage of a full PC keyboard is fine but can only ever be a secondary priority.
- Smartphones are not within scope. I don't think it's possible to design any tool that will make it plausible to run a game from a phone - they're too small and clumsy and slow.
- Underlying data will be stored as plain text that is transparently accessible. Standardise on presenting information to the user similarly to ObsidianMD.
- Widgets exist on screens: the current plan is to have one home/main screen and eight more around it like numpad keys.
- Users should never scroll "around" a screen: information that can't fit on one screen should be moved to a different screen.
- Screens are associated with particular hotkeys e.g. numpad keys (though that's not laptop-friendly). Holding a key displays that screen. Double-pressing a key moves you to that screen.
- Screen transitions should correlate to obvious keyboard shortcuts to reinforce a simulated spatial relation, aiding in remembering where information is.
- Users populate these screens with groups of widgets that are useful for particular contexts: like dungeon exploration, improvisation, combat, faction relations, etc.
- searching all your notes or rolling dice should be available from anywhere.
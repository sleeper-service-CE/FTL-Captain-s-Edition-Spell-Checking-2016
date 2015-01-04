FTL-Captain-s-Edition-Spellchecking-2015
========================================
A community effort to spell check the FTL Captain's Edition mod for the roguelike game FTL by Subset Games.
(2015 Rebirth Edition)

Original Readme:

Welcome traveler. I guess you came here from the FTL forum and know what this is about. If not, than you might want to have a short rundown of what is going on here. Over the last months I have created a quite huge modification of the froguelike game FTL by Subset Games. You can find information on the mod here: http://www.ftlgame.com/forum/viewtopic.php?f=11&t=15663 The mod contains quite a bit of text for the player to read, but English is not my mother tongue and eliminating all the types has been requested quite often. So I uploaded the files containing most of the texts on github to allow multiple people to participate in checking the mod. I have no clue about real coding, FTL moding mostly works by editing simple xml files. So this whole "project" is really just about spell checking a lot of small text snippets contained in xml capsules.

House rules:

1. Changes you make in the files have the potential to make the mod unplayable very easily. Act responsible and observe this rules, else this effort to spell check CE will not work.
2. Only spell check things within text tags. Everything else might mess up the mod structure.
3. If you rephrase things, do not exeed the number of characters the text originally had, specially when the text was already pretty long. Too long texts can cause the game to crash on text load.
4. Don't add intent or any kinds of breaks in the text. FTL event texts need to be pure flowtext to work correctly.
5. Never write anything outside of text tags. Stray characters outside of tags cause problems and are hard to locate afterwards.
6. Please never make any direct changes in the choices that let the player us the combat augments. That will remove my ability to control these choices globally via find and replace. If you have suggestions how these choices could be improved, you can make a suggestion in the thread.
7. This repository is for spellchecking, not for sneaking changes you like to see into CE. The mod is free to use for anyone. If you have your own vision how of it should be than you can simply take a copy, make your modifications and post it. Here is not the place for this though

Sections that have not yet been checked by a third party include:
- Everything concerning the Auto Controlled Sector in events_Rebels.xml.append (event IDs typically start with AUTO...)
- Most events concerning the AI Controlled Sector in events_Zoltan.xml.append (event IDs typically start with AI...)
- Crew conversations in events.xml.append
- Any events that haven been added since the beginning of 2014

Thank you all for your help sleeper_service

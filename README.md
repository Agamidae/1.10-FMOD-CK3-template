# FMOD CK3 template
A template FMOD project with all GUIDs replaced and VCAs set up

IMPORTANT! The bank name can cause a crash on exiting the game.

My tests suggest the name should precede "Master Bank" name alphabetically.
"Mazter" and "New" crash, but "Ma", "Key" or "List" don't.

1. Download, unzip it, open '1.10 fmod ck3 template.fspro' in FMOD.
2. If it asks to recover the file, agree. Re-save it as your own project.
3. Add your sounds to the Assets tab.
4. Right-click them and create events (any type, pick 2D timeline if unsure).
5. Go to Events tab, right-click your events and assign them to the Bank bank.
6. Go to Banks tab and rename the bank to something unique to avoid conflicts with other mods or game files, try names between A-M.
7. Go to Window > Mixer Routing (Ctrl+5).
8. Right-click your events and assign them to appropriate VCAs, these are game's volume controls. Without it, our sounds would blast players at full volume.
9. Save and build the project from File > Build, F7.
10. Copy the banks to your mod /sound/banks.
11. For the future, you can tell FMOD to build right to the mod folder, in Edit -> Preferences -> Build.

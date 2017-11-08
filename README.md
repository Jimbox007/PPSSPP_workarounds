# PPSSPP_workarounds
Just a dump of few cwcheat hacks made to workaround some games problems.

For use with PPSSPP v1.3-604-g9ed55f2 or newer, simply enable cheats, dump cheat.db into your memstick/PSP/Cheats folder("memstick" location will differ depending on platform) then use "Import from cheat.db" from inside PPSSPP cheat menu. In older PPSSPP versions you might need to manually copy those cheats since importing was partialy broken.
Note: [Disable] cheats are restoring original game code, if there's no [Disable] cheat, you have to restart emulation after unchecking the cheat to revert it's changes.

Might not have all stuff, I'm dumping those hacks here exactly because loosing track of how many I made;p. Also this will have only fixes/workarounds, no enhancements like LOD/FPS/Right Analog/etc.(exceptions for enhancements that works around problems), since I don't want to mix potentially unsafe patches here:]. Also note while I might refer to many of those patches as fixes, they merely breaking games to match broken emulation(two negative into positive kind of thing;p), breaking bad design choices that causes problems or simulate unimplemented stuff.

List of game workarounds currently included:
- Activision Hits Remixed (fix graphics with slow effects disabled for speed also boot fix), [ULES-00640]
- Armored Core 3 Portable (fix freeze), [NPUH-10023], [ULJM-05492]
- Armored Core: Last Raven Portable (fix freeze), [NPUH-10024]
- Armored Core: Silent Line Portable (fix freeze), [NPUH-10025]
- Assassin's Creed: Bloodlines (PS3 Connectivity, fix save data loading), [ULES-01367]
- Auditorium (fix black screen), [NPUH-10069]
- Battle Robot Damashii (fix geometry), [NPJH-50720]
- Bleach: Soul Carnival (fix freeze), [UCJS-10085]
- Bleach: Soul Carnival 2 (fix freeze), [UCJS-10106], [UCAS-40297 ? unsure/user I made it for only said "chinese version"]
- Blitz: Overtime (fix fps), [ULUS-10200]
- Brian Lara 2007: Pressure Play (fix fps), [ULES-00814]
- Carnage Heart EXA (hide some UI glitches), [NPEH-00154]
- Castlevania: The Dracula X Chronicles (resolution patches and SotN Richter brandish whip fix), [ULES-00841]
- Colin McRae Rally 2005 Plus (fix lens flare), [ULES-00111]
- Driver 76 (removes spiky vertices), [ULES-00740]
- Final Fantasy Tactics: The War of the Lions (battle animation and original resolution patches), [ULES-00850]
- Final Fantasy Type 0 (remove blur in cutscenes to fix Emina scenes), [NPJH-50443], [NPJH-50444]
- Ford Racing Off Road (removes fog), [ULES-10326]
- Ford Street Racing(L.A. Duel, XR Edition, Bold Moves) (removes fog), [ULES-00564], [ULES-00588], [ULUS-10159]
- Gundam Assault Survive (fix geometry), [ULJS-00281]
- Hokuto no Ken: Raoh Gaiden - Ten no Haoh (display otherwise missing 2D graphics), [ULJM-05404]
- Imagine Champion Rider (unlock fps), [ULES-01161]
- Juiced 2: Hot Import Nights (remove glitchy effect), [ULES-00928]
- Kenka Bancho Badass Rumble(remove ugly barriers), [ULUS-10442]
- Kenka Bancho 4: Ichinen Sensou(remove ugly barriers), [ULJS-00268]
- Macross Triangle Frontier (fix geometry), [ULJS-00321]
- Macross Ultimate Frontier (fix geometry), [NPJH-50050]
- Me & My Katamari (remove glitchy effect), [ULUS-10094]
- Mega Man Powered Up (movement mods), [ULES-00307]
- Metal Gear Solid: Peace Walker (simulates recruit discovery), [ULUS-10509]
- Mighty Flip Champs DX (set volume to max), [NPUZ-00238]
- Monster Hunter Freedom (synchronize savedata with savestate made earlier), [ULES-00318], [ULUS-10084]
- Monster Hunter Freedom 2 (synchronize savedata with savestate made earlier), [ULES-00851], [ULUS-10266]
- Monster Hunter Freedom Unite (synchronize savedata with savestate made earlier), [ULES-01213], [ULUS-10391]
- Monster Hunter Portable 2nd G (synchronize savedata with savestate made earlier), [ULJM-05500]
- Monster Hunter Portable 3rd (synchronize savedata with savestate made earlier), [ULJM-05800]
- Monster Hunter Portable 3rd HD Ver. (synchronize savedata with savestate made earlier), [NPJB-40001]
- n+ (drop down volume to hearable levels), [ULUS-10340]
- Ore no Dungeon (hide some glitchy graphics), [ULJM-05167]
- Patapon 3 (synchronize savedata with savestate made earlier), [UCUS-98751]
- Sakura Taisen 1 & 2 (remove some effects which can eat ~ 6gb of vram), [ULJM-05109]
- Samurai Shodown Anthology (remove magnification filter glitching SSVI), [ULUS-10401]
- San Goku Shi IX with Power-Up Kit (black background fix), [ULJM-05842]
- Senjou no Valkyria 3 E2 (black sky fix), [ULJM-05957], [ULJM-05781 english patch for E2 which uses incorrect ID]
- Sonic Rivals (fix graphics with slow effects disabled for speed), [ULES-00622]
- Sonic Rivals 2 (fix graphics with slow effects disabled for speed), [ULES-00940]
- Spider-Man: Friend or Foe (workarounds loading savedata loop), [ULUS-10318]
- Test Drive Unlimited (remove ugly&slow effect), [ULUS-10249]
- Tokyo Mono Harashi: Karasu no Mori Gakuen Kitan(improve framerate), [NPJH-50215]
- Tony Hawk's Underground 2 Remix (JIT crash fix), [ULES-00033], [ULUS-10014]
- Valkyria Chronicles II (black sky fix), [ULUS-10515]
- Valkyrie Profile: Lenneth (credits movie freeze workaround), [ULUS-10107]
- Zettai Zetsumei Toshi 3 (pass character selection screen). [ULJS-00191]
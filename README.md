# dw3-tas

when to advance text:
- on the frame before the last character appears
- on the frame before a Yes/No box appears

each step is 8 frames (16 in overworld)

encounters seem to be step-based; i.e. an encounter WILL happen every n frames, and i haven't been able to avoid it
they are determined by the address 0C61. the max i've seen is 39. every step in an area with encounters decreases this value by 1-2. certain actions "refill" this address, including changing area (e.g. stairs, entering houses), entering/exiting the overworld, and finishing/fleeing a battle. note: exiting overworld (i.e. entering town) decreases this value, almost always by 12. i still don't know *how* the refill works, so I've just been waiting frames and inputting on the frame that causes the biggest refill. true optimisation would involve determining minimum number of steps required in each area, the corresponding minimum 0C61 value required, and the minimum number of frames waited.

battle fade animation test (take step -> right after red zone)
- 124: windmill, arrow down, vertical/horizontal stripe, messy stripe, spiral
- 126: rectangle

flee battle = 47 frames

Return = level 7
Outside = level 14

- Aliahan: talk to king, party: Dealer (New Town), Cleric, Wizard, buy 2 WarpWing, sell something
- Reeve: (E) visit (E)
- Promontory Cave: pass through (E)
- Najimi Tower: ThiefKey, warp to Reeve
- Reeve: MagicBomb, $Sickle 320
- Tempt Cave: blow up wall
- Romaly: $Spear 650, (get 2 WarpWings latest by now?), initiate Kandar quest
- Pachisi: trigger glitch?, Wooden Boomerang for Kandar group
- Kazave: visit
- Kandar: Boomerang OHKO?, warp to Romaly
- Romaly: become King (sleep), quit being King
- Norud's Tunnel: pass through
- Ashalam: visit
- Isis: $Iron Axe 2500, Starry Bracelet?
- Pyramid: MagicKey, warp to Romaly
- Portoga: $Steel Whip 3100, initiate pepper quest, warp to Ashalam
- Norud's Tunnel: pass through
- Baharata: initiate Gupta quest
- Baharata Cave: Kandar2, warp to Baharata
- Baharata: get pepper, warp to Portoga
- Portoga: get ship, warp to Aliahan
- Lancel: HideHerb, warp to Noaniels
- Edinbear: Dry Vase, warp to Aliahan
- Shoals: FinalKey, begin orbs segment
- 
- Purple: from Reeve, Zipangu, initiate Orochi quest?, NohMask, Orochi Sword
- Red: from Aliahan, Pirate Cove
- Blue: Lancel Temple, Terra Armor?
- Green: from Noaniels, DarkLamp
- 
- Silver: from Romaly, Greenlad, Samanao, $Zombie Sword 6700, Lar Mirror, BossTroll
- (Edinbear ->) Wizard's Cabin: Bone
- manipulate Phantom Ship ("the body of water between Romaly, the Pyramid, and Assaram"), LuvMemory, warp to Noaniels
- Shrine Jail: Gaia Sword, warp to Ashalam
- Volcano: form bridge
- Gondo Cave: Thunder Sword, Blade Armor?, Silver Orb
- 
- Yellow: from Edinbear, earliest after BossTroll (to confirm); bring Dealer, probably last
- 
- (Noaniels ->) Leiamland: Laima
- Dragon Queen: Light Orb? (Zoma), warp to Isis
- Baramos Castle: Baramos, end 1st world
- 
- 
- 
- 
- 

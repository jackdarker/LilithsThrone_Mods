# LilithsThrone_Mods
some mods for the game:

WIP:
- metall Ball-Stretcher: locking BDSM gear; use PENIS-slot (because there is no BALLS), 
- cock ring (metal)
- ladder piercing for cock

IDEAs:
- a NPC to spawn the items on
- leather Ball-stretcher
- Humbler: makes NPC crawl?
- Penis-Plug: reduces expulsion to 10%?
- Wip/Paddle: WEAPON; for BDSM play
- feral tentacle monsters
- felkin
- bondage racks for slaves (as a milking stall alternative?)
- something to disable ENCHANT-button; instead you would have to find a NPC and pay him with essence to enchant something once in a while
- when I equip my slaves with transformative enchantments, i would like to get a notification of there change, at least in the occupation ledger
- make it more difficult to get equipment. Why go shopping if I can rob everyone naked. Maybe limit how many items you can loot from someone you defeated.
- the possibility to mark an item as scrap and sell them with a click - it takes ages to sell each single item
- make it more difficult to create enchantments. Especially you might first have to do something before you are able to create a certain enchantment.
- some interactive slave-training to give them fetishs or attributes. A good price for a slave should require some training.
- why cant I be locked in the milking stall?
- NPC that curse your equips with enchantments (alternative to forced TF)
- add info if someone births your childs (slaves only or all characters?)
- add info on bodychange of slave by enchanted item?
- modify the job-trait of slaves to make use of other options then mugger and prostitute

somewhat based on existing mods and this documentation: https://github.com/bicobus/lilith-throne-documentation

Installation
-----------------------------
Copy the res-directory over the res-directory in your LT-game installation.
The src-directory contains the raw svg-files that need to be cleanded up for the game.

Cleaning the SVG
-----------------------------
- when saving in inkscape, there is always a width & height element (additional to viewbox). Those needs to be removed or the game will always use this size !

To optimize Inkscape generated SVGs in the src-directory:
- use NPX to run from that location (because I have svgo installed locally instead of global)
- specify path to innoxia svgoConfig.yml
- specify input/output of my files (it will process all svg's and place them into \res)
D:\Projects\Javascript\SVGtoJS\node_modules\svgo\bin
npx svgo --config=D:\Projects\Java\liliths-throne-public\svgoConfig.yml -r -f D:\Projects\Java\LilithsThrone_Mods\src D:\Projects\Java\LilithsThrone_Mods\res
for svgo v2.0.0 new config format !->
npx svgo --config=D:\Projects\Java\LilithsThrone_Mods\src\svgoConfig.js -r -f D:\Projects\Java\LilithsThrone_Mods\src D:\Projects\Java\LilithsThrone_Mods\res
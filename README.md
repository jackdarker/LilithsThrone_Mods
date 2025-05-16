# LilithsThrone_Mods
some mods for the game:

WIP:
- metall Ball-Stretcher: locking BDSM gear; use PENIS-slot (because there is no BALLS), 

IDEAs:
- a NPC to spawn the items on
- leather Ball-stretcher
- cock ring (steel)
- Humbler: makes NPC crawl?
- Penis-Plug: reduces expulsion to 10%?
- Wip/Paddle: WEAPON; for BDSM play
- feral tentacle monsters
- felkin
- bondage racks for slaves (as a milking stall alternative?)
- something to disable ENCHANT-button; instead you would have to find a NPC and pay him with essence to enchant something once in a while
- NPC that curse your equips with enchantments (alternative to forced TF)
- add info if someone births your childs (slaves only or all characters?)
- add info on bodychange of slave by enchanted item?
- modify the job-trait of slaves to make use of other options then mugger and prostitute

somewhat based on existing mods and this documentation: https://github.com/bicobus/lilith-throne-documentation

Installation
-----------------------------
Copy the res-directory over the res-directory in your LT-game installation.

Cleaning the SVG
-----------------------------
To optimize Inkscape generated SVGs in the src-directory:
- use NPX to run from that location (because I have svgo installed locally instead of global)
- specify path to innoxia svgoConfig.yml
- specify input/output of my files (it will process all svg's and place them into \res)
D:\Projects\Javascript\SVGtoJS\node_modules\svgo\bin>
npx svgo --config=D:\Projects\Java\liliths-throne-public\svgoConfig.yml -r -f D:\Projects\Java\LilithsThrone_Mods\src D:\Projects\Java\LilithsThrone_Mods\res
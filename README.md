# SRPG-Studio-Unit-Direction-Fix
fixes unit direction when selected on the map

in default SRPG Studio, when you select a unit to move on the map, the unit automatically faces right - it doesn't seem like theres an in-engine fix for this, so i made a little plugin for it. i do not know javascript, and pieced this very small script together using Goinza's plugin tutorial. if theres anything wrong with it, please feel free to let me know!

to change which direction the unit will face when selected, simply change the text of "DirectionType.BOTTOM" from BOTTOM to one of the following:

NULL: Idle animation in the charchip, first row

TOP: upwards-facing animation in the charchip, second row

RIGHT: right-facing animation in the charchip, third row

BOTTOM: down-facing animation in the charchip, fourth row

LEFT: left-facing animation in the charchip, fifth row


to contact me, please do so via my twitter (@tenshibyou)

# Ruathey
## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);


**You say:** `hail`



>**Ruathey says:** Hello Soandso

if(qglobals["Ruathey"] ~= nil) then


**You say:** `sword`




>**Ruathey says:** I've heard stories about a holy sword. There are many rumored to be hidden all throughout the world, yet only a few have actually been found. Amstaf had one of these swords. It is known for its ability to dismiss the undead. Perhaps by having this sword it'll bring you closer to finding your friend. Gather a ghoul's heart, Amstaf's Scroll, the Blade of Nobility, a noblemans hilt and place them in this [bag].


**You say:** `bag`




>**Ruathey says:** Take this bag and gather the items I've mentioned. I've been told that the Ghoul's Heart can be found in the estate of the undead, while the scroll can be found in the Keep not far from the Karanas. One of the others are rumored to be found near the dwarven city among the goblins. While the last should be found in the caverns of Najena.



**You receive:**  [Noblemans Bag](/item/17878)



eq.delete_global("Ruathey");

end

## Turn-Ins




if **You turn in:** [Note to Ruathey](/item/2417)


>**Ruathey says:** I see that you've spoken to Llara. She too came to me looking for Amstaf. Though she wasn't able to find her friend, she was able to recover his [sword].


eq.set_global("Ruathey","ghoul",0,"D30");


 **You receive:** 0 (+500 exp)

**This NPC *should* return incorrect items given.**

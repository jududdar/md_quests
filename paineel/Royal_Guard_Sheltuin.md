# Royal Guard Sheltuin
## Dialog

**You say:** `hail`



>*Royal Guard Sheltuin appears to be ignoring you completely.*

**You say:** `audience with the overlord`



>**Royal Guard Sheltuin says:** The Overlord is not seeing anyone at this time. however. I may have work for you. You seem to have some experience with the kobold annoyance in the region. Are you [interested]. Soandso?

**You say:** `interested`



>**Royal Guard Sheltuin says:** Then I shall give you a task. I assume you are aware of the kobold lair nearby. Many of our adventurous knights and priests crusade to destroy those pests so seeing many Erudites frequent the area is normal. However. it is not normal to see someone carry large crates into the lair and return empty handed. This person's movements also show he is attempting to remain unseen.....the [fool].

**You say:** `fool`



>**Royal Guard Sheltuin says:** Whoever it is. obviously is not an Erudite. even though he appears to be. Only an outsider would take us to be such idiots as to fall for their pitiful attempt at disguise. Or perhaps....well. never mind that. I want you to enter the kobold lair and find these crates. Return one to me and we'll decide what to do from there.

**You say:** `important task`



>**Royal Guard Sheltuin says:** According to the evidence we've uncovered, it appears the kobolds are nothing but pawns to harass us. Or perhaps even all of Odus. If they wish to play these games, then we'll humor them. We'll take their pawn with one of our knights. Will you be the knight, Soandso?

**You say:** `knight`



>**Royal Guard Sheltuin says:** Then you will deliver this chest for us. Don't worry about what's inside it. Although we enjoy our solitude, we do make allies. We also make use of those allies. We will do so now. Take the chest to Lyris Moonbane below the human city of Qeynos. You will then follow her instructions and complete any tasks she assigns you. In return, she will send you back with what we wish. Fear is our armor.


**You receive:**  [Heavy Locked Chest](/item/1792)
end

## Turn-Ins



local text = "Is this it? I asked for the head of the courier, the head of the supplier, a full box of ore, and evidence from the supplier. Do not return until you have all of these!";




if( **You turn in:** [Large Empty Crate](/item/1773)) then


>**Royal Guard Sheltuin says:** Hmmm. Very odd. The dust in the crate implies some sort of stone was transported in it. Perhaps our brothers of the Arcane will be able to find out where this dust came from and what it?s used for. Take this dust sample and note to Keletha Nightweaver. She will examine the dust and send you back with a report. Make haste.


 **You receive:**  [Envelope with dust sample](/item/1774) (+137180 exp)

elseif( **You turn in:** [Heretic's Report](/item/1775)) then


>*Royal Guard Sheltuin 's eyes redden with intense anger after reading the report. When he speaks, his voice is suprisingly calm and measured. He says, 'Listen close " .. e.other:Race() .. ". When you leave this building, you will find the courier who is bringing the ore. You will kill him, and collect his head and a box of the ore. You will then find the supplier, and collect his head and any other information you find on him. Bring me these four things and you will be rewarded. Do not fail.'*


 **You receive:** 0 (+137180 exp)

elseif( **You turn in:** [Crate full of Ore](/item/1776), [Courier's Head](/item/1777), [Sealed Letter](/item/18174), [Supplier's Head](/item/1778)) then


>**Royal Guard Sheltuin says:** Honestly Soandso, I thought you would not return. Such strength and intelligence in a Knight of Fear I have not seen for quite some time. Wear this in pride of the ancient Ridossan. Perhaps when you are ready, I will give you a more [important task]. This conspiracy must be stopped.


* __Faction:__ [Heretics](/faction/265) (20)


* __Faction:__ [Deepwater Knights](/faction/242) (-20)


* __Faction:__ [Gate Callers](/faction/254) (-20)


* __Faction:__ [Craftkeepers](/faction/231) (-20)


* __Faction:__ [Crimson Hands](/faction/233) (-20)


 **You receive:**  [Leggings of Ridossan](/item/1764) (+137180 exp)

elseif( **You turn in:** [Empty Jar](/item/1892)) then


>**Royal Guard Sheltuin says:** Well done, Soandso! Now we need only wait for the kobolds to start dying off and our plan will be complete. Should only take 8 years or so. One such as yourself will wear this ancient armor well. The Tunic of the crusader Rodossan is now yours.  He shall watch over and praise you in your triumphs... your defeats on the other hand... well, never mind that.


* __Faction:__ [Heretics](/faction/265) (40)


* __Faction:__ [Deepwater Knights](/faction/242) (-40)


* __Faction:__ [Gate Callers](/faction/254) (-40)


* __Faction:__ [Craftkeepers](/faction/231) (-40)


* __Faction:__ [Crimson Hands](/faction/233) (-40)


 **You receive:**  [Tunic of Ridossan](/item/1765) (+137180 exp)

**This NPC *should* return incorrect items given.**

# Althele




## Dialog

**You say:** `hail`



>**Althele says:** Hello, friend. Beautiful is what I would call such a day normally but lately? I sense that something is [out of balance].

**You say:** `balance`



>**Althele says:** I sense something foreboding, young one, but you should think nothing of it. The sons and daughters of nature will be able to deal with this problem.
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_647.png" alt="" /> <a
                                href="/item/20448" data-url="20448" class="tooltip-link link">Worn Dark Metal Coin</a>) then


>*Althele looks at the coin and nods gravely at you as she slips it into a fold of her clothing. 'I see. The story of this coin speaks much to me as do the words you have given me. Telin sent word that you would arrive. The tidings you bring are ill indeed. Here, take this amulet and find Sionae. She is nearby. We will speak more on this matter when all are present.'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1053.png" alt="" /> <a
                                href="/item/20450" data-url="20450" class="tooltip-link link">Braided Grass Amulet</a> 

 


**Spawn NPC:**  [Sionae](/npc/15178) at (**y:** -2595, **x:** -1595)

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/20452" data-url="20452" class="tooltip-link link">Fleshbound Tome</a>) then


>*Althele hands the book to Tholris who reads through it with lines of concern etched on his face, then whispers into her ear. 'Dire news, indeed. This cannot be allowed. I must keep this book but you, Soandso, must not allow Innoruuk to seed the land with his hatred and filth. You have only just begun your quest. The path you are guided upon will be difficult, if not impossible, but someone must finish it. Please, take this, read of it, follow its instructions. Tunare bless your path and Karana watch over you.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18959" data-url="18959" class="tooltip-link link">Earth Stained Note</a> (+100000 exp)

 




**Despawn NPC:**  [Sionae](/npc/15178)


**Despawn NPC:**  [Nuien](/npc/15167)


**Despawn NPC:**  [Teloa](/npc/15170)


**Despawn NPC:**  [Tholris](/npc/15043)


**Despawn NPC:**  [Fang](/npc/15042)


**Althele despawns.**

**This NPC *should* return incorrect items given.**



## Signals

if(e.signal == 1) then


>**Althele says:** Great mother of life and father of sky, growth and spirit, Tunare and Karana. Innoruuk once again schemes and we have failed in our duties to protect our land. We give your powers in sacrifice fo ryour help. Heed our call and send us your wisdom.
end

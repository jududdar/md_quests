# Astaed Wemor


## Dialog

local fac = e.other:GetFaction(e.self);


**You say:** `hail`



>**Astaed Wemor says:** Greetings. I am Astaed Wemor of the Paladins of the Temple of Life. We are the defenders of the all-giving Prime Healer. Are you [here to pray] or are you [here to assist the temple]?

**You say:** `here to pray`



>**Astaed Wemor says:** Then pray long and silently, Soandso. Fill your soul with the breath of life.

**You say:** `assist the temple`



>**Astaed Wemor says:** Good.  There are a few in the congregation who require assistance.  Will you be [traveling afar] or are you [staying close to Qeynos]?

**You say:** `traveling afar`



if **Faction** >= Amiable +50 then



>**Astaed Wemor says:** Then outfit yourself well. We will require you to visit Rivervale, the village of the halflings. There you shall find an herb merchant named Kizzie Mintopp. She has an ingredient we require. Tell her you are from the Temple of Life


elseif **Faction** >= Indifferent then



>**Astaed Wemor says:** I do not dislike you, but I cannot fully trust one who has yet to prove his service to the Prime Healer.  Perhaps you can assist us in ridding the land of diseased animals. Priestess Caulria will accept all pelts from rabid beasts.




else



>**Astaed Wemor says:** Foolish person! The word is out amongst the followers of the Prime Healer not to trust you.


**You say:** `staying close to qeynos`



if **Faction** >= Amiable +50 then



>**Astaed Wemor says:** Then you can help with one of our distraught members. The priests have noticed that Nerissa Clothspinner has been a little down lately. Go console her and ask her how she is doing. She is a sweet girl and the temple is worried about her.


elseif **Faction** >= Indifferent then



>**Astaed Wemor says:** I do not dislike you, but I cannot fully trust one who has yet to prove his service to the Prime Healer.  Perhaps you can assist us in ridding the land of diseased animals. Priestess Caulria will accept all pelts from rabid beasts.




else



>**Astaed Wemor says:** Foolish person! The word is out amongst the followers of the Prime Healer not to trust you.


**You say:** `Lempeck Hargrin`





>**Astaed Wemor says:** Have you run into poor, sick Lempeck? He has been ill for quite some time. I have promised to deliver a secret healing potion which might help. Perhaps you can be of assistance and retrieve the potion for me... That is, if you don't mind [traveling afar].



**You say:** `bertoxxulous`



>**Astaed Wemor says:** The beast of the plague.  Bertoxxulous is the foe who spits disease upon the land and mutates the perfection which is life.  He shall soon meet his fate at the hands of Rodcet Nife and as for his followers, the Bloodsabers, they shall meet their doom by the hand of the Temple of Life.

**You say:** `rodcet`



>**Astaed Wemor says:** The river of life which flows through us all originates from the power of Rodcet Nife, the Prime Healer.  He maintains the flow and if any ailment should block its path, the Temple of Life does whatever is necessary to keep the river running.  If this calls for the death of another being, then so be it.  Let one river die so that all may flow freely.

**You say:** `heal`



>**Astaed Wemor says:** I cannot help you with your request.   You must speak with Brother Tonmerk Plorsin.
end



## Turn-Ins





if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18862" data-url="18862" class="tooltip-link link">A tattered note</a>) then




>**Astaed Wemor says:** So you have helped Nerissa. That is good. Here, then, is a small reward. May you find it useful. Keep fighting the good fight!





Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+5</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+2</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6022" data-url="6022" class="tooltip-link link">Bronze Warhammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6023" data-url="6023" class="tooltip-link link">Bronze Flail</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6024" data-url="6024" class="tooltip-link link">Bronze Morning Star</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_738.png" alt="" /> <a
                                href="/item/6025" data-url="6025" class="tooltip-link link">Bronze Warclub</a>) (+4000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_688.png" alt="" /> <a
                                href="/item/13952" data-url="13952" class="tooltip-link link">Honey Jum</a>) then


>**Astaed Wemor says:** I pray to Rodcet Nife that you have made it back in time. Let's add a small amount of this honey jum to this and.. here is the potion. This potion must be taken to a sick member of the congregation. The man is Lempeck Hargrin. He lives in the west plains of Karana between the river and the crop fields. He is in dire need of this potion. He has an odd disease. We have tried everything to cure him and this is his last chance. Run to him.





Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+20</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+6</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+10</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+3</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_599.png" alt="" /> <a
                                href="/item/13954" data-url="13954" class="tooltip-link link">Prime Healer Potion</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_599.png" alt="" /> <a
                                href="/item/13955" data-url="13955" class="tooltip-link link">Prime Healer Potion</a>) (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_579.png" alt="" /> <a
                                href="/item/13970" data-url="13970" class="tooltip-link link">Rusty Scythe</a>) then


>**Astaed Wemor says:** It is good to know that we saved Lempeck. He has given us his scythe as a donation to the temple. We shall find a use for it. As for your fine work at preserving the life of another, I reward you with the Shining Star of Life. Should you ever desire more strength in battle, call upon it to give you strength, but let it be known that at battle's you shall feel weaker than before you called upon the power. Just for a short time. When the power is drained, go to our temple storehouse and ask Whysia to [recharge the Shining Star of Life]. Go and serve life.





Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+20</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+6</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+10</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6356" data-url="6356" class="tooltip-link link">Shining Star of Light</a> (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;


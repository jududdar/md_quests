# Camlend Serbold
## Dialog

local fac = e.other:GetFaction(e.self);


**You say:** `hail`



>**Camlend Serbold says:** I say, good to meet you, Soandso!  I am Camlend Serbold.  Some call me Serbold the Great.  I am the leader of the righteous order of paladins which serves the Temple of Life.  Together with the clerics of this temple, we defend the will of the great [Rodcet Nife] and smite all who dare to oppose us.

**You say:** `rodcet`



>**Camlend Serbold says:** Do you feel your heart beating within your chest?  It is Rodcet Nife, the Prime Healer, whose breath keeps it in perfect rhythm.  If you do not pray to His glory then I assure you, someday when your heart begins to slow, you shall be crying out loud to Rodcet Nife.

**You say:** `bloodsaber`



>**Camlend Serbold says:** So you have heard the name of the Bloodsabers?!  They are the followers of Bertoxxulous.  We have heard rumors of their existence within the city.  We have yet to find any of his followers inside the walls of Qeynos.  As for beyond the walls, there are some...

**You say:** `bertox`



>**Camlend Serbold says:** You'd best whisper that vile name within these walls!  The Lord of Disease has no place in our temple.  His hand has reached far enough into our lands.  We must cut it off!

**You say:** `lord grimrot`



>**Camlend Serbold says:** You have heard of Lord Grimrot? He is a shadowknight working with the Bloodsabers. We have word he is trying to build an army of undead. Only a powerful knight can rid the lands of Grimrot. So, did you come here to [defend life]?

**You say:** `linarius`



>**Camlend Serbold says:** Captain Linarius Graffe is the captain of the tower guards outside Qeynos.  He is headquartered in a bridge keep in the Plains of Karana.  He often informs the local guild of any activity which may be of concern to us.

**You say:** `defend life`



if **Faction** >= Warmly +250 then 



>**Camlend Serbold says:** Then go to the Plains of Karana. Somewhere there, Lord Grimrot is hatching his little plan for the Bloodsabers. Bring me his evil scythe and his heart. It is said that upon his death, his soul will be absorbed into this weapon of darkness. Do this and be rewarded.


elseif **Faction** >= Indifferent then



>**Camlend Serbold says:** The Temple of Life smiles upon you, friend...  but such a delicate matter can only be entrusted to our most loyal members.


else



>**Camlend Serbold says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.



end

## Turn-Ins



local fac = e.other:GetFaction(e.self);

local text = "We must have both Lord Grimrot's scythe, Pestilence, and his misshapen heart.";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18711" data-url="18711" class="tooltip-link link">A tattered note</a>) then 


>**Camlend Serbold says:** Welcome to the Temple of Life. You have much to learn and we have much work to do. Pain, hurt, disease and death lurk everywhere, our job is seemingly endless, but none is more gratifying. Here is our guild tunic, represent us well. Davloran Girionlis will help you to get started.


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+100</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+30</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+50</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-25</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13506" data-url="13506" class="tooltip-link link">Faded Tunic*</a> (+100 exp)

 



elseif **Faction** >= Warmly +250 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_579.png" alt="" /> <a
                                href="/item/13324" data-url="13324" class="tooltip-link link">Pestilence Scythe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/13325" data-url="13325" class="tooltip-link link">Decaying Heart</a>) then 


>**Camlend Serbold says:** We thank you for your service. With Lord Grimrot's evil soul trapped in this scythe, all but the truly evil shadowknights would be able to wield it. I would like to present you with this as a token of our appreciation. Your devotion to life is supreme. Go now, and serve life.





Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+5</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+2</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_805.png" alt="" /> <a
                                href="/item/12238" data-url="12238" class="tooltip-link link">Aegis of Life</a> (+1000 exp)

**You receive coin:** 1-5 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;


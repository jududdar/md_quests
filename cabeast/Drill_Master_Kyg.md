# Drill Master Kyg
## Dialog

**You say:** `Hail`



>**Drill Master Kyg says:** Welcome. Welcome!!  Time to train.  Time to fight.  Time to serve the Iksar Empire.  You will need weapons.  I have the [footman pike] for all new recruits to earn.

**You say:** `pike`



>**Drill Master Kyg says:** A footman pike is what you need.  A footman pike is what you get, but earn it you will.  You must [slay many beasts] to prove to us that you are a true warrior.  Fail and you will be exiled to live with the Forsaken.

**You say:** `beasts`



if **Faction** >= Amiable then



>**Drill Master Kyg says:** Yes.  You will slay or you will be slain.  Take this footman's pack and fill it you will.  Fill it with [weapons of our foes].  When all are combined, the full footman's pack shall be returned to me along with your militia pike.  Do this and earn your footman pike and then we may have a true mission for you.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/17027" data-url="17027" class="tooltip-link link">Footmans Pack</a>


elseif **Faction** >= Indifferent then



>**Drill Master Kyg says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Kyg says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `weapons`



if **Faction** >= Amiable then



>**Drill Master Kyg says:** Yes.  You need to know the weapons required.  Fill the pack with javelins.  Froglok bounder and goblin hunter javelins.  Two of each.


elseif **Faction** >= Indifferent then



>**Drill Master Kyg says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Kyg says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `moglok`



if **Faction** >= Amiable then



>**Drill Master Kyg says:** My dear friend, Warlord Hikyg of the Swamp Gate has encountered some difficulty with a Trooper Moglok. He requested that I find a brave soldier to take charge of the situation. Are you willing to [assist Warlord Hikyg]?


elseif **Faction** >= Indifferent then



>**Drill Master Kyg says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Kyg says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `Hikyg`



if **Faction** >= Amiable then



>**Drill Master Kyg says:** Good. Take this note to Footman Moglok of the swamp garrison. He shall instruct you on your mission.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18234" data-url="18234" class="tooltip-link link">A Sealed Note</a>


elseif **Faction** >= Indifferent then



>**Drill Master Kyg says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Kyg says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.

end

## Turn-Ins



local text1 = "You were instructed to return with the full footmans pack and your militia pike.";




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/12430" data-url="12430" class="tooltip-link link">Full Footmans Pack</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/5131" data-url="5131" class="tooltip-link link">Militia's Pike</a>) then


>**Drill Master Kyg says:** Kyg knew you could do it. You will make a fine legionnaire some day but, for now, you shall be a footman. Take the footman pike head plans. Forge the footman's pike. Do so, and then you may have an audience with the War Baron on the subject of his [Memory of Sebilis].


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+5</span>)


Your faction standing with [Cabilis Residents](/faction/440) got better (<span class='text-success'>+1</span>)


Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+1</span>)


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+1</span>)


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/12475" data-url="12475" class="tooltip-link link">Footman Head Plans</a> (+500 exp)

 

**This NPC *should* return incorrect items given.**






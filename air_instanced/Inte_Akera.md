# Inte Akera


## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds
## Dialog

**You say:** `hail`



>**Inte Akera says:** Greetings, Soandso. I am Inte Akera. I have retired to the Plane of Sky after a long life toiling on Norrath's soil. Have you retreated here as well, or are you merely visiting?

**You say:** `toil`



>**Inte Akera says:** Long ago, before I came to this plane, I fought in the name of Prexus against all the evils that plagued Norrath. In that time, I have done everything one can do. I have fought for the causes of good. I gained the esteem of kings and lords. The sword I hold is but one example of the treasures I have sought and won. I have accomplished all that I can, have all that I desire. My toil is done and now I sit among the clouds in peace, occasionally blessing those who seek it and are found worthy.

**You say:** `blessing`



>**Inte Akera says:** Many come seeking my blessings. No matter how minor the blessing they ask, all must prove that they embody the qualities of a paladin before I bless them.

**You say:** `prove myself`



>**Inte Akera says:** I believe the two most important qualities of a paladin are nobility and sacrifice. Hand me an item of yours that proves you understand what nobility and sacrifice are. Be warned however, if I do not think as you do, I will simply accept the item as a gift, and give you no blessing.

**You say:** `nobility`



>**Inte Akera says:** Ah nobility. A true measure of a paladin. If you are wondering what to bring me, then perhaps you should look within yourself. Look into your soul for a great, burning fire of nobility and you will know.

**You say:** `sacrifice`



>**Inte Akera says:** Sacrifice is a virtue all paladins should strive for. The sacrifice of something dear to you will show your devotion. Perhaps something you use to smite the unholy undead.

**You say:** `accomplish`



>**Inte Akera says:** I accomplished many great deeds; far too many to name. I saved kings and kingdoms; I helped the weak and destitue; I accomplished all I sought to do, save one at which I failed.

**You say:** `failed`



>**Inte Akera says:** No.. I was unable to kill my most hated foe, Miragul. The head of this wretched, foul necromancer is forever out of the reach of justice. It would be worth restoring him to his former state for the chance to take his head as a trophy.

**You say:** `miragul`



>**Inte Akera says:** You think you can succeed where I cannot? Perhaps you can noble one.. Bring me the head of Miragul, his robe and hand me back the two blessings I gave you, and in return I shall bequeath to you this sword I carry. Good luck my friend.
end

## Turn-Ins




if( **Faction is** > Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5504" data-url="5504" class="tooltip-link link">SoulFire</a>) then 


>**Inte Akera says:** You have chosen wisely, my friend. Take this note as a token of my blessing upon you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18033" data-url="18033" class="tooltip-link link">Intes First Blessing</a> (+100000 exp)

 

elseif( **Faction is** > Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5403" data-url="5403" class="tooltip-link link">Ghoulbane</a>) then 


>**Inte Akera says:** You have chosen wisely, my friend. Take this note as a token of my blessing upon you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18034" data-url="18034" class="tooltip-link link">Intes Second Blessing</a> (+100000 exp)

 


elseif( **Faction is** > Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18033" data-url="18033" class="tooltip-link link">Intes First Blessing</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18034" data-url="18034" class="tooltip-link link">Intes Second Blessing</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_986.png" alt="" /> <a
                                href="/item/19073" data-url="19073" class="tooltip-link link">Miragul's Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1126.png" alt="" /> <a
                                href="/item/1254" data-url="1254" class="tooltip-link link">Miragul's Robe</a>) then 


>**Inte Akera says:** Long have I awaited this moment. You have done what even I thought impossible. Take this sword, the Fiery Avenger. You have earned both it and my deepest respect.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/11050" data-url="11050" class="tooltip-link link">Fiery Avenger</a> (+1000000 exp)

 



**Inte Akera despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Inte Akera despawns.**




# Master Rixiz


## Dialog

**You say:** `hail`



>**Master Rixiz says:** You are on the grounds of the Brood of Kotiz. If you do not belong, you must leave at once. There shall be no [third rank skullcap] for you.

**You say:** `third rank skullcap`



if **Faction** >= Amiable then



>**Master Rixiz says:** I offer the third rank apprentice skullcap to those who wear the second. If that is you, then you will do the [bidding of the tower].


elseif **Faction** >= Indifferent then



>**Master Rixiz says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Master Rixiz says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `bidding of the tower`



if **Faction** >= Amiable then



>**Master Rixiz says:** Take this glass canopic. Within it you shall place a brain for me. The brain I seek is that of a sarnak crypt raider. Any shall do. The ones we seek should be near the Lake of Ill Omen. When you obtain the brain, you must quickly put it into the glass canopic with [embalming fluid]. When these are combined, the canopic shall seal and if you return it to me with your second rank skullcap, I shall hand you the next and final skullcap.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/17023" data-url="17023" class="tooltip-link link">Brood Canopic</a>


elseif **Faction** >= Indifferent then



>**Master Rixiz says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Master Rixiz says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `embalming fluid`



>**Master Rixiz says:** Embalming fluid is created through brewing, but do not drink it!! You can learn about the process of brewing on our grounds.
end



## Turn-Ins



local text1 = "You shall get no skullcap until I have the preserved raider brain and your second circle apprentice skullcap.";

local text2 = "I will not be bothered unless you bring me everything!";





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1205.png" alt="" /> <a
                                href="/item/12411" data-url="12411" class="tooltip-link link">Preserved Sarnak Brain</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/14810" data-url="14810" class="tooltip-link link">Snaorfs Medallion</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_962.png" alt="" /> <a
                                href="/item/10033" data-url="10033" class="tooltip-link link">Fire Emerald</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_962.png" alt="" /> <a
                                href="/item/10033" data-url="10033" class="tooltip-link link">Fire Emerald</a>) then


>**Master Rixiz says:** Well done, here is your reference.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/14813" data-url="14813" class="tooltip-link link">Glosk's Reference: Boots</a> (+10000 exp)

 

**This NPC *should* return incorrect items given.**






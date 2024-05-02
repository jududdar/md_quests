# Nicholas
## Dialog

**You say:** `hail`



>**Nicholas says:** Greetings, friend. I am the keeper of the [Boots of Ro]. Please rest here with us in our camp of righteousness. No harm can come to you while we paladins keep watch.

**You say:** `boots of ro`



if **Faction** >= Indifferent +50 then  



>**Nicholas says:** If you desire the mold needed for smithing the Boots of Ro, then first, you shall prove your power. I have long sought an ancient holy weapon called the brazen brass kilij. I have heard rumors of detailed plans on how to make it, coming from Faydwer. Seek out the kilij plans. Bring them to me and you shall have the mold.


elseif **Faction** >= Indifferent then



>**Nicholas says:** You and I must be brothers and serve the Lord of Underfoot. Go to Kaladim and serve her cathedral. When you think you are ready. then ask Lord Datur if you are an [honored member] of the temple. If the answer is yes, then I will trust you.


else



>**Nicholas says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!




**You say:** `candle of bravery`



if( **Faction is** > Amiable) then 



**You say:** `candle of bravery`





>**Nicholas says:** You must be the one Sir Dru of Kaladim sent to retrieve the candlestick which was broken in the [orc onslaught]. I have only this piece in my possession as the other portion was taken by an [odd druid] of these mountains. Should you reclaim it, I am sure the maker of the candlestick can patch it together.




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_732.png" alt="" /> <a
                                href="/item/12276" data-url="12276" class="tooltip-link link">Stem of Candlestick</a>



**You say:** `orc remnant`





>**Nicholas says:** Here. We found this worthless orc bracelet with the name Klunga on it. There was also an orc shovel and a bag of Cauldron prawns. We left them, of course. The camp has now been taken over by the green-skinned orcs. I would advise you to stay clear of this camp in Lake Rathe.




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_509.png" alt="" /> <a
                                href="/item/12280" data-url="12280" class="tooltip-link link">Klunga's Bracelet</a>



**You say:** `orc onslaught`





>**Nicholas says:** The orcs attempted to take the hill, as they do on a frequent basis. We repelled them, of course, but a [blue orc] rushed off with the [Chalice of Conquest]. Where he came from, I do not know. He was no part of the battle!! I believe he just found an opportune moment to loot our camp.



**You say:** `blue orc`





>**Nicholas says:** I had a visiting ranger track him to his camp near Lake Rathetear. I spied the camp and saw his lifeless body near two other blue orcs. Apparently, he must have taken a fatal blow, but had enough stamina to make it to his camp. I returned the following day with my fellow paladins and found the camp long gone. The ranger, who was still with us, found two sets of tracks leading away. We found [orc remnants].



**You say:** `odd druid`





>**Nicholas says:** The mountains have been plagued not only by beasts, but by evil druids!! They attempt to force all men from this land. One has stolen the foot of the candlestick which holds the [Candle of Bravery]. I remember that battle cry of hers, 'Long live the green!!'.




elseif( **Faction is** > Dubious) then



>**Nicholas says:** You and I must be brothers and serve the Lord of Underfoot.  Go to Kaladim and serve her cathedral.  When you think you are ready, then ask Lord Datur if you are an [honored member] of the temple. If the answer is yes, then I will trust you.


else



>**Nicholas says:** How dare you approach a member of the Clerics of Underfoot?! Dogs such as you lie in the same bed as aviaks and ogres!!

end

## Turn-Ins




if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/12206" data-url="12206" class="tooltip-link link">Kilij Plans</a>) then 


>**Nicholas says:** Ahh!!  The kilij!!  The legend was true.  As for you..  the mold for the Boots of Ro.  Go and speak with Thomas for the final component.  Ask him of [Lord Searfire].  Brell be with you.


Your faction standing with [Clerics of Underfoot](/faction/227) got better (<span class='text-success'>+20</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+20</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/12304" data-url="12304" class="tooltip-link link">Mold of Ro Boots</a> (+100000 exp)

 

**This NPC *should* return incorrect items given.**

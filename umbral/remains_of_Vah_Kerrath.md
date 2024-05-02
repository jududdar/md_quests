# remains of Vah Kerrath
## Dialog

**You say:** `hail`



>**remains of Vah Kerrath says:** Fleshy mortal, can you not see that I am cursed to live in eternal anguish? What is it that you seek from me?

**You say:** `vex thal`



if **Faction** >= Warmly +250 then



**You say:** `vex thal`





>**remains of Vah Kerrath says:** The city of shadow is sealed by powerful magic. Only one that wears the talisman of Akelha Ra can pass through the seals on the gate. I have not been beyond the gates but rumors of dark prophets that possess great power have been heard throughout the ages.



**You say:** `dark prophet`





>**remains of Vah Kerrath says:** Only legends and rumors have circulated about the dark prophets in Vex Thal. I suspect that they are the reason for my eternally cursed state. If you could find someway to defeat the dark prophet leading those in Vex Thal and bring me back proof of the deed, I shall reward you with an ancient relic that I possess.




elseif **Faction** >= Indifferent then



>**remains of Vah Kerrath says:** I will not reveal the secrets I have discovered so easily. Since I am unable to leave the protection of the whisperling circle, I will need you to aid me in releasing the Elysian spirits from their tormented states. Destroy their remains and release their spirits from the grip of the shadow curse. Return four of their skulls to me as proof of your deeds. Only then will I impart my discoveries to you.


else



>**remains of Vah Kerrath says:** Begone from my sight corruptor of spirits. I will only aid my allies.

end

## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/8365" data-url="8365" class="tooltip-link link">Soul Essence of Aten Ha Ra</a>) then 


>**remains of Vah Kerrath says:** Soandso, you have done more than was ever expected. Take this and my blessing will be with you always.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_752.png" alt="" /> <a
                                href="/item/8364" data-url="8364" class="tooltip-link link">Talisman of Vah Kerrath</a> (+2000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/28102" data-url="28102" class="tooltip-link link">Elysian Skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/28102" data-url="28102" class="tooltip-link link">Elysian Skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/28102" data-url="28102" class="tooltip-link link">Elysian Skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/28102" data-url="28102" class="tooltip-link link">Elysian Skull</a>) then


>**remains of Vah Kerrath says:** You have done well. Clear your mind of all distractions and ask the whisperlings if you are worthy of my knowledge.


Your faction standing with [Whisperling](/faction/1520) got better (<span class='text-success'>+5</span>)


Your faction standing with [Akheva](/faction/1521) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** 0 (+1000 exp)

 

**This NPC *should* return incorrect items given.**

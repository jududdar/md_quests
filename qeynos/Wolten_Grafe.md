# Wolten Grafe
## Dialog

**You say:** `hail`



>**Wolten Grafe says:** Hail, noble Soandso. Remember to spread the words of Karana throughout the faraway lands on which you shall tread. We of the Temple of Thunder are looking for new members - good people who [wish to join our cause]. Let the call go out!

**You say:** `join the cause`



>**Wolten Grafe says:** That IS good news! If you walk the righteous path of the Rainkeeper, Karana, then you are truly noble. I have need of someone like that. I must find someone to perform a [dangerous mission] or perhaps you would rather [seek out the Rat King] or [crush the undead].

**You say:** `crush the undead`



if **Faction** >= Dubious then 



>**Wolten Grafe says:** Those who passed generations ago have had their bones exhumed and enchanted. Some evil force plagues this land with these evil skeletons. You will fight for us and crush the skeletons. Take this box and fill it with the bones of those creatures. We will not allow them to rise again and you shall earn our respect. Go forth and fight for Karana!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17941" data-url="17941" class="tooltip-link link">Box For Bones</a>


else



>**Wolten Grafe says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!



**You say:** `dangerous mission`





if **Faction** >= Apprehensive then



>**Wolten Grafe says:** You must go into the catacombs and find a man named Drosco Finlayer. Pass him this note. He has been deep undercover in the Shrine of Bertoxxulous and will have directions to that vile place. To do this will surely show your allegiance to this temple.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18804" data-url="18804" class="tooltip-link link">A Tattered Note</a>


else



>**Wolten Grafe says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!





**You say:** `seek out the Rat King`



>**Wolten Grafe says:** Under this city lie the catacombs of Qeynos. Somewhere down there lurks the Rat King. None have truly seen him, but we know of him. It is he who plagues us with the recent infestation of rats. Why? Who knows? We need a brave member to [hunt the Rat King].

**You say:** `hunt the Rat King`



if **Faction** >= Dubious +300 then



>**Wolten Grafe says:** You are truly brave, young knight. Go to the catacombs. Find the Rat King. Bring me his head as proof of your noble deed. He must be stopped. Beware of his allies. May Karana watch over you.


else



>**Wolten Grafe says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!


**You say:** `Bertoxxulous`



>**Wolten Grafe says:** Bertoxxulous, the Plaguebringer, is the Lord of Disease. It is he who smites Norrath with his diseases and imperfections. Those who follow him are called [Bloodsabers].





**You say:** `Bloodsabers`



>**Wolten Grafe says:** It is rumored that there is a shrine in the great city of Qeynos which pays homage to the Plaguebringer, Bertoxxulous. The members of this vile church of the damned are called the Bloodsabers. They are dreaded shadowknights, necromancers and evil clerics. It is our duty to destroy all who dare to pray to such a deity. Join our fight. Speak more of this matter with Chesgard Sydwend.






**You say:** `karana`



>**Wolten Grafe says:** Karana, the Rainkeeper, is the provider of the storms. If it were not for the storms of Karana, life would not flourish. All should pay tribute to the Rainkeeper.

**You say:** `healer`



>**Wolten Grafe says:** If you need to be healed, I suggest you speak with the Priests of Life. You can find them in the Temple of Life on the other side of Qeynos. The only service you can pay for here is holy armor. Daedet Losaren charges followers of Karana for that blessing.
end

## Arrive at Waypoint Script

if(e.wp == 4) then


>**Wolten Grafe says:** Your Excellency, we need to recruit a newcomer to find and infiltrate the Shrine of Bertoxxulous. The Shrine's eyes are watching all our moves.


**Signaled to:**  [Runethar Hamest](/npc/1128)
end

## Turn-Ins




if **Faction** >= Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/13882" data-url="13882" class="tooltip-link link">A Box of Bones</a>) then 


>**Wolten Grafe says:** You have done well. Let it be known to all that you fight for the Rainkeeper. Go and continue the battle.





Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+10</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-10</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+7</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+7</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/13006" data-url="13006" class="tooltip-link link">Water Flask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13007" data-url="13007" class="tooltip-link link">Ration</a>) (+4500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18805" data-url="18805" class="tooltip-link link">A Sealed Letter</a>) then


>**Wolten Grafe says:** This is terrible news. It is good you did not find your grave in the catacombs. You completed your mission regardless of the odds of survival. The temple thanks you. We shall still require your service, Knight of Thunder. Events have transpired which put all agents of righteousness in danger. We cannot explain all as yet. Take this note to Freeport. You will give it to Eestyana Naestra at the Hall of Truth. Beware, now. The Shrine of Bertoxxulous now knows of your allegiance. Give me any other item.





Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+50</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+37</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+37</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18822" data-url="18822" class="tooltip-link link">A Note</a> (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/13396" data-url="13396" class="tooltip-link link">Human Head</a>) then 


>**Wolten Grafe says:** We have finally destroyed the Rat King. You have performed a great service to Qeynos. Here is a small reward. Please continue with the work of the Rainkeeper.





Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+50</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+37</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+37</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2112" data-url="2112" class="tooltip-link link">Patchwork Boots</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2106" data-url="2106" class="tooltip-link link">Patchwork Cloak</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2111" data-url="2111" class="tooltip-link link">Patchwork Pants</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2104" data-url="2104" class="tooltip-link link">Patchwork Tunic</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2108" data-url="2108" class="tooltip-link link">Patchwork Sleeves</a>) (+4900 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 5 <img src='/static/icons/item_646.png' width='14' height='14'/> 7 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/13288" data-url="13288" class="tooltip-link link">Order of Thunder</a>) then 


>**Wolten Grafe says:** Ahh. Drosco's Order of Thunder. You are truly an honorable knight. Many vile people would pay greatly for this medal. I thank you for its return. I shall honor you by rewarding you with a thunder staff. Meant for young clerics and paladins of this temple. Never let it leave your side.





Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+50</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+37</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+37</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/6357" data-url="6357" class="tooltip-link link">Thunder Staff</a> (+2000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**




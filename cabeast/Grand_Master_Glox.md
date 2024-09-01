# Grand Master Glox

[Grand Master Glox](/npc/106100) is a level 61 Iksar GM Monk that spawns in [Cabilis East](/zone/106).

Their primary faction is [Swift Tails](/faction/444).



## Dialog

if(eq.is_the_ruins_of_kunark_enabled()) then

**You say:** `hail`


>*Grand Master Glox 'shows no reaction to your greeting.'*

**You say:** `trial of agility`


>**Grand Master Glox says:** I knew you were not the whiff others claimed you to be, are you sure you are [ready] to be tested in agility?

**You say:** `ready`


if **Faction** >= Amiable then

>**Grand Master Glox says:** We shall spar then, I hope you are as prepared as you think you are.

**Grand Master Glox casts:** [Cabilis Sending](/spell/2064) on target.

elseif **Faction** >= Indifferent then

>**Grand Master Glox says:** The Swifttail Caste desires further service before I can share this with you.

else

>**Grand Master Glox says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.





else

**You say:** `hail`


>*Grand Master Glox 'shows no reaction to your greeting.'*











## Turn-Ins



local text1 = "sits, his eyes still closed, and tilts his head in confusion. He then sighs and shakes his head implying disappointment. You suddenly realize that the old master asked for the mole's collar and two star rubies.";



if( **You turn in:**   <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18204" data-url="18204" class="tooltip-link link">Guild Summons</a> ) then 

>*Grand Master Glox 'breaks his meditation and quickly grabs your forearms. You feel the raw power in his heavily callused hands. Out of nowhere, his tail sweeps forward and places a shackle upon your wrist. He then points south towards Master Bain and returns to his meditation.'*

Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+200</span>)

Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+50</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/4190" data-url="4190" class="tooltip-link link">Shackle of Dust</a> (+1000 exp)

 

elseif( **You turn in:**   <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/14788" data-url="14788" class="tooltip-link link">Illegible Note: Helm</a> ) then

>*Grand Master Glox sits whispering incoherently for a long moment before even regarding the note you dropped in front of him. The Grand Master suddenly snatches up the note from Xlixinar, removes a small charcoal marker from a belt pouch, and scrawls some intructions upon it. He drops the note immediately after finishing and resumes his meditation without a word.*

 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/18980" data-url="18980" class="tooltip-link link">Note from Glox</a> 

 

elseif( **You turn in:**   <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_643.png" alt="" /> <a
                                href="/item/14782" data-url="14782" class="tooltip-link link">a Tiny Collar</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10032" data-url="10032" class="tooltip-link link">Star Ruby</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10032" data-url="10032" class="tooltip-link link">Star Ruby</a> ) then

>*Grand Master Glox nods slightly*

 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/14783" data-url="14783" class="tooltip-link link">Glox Reference</a> (+10000 exp)

 



**This NPC *should* return incorrect items given.**













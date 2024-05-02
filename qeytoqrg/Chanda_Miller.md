# Chanda Miller
## Arrive at Waypoint Script

if(e.wp == 1) then


eq.set_anim(4052,1);

elseif(e.wp == 5) then


e.self:SetRunning(true);

elseif(e.wp == 9) then


e.self:SetRunning(false);

elseif(e.wp == 12) then


eq.set_anim(4052,1);
end

## Signals

>**Chanda Miller says:** I am f.. fff.. fff.. fine, brother. You um.. don't need to worry about me so much. I am a big girl now.

**Signaled to:**  [Baobob Miller](/npc/4055)
## Dialog

**You say:** `hail`



>**Chanda Miller says:** Um.. I do not know you. Please um.. leave me be.

**You say:** `baobob sent`



>**Chanda Miller says:** Oh.. Hello. My name is Chanda. Soandso is your name? That's a nice name. My [brother] sent you to talk to me? You must want some bear.. um.. [clothes].

**You say:** `brother`



>**Chanda Miller says:** umm.. My brother.. Um.. I mean my BROTHER.. He is the finest tanner there is. His name is Baobob and I love him very much.

**You say:** `clothes`



>**Chanda Miller says:** I um.. know how to make.. umm.. [cloaks] and [boots]. Oh yes! and belts! I love to make bear skin belts! Um.. I really like [belts]. My [brother] says I have to start charging more gold for my stuff though..

**You say:** `cloak`



if **Faction** >= Indifferent then



>**Chanda Miller says:** I.. um.. can make.. um.. a good cloak for you. You have to get me a bear skin of high quality and my brother says I should not make them unless you also give me 21 gold pieces. I used to give them away but [Baobob] got mad at me so I don't do that anymore.


else



>**Chanda Miller says:** Hmm.. I really would not feel comfortable helping you in that way. You need to prove yourself to me by aiding my friends and family in the Plains of Karana before I will help you.


**You say:** `belt`



>**Chanda Miller says:** Oh, yes, I like making belts! They are easy! All I need is a bear skin and 5 gold pieces. The bear skin doesn't have to be that great but don't bring me a ruined one. The gold was my brother's idea.. sorry.

**You say:** `boot`



>**Chanda Miller says:** I know how to make boots. Um.. I don't like them as much as belts. They are harder to make. You have to get me a medium quality bear skin and give me 15 gold pieces if you want some bear boots. They are really good, though. At least that is what Baobob tells me.

**You say:** `talym`



>**Chanda Miller says:** Talym...  umm...  He is a good source of hides...  He is wanted by the...  umm...  Protectors of the...  um... Pine.


**You say:** `mammoth`



>**Chanda Miller says:** Ooh! Umm. Mammoth! He is a big bear. Bigger than others...  He is living in Surefall Glade. Um...  Bring me his hide.  It would be worth a lot.
end

## Turn-Ins



local text = "Oh.. I see.. But um.. I still need the other thing before I can make anything for you.. sorry.";





if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13752" data-url="13752" class="tooltip-link link">High Quality Bear Skin</a>, gold = 21) then


>**Chanda Miller says:** Oh, good! I can make you a nice new cloak now. Here. Here. Oh, this.. it is a good one. Nice bear fur. Here you go!


Your faction standing with [Karana Residents](/faction/345) got better (<span class='text-success'>+2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_841.png" alt="" /> <a
                                href="/item/2902" data-url="2902" class="tooltip-link link">Bear-hide Cape</a> (+50 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13751" data-url="13751" class="tooltip-link link">Medium Quality Bear Skin</a>, gold = 15) then


>**Chanda Miller says:** Ohh good.. good! I.. um.. can make.. Oh great. Here you go. I hope you like it. I always um.. try my best. Tell your um.. friends where you got your bear things!


Your faction standing with [Karana Residents](/faction/345) got better (<span class='text-success'>+2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_525.png" alt="" /> <a
                                href="/item/2903" data-url="2903" class="tooltip-link link">Bear-hide Boots</a> (+50 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13750" data-url="13750" class="tooltip-link link">Low Quality Bear Skin</a>, gold = 5) then


>**Chanda Miller says:** Great. Oh, here, now I can make the.. um.. ok.. here. Yes.. good. I love making bear skin belts. Here you go. I hope you like it.


Your faction standing with [Karana Residents](/faction/345) got better (<span class='text-success'>+2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/2904" data-url="2904" class="tooltip-link link">Bear-hide Belt</a> (+50 exp)

 

**This NPC *should* return incorrect items given.**

# Bregun Dorey

## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds
## Timer(s)

if(e.timer == "depop") then


**Bregun Dorey despawns.**
end

## Dialog

**You say:** `hail`



>**Bregun Dorey says:** Trog trog trog trog?

**You say:** `trog`



>**Bregun Dorey says:** Ha! What are you talking about?! Strange thing you are. Wait a minute, come closer. Are you [from Norrath]?

**You say:** `from norrath`



>**Bregun Dorey says:** I thought so, your armor looks to be made from things found not here. Have you heard of [Rivervale]?

**You say:** `bixies around rivervale`



>**Bregun Dorey says:** There are Bixies! THERE ARE BIXIES! This is great. You should hunt some Bixies, and get some Bixie parts. Then you can make me some Bixie Crunchies! Ooooh, Crunchies. I want to try the Crunchies. I think you should bring me four Crunchies!

**You say:** `rivervale`



>**Bregun Dorey says:** [Good].

**You say:** `good`



>**Bregun Dorey says:** Yeah good! Trog trog trog trog! Hahaha! These Troglodytes don't know of Rivervale. They just run around the cave all day doing Troglodyte things. Hahaha! Trog trog trog. So what was I speaking of.. Oh Bixies! So, are there [bixies around Rivervale]?
end

## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_785.png" alt="" /> <a
                                href="/item/13464" data-url="13464" class="tooltip-link link">Bixie Crunchies</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_785.png" alt="" /> <a
                                href="/item/13464" data-url="13464" class="tooltip-link link">Bixie Crunchies</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_785.png" alt="" /> <a
                                href="/item/13464" data-url="13464" class="tooltip-link link">Bixie Crunchies</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_785.png" alt="" /> <a
                                href="/item/13464" data-url="13464" class="tooltip-link link">Bixie Crunchies</a>) then 


>**Bregun Dorey says:** Ah hum!


e.self:RemoveItem( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1056.png" alt="" /> <a
                                href="/item/29852" data-url="29852" class="tooltip-link link">Bixie Charm</a>);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1056.png" alt="" /> <a
                                href="/item/29852" data-url="29852" class="tooltip-link link">Bixie Charm</a> 

 


>**Bregun Dorey says:** Give this charm to Torsten as a present from his old friend.

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/29853" data-url="29853" class="tooltip-link link">Sealed Note to Bregun</a>) then 


>**Bregun Dorey says:** Hahaha! Silly Torsten. Always snooping over my shoulder. Well I have nothing to lose... Take this to him, it's directions on how to find the Journal I kept. I hid it where no one would look! Haha! Trog trog trog!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_683.png" alt="" /> <a
                                href="/item/29854" data-url="29854" class="tooltip-link link">Breguns Directions</a> 

 

**This NPC *should* return incorrect items given.**

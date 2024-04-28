# Sir Morgan







## Arrive at Waypoint Script

if(e.wp == 1) then


>**Sir Morgan says:** Hello, Wimbley, old chap!

elseif(e.wp == 8) then


>**Sir Morgan says:** Almost there...

elseif(e.wp == 9) then


>**Sir Morgan says:** Well, here we are! It is just a short jaunt through the pass ahead. Just remember to take the high road. I'm off, then. Good luck!


e.self:SetRunning(true);

elseif(e.wp == 10) then


e.self:SetRunning(false);
end

## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then 



>**Sir Morgan says:** Hail, traveler!  Might I escort you through to Highpass? The path ahead is filled with giants and many other hungry beasts. I assure you, you will be safe with me. I must admit, I am quite experienced in the ways of the warrior. Do you [wish an escort] or will you [travel alone]?


else



>**Sir Morgan says:** No person in Karana would speak with you. You had best leave before my sword finds your skull!




**You say:** `escort`



if **Faction** >= Apprehensive then 



>**Sir Morgan says:** I shall be honored to escort you to Highpass, but you shall have to wait for a spell. I make trips every few hours. I also would be grateful to any who wish to donate gold coins to the upkeep of my armor. The rains in the plains cause much rusting.


else



>**Sir Morgan says:** No person in Karana would speak with you. You had best leave before my sword finds your skull!




**You say:** `travel alone`



if **Faction** >= Apprehensive then 



>**Sir Morgan says:** Then, good luck to you! May your faith protect you. Or at the very least, guide you to a grand afterlife.


else



>**Sir Morgan says:** No person in Karana would speak with you. You had best leave before my sword finds your skull!



end

## Turn-Ins




if **Faction** >= Apprehensive and  **You turn in:** gold = 5


>**Sir Morgan says:** What a grand donation!! You must be a rich noble to be making such a donation. Here, I am but a simple warrior, but I found this lying on the highway to Highpass Hold. The lifeless corpse next to it had no more need of it.


 **You receive:** eq.ChooseRandom( [Mountain Lion Cape](/item/2041), [Bear-hide Belt](/item/2904), [Ratskin Gloves](/item/2312), [Snakeskin Mask](/item/2307), [Halfling Knife](/item/8306), [Silver Earring](/item/10006), [Highkeep Flask](/item/13944), [Large Lantern](/item/13004), [Patchwork Cloak](/item/2106), [Patchwork Boots](/item/2112), [Rusty Dagger](/item/7007), [Rusty Halberd](/item/5024), [Rusty Flail](/item/6015), [Rusty Scimitar](/item/5021), [Bronze Dagger](/item/7012), [Damask Cap](/item/1331), [Belt Pouch](/item/17002), [Drom's Champagne](/item/13829), [Hunting Bow](/item/8011), [Spell: Mircyl's Animation](/item/15295), [Spell: Shock of Blades](/item/15324), [Spell: Column of Frost](/item/15380), [Spell: Soothe](/item/15501), [Spell: Glimpse](/item/15051), [Bloodstone](/item/10019)) 






**This NPC *should* return incorrect items given.**


# Guard Shilster




## Arrive at Waypoint Script

if(e.wp == 2) then


>*Guard Shilster stumbles and says, 'Hey fools.  Blackburrow stout for sale five gold.  Load up now 'cause it's going fast!  Just make sure you enjoy it in privacy or you might get arrested, ha haaaa!'*

elseif(e.wp == 3) then


>*Guard Shilster burps loudly and says, 'Your loss.  Back to the bridge I go to keep us safe from the enemy or whatever it is I'm supposed to be doing out there.'*
end

## Dialog

**You say:** `hail`



>**Guard Shilster says:** Hey, hey! I have some Blackburrow Stout for sale. Just hand over five gold and I'll give you a bottle of it. Don't get caught though because it is considered [contraband]. [Antonius] don't like it being smuggled and all that but what does he know, anyway?

**You say:** `contraband`



>**Guard Shilster says:** Well it's brewed by gnolls, ya know. Don't know exactly why it's considered contraband but I think it's because they use the money they get from selling the stout to buy arms. I dunno. I buy low and sell high. Blackburrow Stout is good for you though! It does wonders for me! Now buy some already before someone hears us talking.

**You say:** `antonius`



>**Guard Shilster says:** That man is as clueless as a froglok tad swimming in a keg of dwarven ale! He has no idea what is going on around him. He won't be around for much longer I wager.
end

## Turn-Ins




if( **You turn in:** gold = 5) then


>**Guard Shilster says:** There you go, sport. If you get caught with that, you didn't get it from me!





* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Kane Bayle](/faction/273) (1)




* __Faction:__ [Circle of Unseen Hands](/faction/223) (1)


* __Faction:__ [Bloodsabers](/faction/221) (1)


 **You receive:**  [Black Burrow Stout](/item/13107) 

**This NPC *should* return incorrect items given.**



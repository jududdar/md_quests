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





Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Kane Bayle](/faction/273) got better (<span class='text-success'>+1</span>)




Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+1</span>)


Your faction standing with [Bloodsabers](/faction/221) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_827.png" alt="" /> <a
                                href="/item/13107" data-url="13107" class="tooltip-link link">Black Burrow Stout</a> 

 

**This NPC *should* return incorrect items given.**



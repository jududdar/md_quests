# Drekon Vebnebber



[Drekon Vebnebber](/npc/55116) is a level 20 Gnome Shopkeeper that spawns in [Ak'Anon](/zone/55).



## Dialog

**You say:** `hail`



>**Drekon Vebnebber says:** Hello, Soandso. It is grand to make your acquaintance. I am the in-house merchant-slash-file clerk. I have goods to offer and I handle all the Gemchopper paperwork. Thrilling, don't you think?

**You say:** `red 5`



>**Drekon Vebnebber says:** Red 5 is rumored to be a haywire clockwork. They say he pieced himself back together and lives in the scrapyard. If he IS there, you must hunt him down and take his blackbox to Manik Compolten. Be careful, if Red 5 rebuilt himself, he may have rebuilt minions as well.

**You say:** `blackbox`



>**Drekon Vebnebber says:** If you have a clockwork blackbox which is still intact, take it to [Manik Compolten].  All clockwork matters go through him.

**You say:** `manik compolten`



if **Faction** >= Indifferent then 



>**Drekon Vebnebber says:** Manik is a trainer within this guild. The clockworks are his responsibility. Speak with him - I am sure he is here somewhere.


else



>**Drekon Vebnebber says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `meldrath`



>**Drekon Vebnebber says:** Meldrath is the mad gnome.  He used to be a member of the Eldritch Collective.  Some say he lost his mind while he was working on a formula he obtained from other worlds.  He used to lead the cult called the [Asylum of the Mad].

**You say:** `asylum`



>**Drekon Vebnebber says:** The Asylum of the Mad was formed by the mad gnome, Meldrath. Under his direction, they were trying to build some giant mechanical titan.  We recently sent all of our clockworks into the Steamfont Mountains to destroy their evil cult.
end



## Turn-Ins





if ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18837" data-url="18837" class="tooltip-link link">A Daily Log</a>) then


>**Drekon Vebnebber says:** Why, thank you. Hey!! This log indicates some messy business is going on at the scrapyard. Something happened to a group of gnomes. They never came out!! Go check out the scrapyard! I believe the rumors of [Red 5] are true.





Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+5</span>)


Your faction standing with [Merchants of Ak`Anon](/faction/288) got better (<span class='text-success'>+1</span>)


Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+1</span>)


Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Clan Grikbar](/faction/1604) got worse (<span class='text-danger'>-1</span>)


**Experience:** Awards 11% experience at level 1.




elseif ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18838" data-url="18838" class="tooltip-link link">A Daily Log</a>) then


>**Drekon Vebnebber says:** Oh my! It seems two of the obsolete duster models were not fully shut down. You must find them. They could be anywhere in Ak'Anon! After you destroy them, take their scraps to Sanfyrd Montop. He is the operator of the scrapyard.


**Spawn NPC:**  [Duster X](/npc/55001) at (**y:** 1504, **x:** -300)


Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+5</span>)


Your faction standing with [Merchants of Ak`Anon](/faction/288) got better (<span class='text-success'>+1</span>)


Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+1</span>)


Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Clan Grikbar](/faction/1604) got worse (<span class='text-danger'>-1</span>)


**Experience:** Awards 11% experience at level 1.




**This NPC *should* return incorrect items given.**

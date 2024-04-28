# Bronin Higginsbot
## Dialog

**You say:** `hail`



>**Bronin Higginsbot says:** Hello. It is dangerous out in the woods. You should go to Rivervale. It's at theof the path. You will find good times there. Travel safely, my friend!

**You say:** `shard`



>**Bronin Higginsbot says:** Searching for that blasted emerald shard, are you? That thing has done nothing but bring me bad luck!! I would gladly give it to you if you would do a [small favor] for me.

**You say:** `small favor`



if( **Faction is** > Indifferent) then



>**Bronin Higginsbot says:** I have been tracked here by a bounty hunter named Slaythe. I have heard reports of his presence beyond the Great Wall. Please seek him out and bring me some body part of his as proof of his passing. Do this and the emerald shard is yours.



if(**spawned NPC:**  [Slaythe](/npc/33146) == false) then




 **Spawn NPC:**  [Slaythe](/npc/33146) at (**y:** 664.00, **x:** 893.00)




elseif( **Faction is** > Apprehensive) then



>**Bronin Higginsbot says:** When the blood of many Runnyeye goblins has covered your blade, then I shall find you worthy to speak of such matters.


else



>**Bronin Higginsbot says:** You are no ally of the Rivervale Deeppockets!! Leave at once!!


**You say:** `second piece of the gem`



if( **Faction is** > Indifferent) then



>**Bronin Higginsbot says:** The second emerald shard was hidden in the forest near Kelethin. I heard one of the local guilds found it and now call it the Gem of Tunare. You will have to ask around in Kelethin about it. Good luck.


elseif( **Faction is** > Apprehensive) then



>**Bronin Higginsbot says:** When the blood of many Runnyeye goblins has covered your blade, then I shall find you worthy to speak of such matters.


else



>**Bronin Higginsbot says:** You are no ally of the Rivervale Deeppockets!! Leave at once!!

end

## Turn-Ins



if **You turn in:** [Bloody Shank](/item/13110)


>**Bronin Higginsbot says:** AHH!! You have been sent by the Highkeep Guards!! You will never take Bronin Higginsbot alive!!


* __Faction:__ [Deeppockets](/faction/241) (-50)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-2)


* __Faction:__ [Merchants of Rivervale](/faction/292) (2)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-2)


* __Faction:__ [Carson McCabe](/faction/329) (-2)


e.self:AddItem(13111,0);


**Bronin Higginsbot attacks you.**

elseif(( **Faction is** > Indifferent) and  **You turn in:** [A Froglok Leg](/item/12192)


>**Bronin Higginsbot says:** So I see you have defeated Slaythe. I shall sleep much better now that he is gone. I placed the emerald shard in one of the Highkeep strongboxes in Highpass. Give the Bank Clerk this key. There is a [second piece of the gem] which I hid near Kelethin. You will need it to complete the gem. I hope it brings you better luck than I.


* __Faction:__ [Deeppockets](/faction/241) (10)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (1)


* __Faction:__ [Merchants of Rivervale](/faction/292) (-1)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (1)


* __Faction:__ [Carson McCabe](/faction/329) (1)


 **You receive:**  [H.K. 106](/item/12193) (+500 exp)

**This NPC *should* return incorrect items given.**






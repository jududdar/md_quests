# Plagus Ladeson



[Plagus Ladeson](/npc/9112) is a level 61 Human GM Warrior that spawns in [West Freeport](/zone/9).



## Dialog

local fac = e.other:GetFaction(e.self);


**You say:** `hail`



>**Plagus Ladeson says:** Greetings Soandso, and welcome to the Bunker. Are you a [new warrior] or [veteran]?

**You say:** `Milea`



>**Plagus Ladeson says:** Milea Clothspinner. She was my one true love. She, too, is a Steel Warrior. When she left Qeynos to find adventure, my heart left also. I never saw her again, but I decided to transfer my skills to Freeport. It is probably best that I did not find her. She was in love with adventure. sigh> The women I am attracted to are always in love with another. Just like [Toala].

**You say:** `Toala`



>**Plagus Ladeson says:** Toala is supreme when it comes to the blade, but in the art of passion she chooses to leans toward Cain Darkmoore. I do not get it. She is a very beautiful and strong-hearted warrior. Why Cain does not like her is a mystery to me. Why does she waste her time when she could have me? After all, we men of Qeynos are known as the most romantic in all of Norrath.

**You say:** `in east karana`



>**Plagus Ladeson says:** You have seen Milea Clothspinner!! This is great news. I wish I could travel to see her, but Cain will not allow me to do so at this time. You must take her a note for me. Here, take this to her. As a master in this order, I command you to do so immediately. Go!!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18934" data-url="18934" class="tooltip-link link">Sealed Note</a>

elseif(fac < 5) then


**You say:** `new warrior`




>**Plagus Ladeson says:** Good to know you chose the Bunker to train you. It is the home of The Steel Warriors. We find our inner strengths grow through battles and deeds to further our growth. Do you [seek deeds] or [crave battle]?


**You say:** `seek deeds`




>**Plagus Ladeson says:** It may not be a fray, but who ever said we Steel Warriors are nothing but brawn?  Recently, there has been reports of frequent visits by dark elves to the Hog Caller's Inn, here in Freeport. Go speak with Lady Shae. Tell her, the [Steel Warriors sent you]. We cannot rely on the Freeport Militia to look into such matters. They are probably involved. Bring me any clues you find.


**You say:** `crave battle`




>**Plagus Ladeson says:** Aye!!  That is good.  Ask Cain Darkmoore about Clan Deathfist.  Also, when striking underhand, plant your feet at shoulder width and push with your legs on contact.  It does wonders and keeps your back and shoulders from aching.




**You say:** `veteran`




>**Plagus Ladeson says:** I apologize for not knowing. I am new to the Bunker. I was a trainer at the Hall of Steel in Qeynos before this.  I left Qeynos in search of [Milea] and instead found myself joining the bunker's weaponmasters.


elseif(fac == 5) then


**You say:** `new warrior`




>**Plagus Ladeson says:** The Steel Warriors have no cause to dislike you, but you have yet to prove your worth to this guild.


elseif(fac > 5) then


**You say:** `new warrior`




>**Plagus Ladeson says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!

end



## Turn-Ins



local fac = e.other:GetFaction(e.self);


if(fac < 5 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18814" data-url="18814" class="tooltip-link link">A Sealed Letter</a>) then 



>**Plagus Ladeson says:** Oh my! Opal? She is providing these agents of Neriak with information regarding the Acedemy's secrets. I can not tell Cain about this. He will be furious. Show this to Toala. She will know what to do.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18814" data-url="18814" class="tooltip-link link">A Sealed Letter</a> 

 

elseif(fac == 5 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18814" data-url="18814" class="tooltip-link link">A Sealed Letter</a>) then



>**Plagus Ladeson says:** The Steel Warriors have no cause to dislike you, but you have yet to prove your worth to this guild.

elseif(fac > 5 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18814" data-url="18814" class="tooltip-link link">A Sealed Letter</a>) then



>**Plagus Ladeson says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!

**This NPC *should* return incorrect items given.**
;

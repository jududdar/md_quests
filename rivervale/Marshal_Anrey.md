# Marshal Anrey



[Marshal Anrey](/npc/19055) is a level 61 Halfling GM Warrior that spawns in [Rivervale](/zone/19).





## Dialog

**You say:** `hail`



>**Marshal Anrey says:** Stand at attention!! You don't look fit enough to toe-wrestle my grandma!! You cannot be in my squad!! Are you [petitioning] or are you a [visitor]?

**You say:** `visitor`



>**Marshal Anrey says:** Well, why didn't you say so?! Forgive me for hollering. Allow me to introduce myself. I am Marshal Anrey Leadladle, commander of the [Leatherfoot Raiders].

**You say:** `leatherfoot raider`



>**Marshal Anrey says:** You must be a visitor. The Leatherfoot Raiders are the elite force of the Guardians of the Vale. I command them. It is good to meet an outsider.



**You say:** `petitioning`



if **Faction** >= Amiable +100 then 
(200)




>**Marshal Anrey says:** So you want to be a [Leatherfoot Raider]? What kind of joke is this? Look at you! You're a mess! Where are you [from]?


elseif **Faction** >= Indifferent then



>**Marshal Anrey says:** You are in good standing with the Guardians of the Vale. Continue with your good work and then we may speak.


else



**Marshal Anrey says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `from rivervale`




if **Faction** >= Amiable +100 then 
(200)




>**Marshal Anrey says:** So you're from Rivervale?!! You must be some kind of freak. No halfling from Rivervale would look, smell and act anything like you. Well, freak, if you think you're stout enough to be a Leatherfoot Raider, you prove it!! You travel the lands and return to me a polar bear skin, a grizzly bear skin, a shark skin and an alligator skin. Then maybe, just maybe, I will let you wear the cap of a Leatherfoot Raider.




elseif **Faction** >= Indifferent then



>**Marshal Anrey says:** You are in good standing with the Guardians of the Vale. Continue with your good work and then we may speak.


else



**Marshal Anrey says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `from qeynos`




>**Marshal Anrey says:** What!  The only things from there are gnolls and trolls!  Which one are you?!  You kind of look like a troll, but you smell like a gnoll!  Get out of my sight or you will be cleaning the latrine with a toothbrush!
end



## Turn-Ins




if **Faction** >= Amiable +100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_835.png" alt="" /> <a
                                href="/item/13761" data-url="13761" class="tooltip-link link">Polar Bear Skin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13756" data-url="13756" class="tooltip-link link">Thick Grizzly Bear Skin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_814.png" alt="" /> <a
                                href="/item/13075" data-url="13075" class="tooltip-link link">Shark Skin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_813.png" alt="" /> <a
                                href="/item/13749" data-url="13749" class="tooltip-link link">Alligator Skin</a>) then 


>**Marshal Anrey says:** So I see the young troll has become a young warrior.  You have stepped up to the challenge of the Leatherfoot Raiders, you may wear the petitioner's skullcap, but to receive the true cap of the raiders, bring me the dirk of a fallen Neriak dragoon and the cap I have given you.  Only then can I be sure that you can truly be one of the few and bold, the Leatherfoot Raiders.





Your faction standing with [Guardians of the Vale](/faction/263) got better (<span class='text-success'>+25</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+3</span>)


Your faction standing with [Storm Reapers](/faction/355) got better (<span class='text-success'>+2</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+2</span>)


Your faction standing with [Dreadguard Outer](/faction/334) got worse (<span class='text-danger'>-3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/13941" data-url="13941" class="tooltip-link link">Leatherfoot Skullcap</a> (+1000 exp)

**You receive coin:** 1 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable +100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/13941" data-url="13941" class="tooltip-link link">Leatherfoot Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_574.png" alt="" /> <a
                                href="/item/13942" data-url="13942" class="tooltip-link link">Dragoon Dirk</a>) then 


>**Marshal Anrey says:** Congratulations, my young deputy! Welcome to the brotherhood of the Leatherfoot Raiders. You have earned your skullcap. Wear it with pride. You are now one of the elite. Remember our motto, 'Those who risk, prevail'.





Your faction standing with [Guardians of the Vale](/faction/263) got better (<span class='text-success'>+50</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+7</span>)


Your faction standing with [Storm Reapers](/faction/355) got better (<span class='text-success'>+5</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+5</span>)


Your faction standing with [Dreadguard Outer](/faction/334) got worse (<span class='text-danger'>-7</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/12259" data-url="12259" class="tooltip-link link">Leatherfoot Raider Skullcap</a> (+5000 exp)

**You receive coin:** 1 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**



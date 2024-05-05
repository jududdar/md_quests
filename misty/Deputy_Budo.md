# Deputy Budo



[Deputy Budo](/npc/33068) is a level 39 Halfling Warrior that spawns in [Misty Thicket](/zone/33).



## Dialog

**You say:** `hail`



>**Deputy Budo says:** Hail, Soandso. I am Deputy Budo Bullnose, the squad leader of the Great Wall Patrol. Be very careful in the lands beyond the wall. They are filled with dangerous beasts, as well as [Clan Runnyeye].

**You say:** `clan Runnyeye`



>**Deputy Budo says:** Beyond this wall lies Runnyeye, the lair of the goblins of Clan Runnyeye. They have been a nuisance to Rivervale for quite some time. If you wish to join the fight, go to Rivervale and ask Sheriff Roglio about Clan Runnyeye.

**You say:** `I am reporting for duty`



if **Faction** >= Amiable then



>**Deputy Budo says:** Stand tall then, Deputy Soandso. Your orders are to keep the creatures from venturing into the community of Rivervale and to kill many goblins. Check the goblin bodies, if you should find unbroken warrior beads on them, take them to Sheriff Roglio Bruth and should you be lucky enough to find a bizarre grappling device, you are to take it to Marshal Ghobber Truppack immediately! One more thing - should you defeat any orcs in battle, bring me their leather belts and I shall reward you for the great victory. May the power of Underfoot be with you!


elseif( **Faction is** == Indifferent) then



>**Deputy Budo says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Deputy Budo says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




end



## Turn-Ins




local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/13916" data-url="13916" class="tooltip-link link">Deathfist Slashed Belt</a>}

if(count > 0) then


repeat



>**Deputy Budo says:** Grand work. Deputy Soandso! You will become a full-fledged deputy in no time. You should check in with Marshal Ghobber from time to time to see if you have earned your squad ring. Just go up to him and ask. 'Am I one with the Wall?' He will know. but you must first show your bravery in many battles against the goblins.



Your faction standing with [Guardians of the Vale](/faction/263) got better (<span class='text-success'>+5</span>)



Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+1</span>)



Your faction standing with [Storm Reapers](/faction/355) got better (<span class='text-success'>+1</span>)



Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+1</span>)



Your faction standing with [Dreadguard Outer](/faction/334) got worse (<span class='text-danger'>-1</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_717.png" alt="" /> <a
                                href="/item/13024" data-url="13024" class="tooltip-link link">Tagglefoot Tingle Drink</a> (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 9 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**


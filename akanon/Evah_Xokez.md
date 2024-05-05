# Evah Xokez



[Evah Xokez](/npc/55124) is a level 61 Gnome GM Cleric that spawns in [Ak'Anon](/zone/55).





## Dialog

**You say:** `hail`



if **Faction** >= Amiable then 



>**Evah Xokez says:** Be wary, Soandso, there are unseen powers within these mines that can destroy the strongest warriors or the wisest seers. Do you find the rust that corrodes the mechanisms around you and the decaying forms that wander [these tunnels pleasing]?


elseif( **Faction is** == Indifferent) then



>**Evah Xokez says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Evah Xokez says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `pleasing`



if **Faction** >= Indifferent then 



>**Evah Xokez says:** Then perhaps you share the vision of we who have made these mines our home. We are the Dark Reflection and our perceptions have been refined to allow us to see the poisons and disease coursing through every creature's veins and the decay afflicting all forms of matter in Norrath. I can teach you to harness the powers of our divine benefactor if you are [willing to learn] through service to the Dark Reflection.


else



**Evah Xokez says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `willing.* learn`



if **Faction** >= Indifferent then 



>**Evah Xokez says:** Then your first lesson shall be the fulfillment of spreading infection and disease. Some of the best carriers of infectious diseases are rodents. Take this vial containing a slow and painful infection and give it to one of the pregnant giant rodents that can be found outside in the Steamfont Mountains. This way you can spread the disease to not only those creatures which cross the mother's path but also to those who cross the paths of her future offspring. Bring me the empty vial when the task has been completed.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/10262" data-url="10262" class="tooltip-link link">Vial of Infectious Disease</a>



else



**Evah Xokez says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `components`



if **Faction** >= Indifferent then 



>**Evah Xokez says:** The recipe we use to make the plague rat disease is fairly simple. We could easily extract the fluids from the infected rat livers but that would be counterproductive to our cause since it would require the deaths of our rodent carriers. Instead, I need you to collect two parts diseased bone marrow, one sprig of wormwood and one part gnomish spirits to be used as a medium. When you have combined all the components in the container I have provided, return it to me so that we may continue to spread the disease!


else



**Evah Xokez says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18769" data-url="18769" class="tooltip-link link">Stained Note</a>) then  


>**Evah Xokez says:** Join us in fulfilling teh will of Bertoxxulous. You can train with us here, in the shadows of the Abbey. Wear this tunic to help conceal your true identity.


Your faction standing with [Dark Reflection](/faction/238) got better (<span class='text-success'>+100</span>)



Your faction standing with [Eldritch Collective](/faction/245) got worse (<span class='text-danger'>-10</span>)



Your faction standing with [Gem Choppers](/faction/255) got worse (<span class='text-danger'>-10</span>)


Your faction standing with [Deepmuses](/faction/240) got worse (<span class='text-danger'>-10</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13518" data-url="13518" class="tooltip-link link">Tin Patched Tunic*</a> (+20 exp)

 


elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/10263" data-url="10263" class="tooltip-link link">Empty Infectious Vial</a>) then 


>**Evah Xokez says:** I hope you enjoyed the thrill of your first lesson and the awakening of your vision. Now you must prove your utility to our society. Take this airtight container and gather the [components] for another dose of the plague rat disease.


Your faction standing with [Dark Reflection](/faction/238) got better (<span class='text-success'>+50</span>)



Your faction standing with [Eldritch Collective](/faction/245) got worse (<span class='text-danger'>-5</span>)



Your faction standing with [Gem Choppers](/faction/255) got worse (<span class='text-danger'>-5</span>)



Your faction standing with [Deepmuses](/faction/240) got worse (<span class='text-danger'>-5</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/17357" data-url="17357" class="tooltip-link link">Airtight Metal Box</a> (+150 exp)

 


elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/10266" data-url="10266" class="tooltip-link link">Container of Infectious Reagents</a>) then


>**Evah Xokez says:** It appears that you truly seek to expand your vision into the Dark Reflection, Soandso. I grant you the Initiate Symbol of Bertoxxulous!


Your faction standing with [Dark Reflection](/faction/238) got better (<span class='text-success'>+25</span>)



Your faction standing with [Eldritch Collective](/faction/245) got worse (<span class='text-danger'>-2</span>)



Your faction standing with [Gem Choppers](/faction/255) got worse (<span class='text-danger'>-2</span>)



Your faction standing with [Deepmuses](/faction/240) got worse (<span class='text-danger'>-2</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/1390" data-url="1390" class="tooltip-link link">Initiate Symbol of Bertoxxulous</a> (+200 exp)

 


**This NPC *should* return incorrect items given.**

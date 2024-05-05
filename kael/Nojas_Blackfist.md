# Nojas Blackfist



[Nojas Blackfist](/npc/113282) is a level 49 Giant Shaman that spawns in [Kael Drakkel](/zone/113).



## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Nojas Blackfist says:** What brings you to the hall of the frost giants, little one? Have you come to serve our lord and master? Or are you simply a scout for a raiding party? I warn you, do not make war on my kin. I will twist the elements to my will and destroy you if that is your intent.


else



**Nojas Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `serve`



if **Faction** >= Amiable then



>**Nojas Blackfist says:** You could best serve the masters by serving me. The more time I have to tend to my research the better. I have several minor tasks which you could easily handle...


elseif **Faction** >= Indifferent then



>**Nojas Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Nojas Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `minor task`



if **Faction** >= Amiable then



>**Nojas Blackfist says:** In the wreched jungle to the west there lives a race of faries protected by Tunare and her other minions. These abominations are called the Sifaye. I belive that the strength of the Wakening lands is linked not only to Tunare herself, but her connection with these foul beasts. Bring me the wings of one of their so called knights and the heads of three commoners and I will reward you for such busy work.


elseif **Faction** >= Indifferent then



>**Nojas Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Nojas Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `elements`



if **Faction** >= Amiable then



>**Nojas Blackfist says:** The elements of  nature, of course!  Over the years, I have learned that I can bend the powers of nature and the spirits of those long passed to my will and achieve many things.


elseif **Faction** >= Indifferent then



>**Nojas Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Nojas Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_910.png" alt="" /> <a
                                href="/item/25112" data-url="25112" class="tooltip-link link">Wings of a Sifaye Knight</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_744.png" alt="" /> <a
                                href="/item/25113" data-url="25113" class="tooltip-link link">Sifaye Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_744.png" alt="" /> <a
                                href="/item/25113" data-url="25113" class="tooltip-link link">Sifaye Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_744.png" alt="" /> <a
                                href="/item/25113" data-url="25113" class="tooltip-link link">Sifaye Head</a>) then


>**Nojas Blackfist says:** Congratulations, slayer of tiny beasts. Take this living tattoe for your troubles.  If you wish to continue to serve me, find a way to capture more noble sifaye... alive.





Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+10</span>)


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+2</span>)


Your faction standing with [Coldain](/faction/406) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/25056" data-url="25056" class="tooltip-link link">Silver Dragon Tattoo</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**

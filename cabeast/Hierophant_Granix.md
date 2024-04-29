# Hierophant Granix



## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Hierophant Granix says:** Leave me in peace Soandso, I have little desire for company now. The Faceless sends visions to me that may hold the fate of our race in sway.


else



**Hierophant Granix says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




**You say:** `visions`



if **Faction** >= Indifferent then



>**Hierophant Granix says:** The spirits tell me of strange happenings around the ancient city of Charasis. None of the mystics that have been sent to investigate have returned. Something is surely happening in the ancient tombs of that city. I pray to our lord for some way to calm the tortured spirits of our fallen brothers that haunt the Howling Stones.


else



**Hierophant Granix says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




**You say:** `dreams cloud your mind`



if **Faction** >= Indifferent then



>**Hierophant Granix says:** I see much darkness...darkness and death. A void of life...the cold grip of death. An Ancient pact...with forces too terrible to describe...A great Leader...a fall, and a second coming. I see...a symbol of...an ancient city...Kaesora. I would begin there young Mystic. The spirits of that fallen city may hold a key to our future.


else



**Hierophant Granix says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.



end

## Turn-Ins







if **Faction** >= Amiable and  **You turn in:** [A Dusty Iksar Skull](/item/30984))  then


>*Hierophant Granix peers at the skull intently. 'There is strange magic in this skull Soandso, whatever necromancer animated this skeleton was a powerful warlock indeed. I sense the power of several ancients in this relic. Take this skull to Oracle Qulin in the field of bone, he may be able to perform the ritual which will free this ancient's spirit from the mortal realm.'*


 **You receive:**  [A Dusty Iksar Skull](/item/30984) 





elseif **Faction** >= Amiable and  **You turn in:** [Note to Granix](/item/30986)) then


>**Hierophant Granix says:** It is as I feared, the mark of the warlock has surely driven these ancient spirits mad. We can not allow these spirits to roam free in our world Soandso. Take this case and place the glowing skulls of other ancients inside of it. Return it to me with your Cudgel of the Heirophant so that we may remove these cursed spirits from our world forcefully.


 **You receive:**  [Ornate Skull Case](/item/17134) 





elseif **Faction** >= Amiable and  **You turn in:** [A Filled Ornate Skull Case](/item/30988), [Iron Cudgel of the Hierophant](/item/5146)) then


>**Hierophant Granix says:** You have done well Soandso. Perhaps you can help clear these troubling dreams from my tired aging mind. Commune with the spirits of our Ancestors and learn from them. Never forget that the ultimate power comes from knowledge. The ancients are privy to much knowledge that mortals will never see. Should you be granted enlightenment from our ancestors, share your knowledge with me so that we may use this knowledge for the benefit of our brethren. I will continue to study the [dreams] that [cloud] my mind.


 **You receive:**  [SkyIron Cudgel of the Arisen](/item/5148) 


**This NPC *should* return incorrect items given.**







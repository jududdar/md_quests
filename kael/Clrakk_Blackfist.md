# Clrakk Blackfist


## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>*Clrakk Blackfist looks down at you. 'What is it you want, Soandso? Why do you speak to the great Knight Clrakk Blackfist?*


else



**Clrakk Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `bring strife`



if **Faction** >= Amiable then



>**Clrakk Blackfist says:** The Coldain have grown complacent. The defenses of their city are built to keep my kind and dragonkind at bay. However, their defenses against the smaller races such as yourself are not nearly as sophisticated. I wish to kill many Coldain, but now is not the time for that. There is a particular Coldain whose death will strike fear into the hearts of many. His name is Deaen Greyforge, a Coldain knight. He is both feared and respected by his kind. If you can destroy him, it will send a message to the Coldain that they are not safe from the wrath of the giants. Kill him and chop his body into bits. Bring me a few pieces as proof that the fool is dead.


elseif **Faction** >= Indifferent then



>**Clrakk Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Clrakk Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `knight`



if **Faction** >= Amiable then



>**Clrakk Blackfist says:** Yes, I am a knight.  One who walks a dark path of blood and hatred.  In your realms, one such as myself is called a shadowknight.


elseif **Faction** >= Indifferent then



>**Clrakk Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Clrakk Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_744.png" alt="" /> <a
                                href="/item/25115" data-url="25115" class="tooltip-link link">Hand of Deaen Greyforge</a>) then 


>**Clrakk Blackfist says:** You truly are a bringer of strife, Soandso. Take this. I hope it will assist you. Use it in our war against the Coldain scum.





Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+10</span>)


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+2</span>)


Your faction standing with [Coldain](/faction/406) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/25054" data-url="25054" class="tooltip-link link">Mask of Malediction</a> (+1000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_919.png" alt="" /> <a
                                href="/item/25114" data-url="25114" class="tooltip-link link">Legs of Deaen Greyforge</a>) then 


>**Clrakk Blackfist says:** You truly are a bringer of strife, Soandso. Take this. I hope it will assist you. Use it in our war against the Coldain scum.





Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+10</span>)


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+2</span>)


Your faction standing with [Coldain](/faction/406) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/25051" data-url="25051" class="tooltip-link link">Dark Spear of Venom</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**

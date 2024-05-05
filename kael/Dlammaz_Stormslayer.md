# Dlammaz Stormslayer



[Dlammaz Stormslayer](/npc/113246) is a level 62 Giant Warrior that spawns in [Kael Drakkel](/zone/113).





## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Dlammaz Stormslayer says:** Welcome to the castle of King Tormax. It is quite an accomplishment for one of your kind to have lived this long in the service of our great King Tormax. You must be powerful indeed. My power is like a storm - I may rage and destroy my foes with great fury.


else



**Dlammaz Stormslayer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `foes`



if **Faction** >= Amiable +300 then



>**Dlammaz Stormslayer says:** The dragons are the greatest threat to Kael Drakkel. For some reason they believe that this land we inhabit is holy and should not be tread upon. I cannot count the number of wurms I have beaten back from the gates of Kael Drakkel in the past. We giants will live on, though, for each year their numbers thin and ours only grow. With the help of mercenaries such as yourself we may be able to eradicate them from the face of Velious.


elseif **Faction** >= Indifferent then



>**Dlammaz Stormslayer says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Dlammaz Stormslayer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `eradicate`



if **Faction** >= Amiable +300 then



>**Dlammaz Stormslayer says:** I dream of the day when the only dragons in Velious are the ones whose skins line my boots. Some day my dream will come true. Until the day I can gather a force powerful enough to assault their homes, I will slay whatever foul beasts tread near Kael Drakkel.


elseif **Faction** >= Indifferent then



>**Dlammaz Stormslayer says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Dlammaz Stormslayer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `assault`



if **Faction** >= Amiable +300 then



>**Dlammaz Stormslayer says:** That is an aspiration of King Tormax. One day, it may be possible for us to do so. Encountering so many dragons at once may very well be suicide though. Enough of my banter about dragons. What is it that brings you to Dragon Death Keep? Do you seek more challenging tasks?


elseif **Faction** >= Indifferent then



>**Dlammaz Stormslayer says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Dlammaz Stormslayer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `challenging tasks`



if **Faction** >= Amiable +300 then



>**Dlammaz Stormslayer says:** If you are as mighty as I believe you to be, travel out from this city and fight off the draconian menace. For the head of an elder dragon you will be handsomely rewarded.


elseif **Faction** >= Indifferent then



>**Dlammaz Stormslayer says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Dlammaz Stormslayer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `reward`



if **Faction** >= Amiable +300 then



>*Dlammaz Stormslayer pats the huge axe at his side and drapes his shimmering cloak over his shoulders.*


elseif **Faction** >= Indifferent then



>**Dlammaz Stormslayer says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Dlammaz Stormslayer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `axe`



if **Faction** >= Amiable +300 then



>**Dlammaz Stormslayer says:** My axe is named Frostbringer. It was given to me by the great King Tormax for my service to him. Serving the king can be quite advantageous.


elseif **Faction** >= Indifferent then



>**Dlammaz Stormslayer says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Dlammaz Stormslayer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `cloak`



if **Faction** >= Amiable +300 then



>**Dlammaz Stormslayer says:** The cloak of the Maelstrom allows me to rage like a great storm. It is but a simple possession - the head of an elder dragon would be worth far more to my kind.


elseif **Faction** >= Indifferent then



>**Dlammaz Stormslayer says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Dlammaz Stormslayer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins





if **Faction** >= Amiable +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1231.png" alt="" /> <a
                                href="/item/25119" data-url="25119" class="tooltip-link link">Great Dragon's Head</a>) then


>**Dlammaz Stormslayer says:** The bards will sing of your greatness, Soandso. Rage on like the Maelstrom when you wear this cloak. You have done a great service for the city of Kael Drakkel, and we Kromzek do not soon forget great deeds.


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+25</span>)


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+25</span>)


Your faction standing with [Yelinak](/faction/436) got worse (<span class='text-danger'>-12</span>)


Your faction standing with [Dain Frostreaver IV](/faction/405) got worse (<span class='text-danger'>-12</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_659.png" alt="" /> <a
                                href="/item/25023" data-url="25023" class="tooltip-link link">Cloak of the Maelstrom</a> (+5000 exp)

 

elseif **Faction** >= Amiable +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1231.png" alt="" /> <a
                                href="/item/25118" data-url="25118" class="tooltip-link link">Greater Dragon's Head</a>) then


>**Dlammaz Stormslayer says:** We shall hang this head from the halls of Dragondeath Keep and sing your praises, Soandso. Take my axe as a reward for your great deeds. You are a true hero for Kael Drakkel!


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+25</span>)


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+25</span>)


Your faction standing with [Yelinak](/faction/436) got worse (<span class='text-danger'>-12</span>)


Your faction standing with [Dain Frostreaver IV](/faction/405) got worse (<span class='text-danger'>-12</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_902.png" alt="" /> <a
                                href="/item/25022" data-url="25022" class="tooltip-link link">Frostbringer</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**

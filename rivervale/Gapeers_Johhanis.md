# Gapeers Johhanis









## Dialog 

**You say:** `Hail`



>*Gapeers Johhanis jumps at your voice, he's obviously very focused on a set of beakers on the table. They seem to be holding samples of rotted flesh. Gapeers says, 'Oh my heart! You could have stopped it! Please be careful when entering these chambers. It would be unfortunate if I had dropped and broken these [specimens].*

**You say:** `what specimens`



if **Faction** >= Indifferent +50 then 



>*Gapeers Johhanis turns to explain the specimens when he accidentally knocks over the beakers. He sucks in a short breath as the beakers crash to the ground, ruining the samples. As Gapeers's skin loses color he says, 'OH NO!! No, not my specimens!! Now what am I to do?! I needed those badly! You did this! You [owe] me now!*


elseif **Faction** >= Indifferent then



>**Gapeers Johhanis says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Gapeers Johhanis says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



**You say:** `owe`



if **Faction** >= Indifferent +50 then



>**Gapeers Johhanis says:** You bet you do! You big clumsy " .. e.other:Race() .. "! These were the remains of unfortunates who were drowned. Not only were they drowned but their bodies clung to life and refused to settle. Products of the horrendous curse of unlife. I'll need you to find three [special samples] of drowned and cursed flesh.


elseif **Faction** >= Indifferent then



>**Gapeers Johhanis says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Gapeers Johhanis says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



**You say:** `special sample`



if **Faction** >= Indifferent +50 then



>*Gapeers Johhanis 's eyes widen as he realizes you actually might intend to help him. His voice becomes raspy with desperation as he says, 'Oh! Wonderful....uuhhmmm.... well ....You'll need to find undead creatures found in the waters of three different climates. One from a tropical ocean. One from the muddy and slow moving river of a jungle. And one from the stagnate and polluted water of a city's sewer, Freeport would be ideal. Will you really [do this for me]?*


elseif **Faction** >= Indifferent then



>**Gapeers Johhanis says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Gapeers Johhanis says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



**You say:** `do.* for you`



if **Faction** >= Indifferent +50 then



e.self:DoAnim(50);



>**Gapeers Johhanis says:** Oh thank goodness! Thank you so much, Soandso! Those old specimens were much to ancient anyway, fresh ones will help in my mission to heal those who were unfortunate enough to drown and become cursed. If you bring back the three samples I have a little something you might like. Although it will only fit and be of use to one who heals as a profession and is small of stature like myself. Good luck!


elseif **Faction** >= Indifferent then



>**Gapeers Johhanis says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Gapeers Johhanis says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


end



## Turn-Ins



local text = "Oh....well.....This is nice, but I'll need the swollen, waterlogged, and algae covered flesh before I can reward you.";


if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/1736" data-url="1736" class="tooltip-link link">Algae Covered Flesh</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/1737" data-url="1737" class="tooltip-link link">Swollen Flesh</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/1735" data-url="1735" class="tooltip-link link">Waterlogged Flesh</a>) then


>*Gapeers Johhanis cheers as you hand him the samples of zombie flesh. He says, 'You have them! Excellent! Thank you very much, Soandso! Now I have much work to do so shoo before you break something else. Oh and here is your reward. It's an anklet that all our acolytes wear. Not only is it functional, but we can show off our beautiful foot hairs at the same time. Us halflings are pretty smart really.*


Your faction standing with [Priests of Mischief](/faction/300) got better (<span class='text-success'>+5</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guardians of the Vale](/faction/263) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1124.png" alt="" /> <a
                                href="/item/1731" data-url="1731" class="tooltip-link link">Acolyte's Anklet</a> (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-7 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-15 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-15 <img src='/static/icons/item_647.png' width='14' height='14'/> 

else


**This NPC *should* return incorrect items given.**
; 
end

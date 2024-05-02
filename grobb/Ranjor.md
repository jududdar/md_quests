# Ranjor


## Dialog

**You say:** `hail`



>**Ranjor says:** Ya wanna be a member a Da Bashers, duz ya?  What making ya tink yooz is good nuff ta be one o' us?  Can ya proves ta me why I shouldn't oughtta just eat yer smelly hide?  I gonna tests ya, ya big, ugly peece o' meet.  Ya [willin ta test] or duz I just eats ya now?

**You say:** `willin ta test`



if **Faction** >= Amiable then






>**Ranjor says:** Stoopid meat.  I gonna eats ya anyways sumday.  Brings me a froglok meat and two dem li'l froglok tadpole fleshes.  Dey berry good.


elseif **Faction** >= Indifferent then



>**Ranjor says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Ranjor says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



if ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18790" data-url="18790" class="tooltip-link link">A tattered note</a>) then 


>**Ranjor says:** Arhh.. Ranjor mighty warrior.. Ranjor teach you warrior.. you fight for Ranjor now.


Your faction standing with [Da Bashers](/faction/235) got better (<span class='text-success'>+100</span>)



Your faction standing with [Broken Skull Clan](/faction/222) got worse (<span class='text-danger'>-15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13528" data-url="13528" class="tooltip-link link">Mud Covered Tunic*</a> (+20 exp)

 

elseif  **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/13409" data-url="13409" class="tooltip-link link">Froglok Meat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/13187" data-url="13187" class="tooltip-link link">Froglok Tadpole Flesh</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/13187" data-url="13187" class="tooltip-link link">Froglok Tadpole Flesh</a>) then


>**Ranjor says:** You is berry slow. Me too hungry. Me shood eats you for being slow. Gib me dat stuff. Here, take dis and git more stuff fer us. You much kllin, come backs sees me. I teeches ya hows ta kill bedder. Now git and kill stuff. We be Da Bashers fer a reesun.


Your faction standing with [Da Bashers](/faction/235) got better (<span class='text-success'>+5</span>)



Your faction standing with [Broken Skull Clan](/faction/222) got worse (<span class='text-danger'>-1</span>)




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/5025" data-url="5025" class="tooltip-link link">Rusty Two Handed Battle Axe</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**

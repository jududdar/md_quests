# Oracle Jaarl



[Oracle Jaarl](/npc/181077) is a level 42 Gnoll Shaman that spawns in [Jaggedpine Forest](/zone/181).



## Dialog

**You say:** `hail`



>**Oracle Jaarl says:** shakes his body and his countless necklaces cause a loud rattle to echo off the stone walls. 'Hello Soandso. Have you come to [worship] or have you just come for a visit to view our wonderful architecture and to [pay your respects].'

**You say:** `worship`



>**Oracle Jaarl says:** Very well. You worship quietly then. May Brell Serillis bless you.

**You say:** `respects`



>**Oracle Jaarl says:** You have, well then! You can pay your respects by bringing me a [present].

**You say:** `present`



>**Oracle Jaarl says:** I like necklaces. I wear necklaces made from every kind of beast. The power of the beast is contained within each necklace. The more necklaces I wear, the greater my power! Bring me a Bear Fang Necklace, a Wolf Fang Necklace and a Panther Fang Necklace. This will show your devotion to the temple. Then perhaps I can do you a [favor].

**You say:** `favor`



if **Faction** >= Amiable +250 then



**You say:** `favor`





>**Oracle Jaarl says:** I see that you truly respect our temple and more importantly, myself. Since I have great power and you have given me many gifts, I am willing to give you a gift if you are skilled in the ways of the [mystic] or the [heretic].



**You say:** `heretic`





>**Oracle Jaarl says:** I can make a weapon for you, one that you may use to curse your enemies with terrible illness. I require several items. The shaft of the weapon will be made from a Treant Finger. I shall cover the shaft in Griffon Down and affix a Griffon Skull to the top. Finally, I shall need a Diseased Bear Liver with which to imbue the staff with its terrible magic.



**You say:** `treant finger`





>**Oracle Jaarl says:** I doubt a treant would willingly hand over his finger. Remember , the older the treant the stronger the shaft of the weapon will be.



**You say:** `bear liver`





>**Oracle Jaarl says:** The best person to talk to about that would be that human. I believe he calls himself Farkus Grime. He passes through here now and then and he seems to be fascinated with disease. Perhaps he could help you with that.



**You say:** `griffon down`





>**Oracle Jaarl says:** I imagine you could find one of those from a Griffon.



**You say:** `griffon skull`





>**Oracle Jaarl says:** I imagine you could find one of those from a Griffon.




elseif( **Faction is** > Apprehensive) then



>**Oracle Jaarl says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Oracle Jaarl says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1237.png" alt="" /> <a
                                href="/item/8258" data-url="8258" class="tooltip-link link">Wolf Fang Necklace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1237.png" alt="" /> <a
                                href="/item/8261" data-url="8261" class="tooltip-link link">Bear Fang Necklace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1237.png" alt="" /> <a
                                href="/item/8257" data-url="8257" class="tooltip-link link">Panther Fang Necklace</a>) then


>*Oracle Jaarl puts the necklaces around his neck as his body shakes, causing the various bits and pieces of bone and tooth to clatter loudly. 'Ah yes! I feel the power flowing through me, I am ever closer to the spirit world! I thank you for your devotion to the temple!'*


Your faction standing with [Anchorites of Brell Serilis](/faction/1598) got better (<span class='text-success'>+100</span>)

elseif **Faction** >= Amiable +250 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/8268" data-url="8268" class="tooltip-link link">Treant Finger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/8267" data-url="8267" class="tooltip-link link">Griffon Skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_755.png" alt="" /> <a
                                href="/item/8266" data-url="8266" class="tooltip-link link">Griffon Down</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/8265" data-url="8265" class="tooltip-link link">Diseased Bear Liver</a>) then


>**Oracle Jaarl says:** Very well. These will do just fine. Here, it is finished. Take this and smite your enemies with terrible disease.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/8071" data-url="8071" class="tooltip-link link">Rod of Ulceration</a> 

 

**This NPC *should* return incorrect items given.**

# Kaglari



[Kaglari](/npc/52041) is a level 61 Troll GM Shaman that spawns in [Grobb](/zone/52).




## Dialog

**You say:** `hail`



>**Kaglari says:** SNORT!  HHUUUUCCCSSH..  Peh!  You speak at Kaglari, High Priestess of Dark Ones.  Children of Hate.  Spawn of Innoruuk.  Soandso . speak or be gone!  <SNORT!>  You [wish majik power]?

**You say:** `wish majik power`



if **Faction** >= Amiable then




>**Kaglari says:** GOOD! SNORT!! Innoruuk needs more childrens.  You show majik skill or I give you to Innoruuk.  You bring two snake scales and two bone chips ..<SNORT>..  from old bones.  I teach you majik.  GO!  <SNORT!!>


elseif **Faction** >= Indifferent then



>**Kaglari says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Kaglari says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins



if  **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_813.png" alt="" /> <a
                                href="/item/13070" data-url="13070" class="tooltip-link link">Snake Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_813.png" alt="" /> <a
                                href="/item/13070" data-url="13070" class="tooltip-link link">Snake Scales</a>) then 


>**Kaglari says:** SNORT!! Good. Innoruuk get special gift. Not you, dis time. Here. Learning majik wid dis. You more want to help Innoruuk?


Your faction standing with [Dark Ones](/faction/237) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowknights of Night Keep](/faction/308) got better (<span class='text-success'>+1</span>)


Your faction standing with [Frogloks of Guk](/faction/251) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15093" data-url="15093" class="tooltip-link link">Spell: Burst of Flame</a> (+1000 exp)

 

elseif ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18791" data-url="18791" class="tooltip-link link">A tattered note</a>) then 


>**Kaglari says:** Good.. Kaglari need you help.. Kaglari teach you majik now.


Your faction standing with [Dark Ones](/faction/237) got better (<span class='text-success'>+100</span>)


Your faction standing with [Shadowknights of Night Keep](/faction/308) got better (<span class='text-success'>+25</span>)


Your faction standing with [Frogloks of Guk](/faction/251) got worse (<span class='text-danger'>-15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13529" data-url="13529" class="tooltip-link link">Muck Stained Tunic*</a> (+20 exp)

 

**This NPC *should* return incorrect items given.**

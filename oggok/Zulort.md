# Zulort
## Dialog

**You say:** `hail`



>**Zulort says:** Um, you. Hi.. You Shaman of War now, right? You gotta learns war and war spells. We fights all and makes the Warlord likes us. You [gonna help] or me gonna feed you fat stoopid boddie to doggies.

**You say:** `help`



if **Faction** >= Indifferent +50 then 



>**Zulort says:** Good. Warlord need many boddie.. I means Shamans of War.. to kill and gets killed.. no, ummm.. kill and smoosh for Him and makes Him happy. You goes show me you can smoosh tings good. Gets me four froglok tadpole fleshies for me to munchings on and me be happy.. um, He, the Warlord be so berry happy. Helping our tuff friends de Greenbloods but be watching for dem scummy Crakneks, dumb ogres dey is. No good, no our friends. Go now. Me.. er.. he waiting and hungry.


elseif **Faction** >= Indifferent then




>**Zulort says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Zulort says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `bedder shaman`



if **Faction** >= Indifferent +50 then 



>**Zulort says:** Yoo want to be bedda shaman? Them lizards in de Feerrott tink de bedda den us and bodder us wit der majiks like fleas on a dog. Kill dem and bring me, um, one of dem bags dey wear around dem necks and, um, three of dem dolls dey hold.


elseif **Faction** >= Indifferent then




>**Zulort says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Zulort says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins




if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/13187" data-url="13187" class="tooltip-link link">Froglok Tadpole Flesh</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/13187" data-url="13187" class="tooltip-link link">Froglok Tadpole Flesh</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/13187" data-url="13187" class="tooltip-link link">Froglok Tadpole Flesh</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/13187" data-url="13187" class="tooltip-link link">Froglok Tadpole Flesh</a>) then


>**Zulort says:** Oh, me.. um.. Warlord BERRY happy. Berry like dese. Gimme. Uh, why is you still here? Take dis and gets more kills. You learning good, come sees me. I teaches you bout stuff. Make you [bedder shaman]. Go. He and me watching.


Your faction standing with [Shamen of War](/faction/394) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15093" data-url="15093" class="tooltip-link link">Spell: Burst of Flame</a> (+1000 exp)

 

elseif **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_739.png" alt="" /> <a
                                href="/item/14199" data-url="14199" class="tooltip-link link">Allize Volew Medicine Bag</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_720.png" alt="" /> <a
                                href="/item/13367" data-url="13367" class="tooltip-link link">Mystic Doll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_720.png" alt="" /> <a
                                href="/item/13367" data-url="13367" class="tooltip-link link">Mystic Doll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_720.png" alt="" /> <a
                                href="/item/13367" data-url="13367" class="tooltip-link link">Mystic Doll</a>) then


>**Zulort says:** Dis good stuff! Me and Warlord happy! Wear dis symbol and he make yoo strong with majik!


Your faction standing with [Shamen of War](/faction/394) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/1444" data-url="1444" class="tooltip-link link">Initiate Symbol of Rallos Zek</a> (+1000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18788" data-url="18788" class="tooltip-link link">A tattered note</a>) then 


>**Zulort says:** Take, take.. You now Shaman of War.. Zulort make you majik, too.


Your faction standing with [Shamen of War](/faction/394) got better (<span class='text-success'>+100</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13526" data-url="13526" class="tooltip-link link">Dirty Patched Fur Tunic*</a> (+20 exp)

 


**This NPC *should* return incorrect items given.**







# Kogna
## Dialog

**You say:** `Hail`



>**Kogna says:** You be tinking you be [real tuff Craknek]?

**You say:** `real tuff craknek`



if **Faction** >= Indifferent +50 then



>**Kogna says:** Me not tinking so. but maybe me wrongs.. no.. me neber wrongs.  You no tuff. only liddle Craknek is you.  You tink you be tuff Craknek. you bringed me four lizard meats.  Me like lizard meats.  You no tuff.  You bringed me lizard [meats].  I make you tuffer Craknek.  Me bestest Craknek.


elseif **Faction** >= Indifferent then




>**Kogna says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Kogna says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `meats`



>**Kogna says:** Yup, meats.  You brings me four, me gives you sumting.
end

## Turn-Ins



if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/13410" data-url="13410" class="tooltip-link link">Lizard Meat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/13410" data-url="13410" class="tooltip-link link">Lizard Meat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/13410" data-url="13410" class="tooltip-link link">Lizard Meat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/13410" data-url="13410" class="tooltip-link link">Lizard Meat</a>) then


>**Kogna says:** No, I donut tink so. Who gived you? Bah, me most tuffest Craknek, but me no lier. Me help you be tuffer Craknek. Who gived you dese? Maybe you finded dead lizards, yes, dat it. Bah, taking dis and kills more tings. You learned much, com see me, I teaches you best Craknek ways. Keep eye on dem Greenbloods, dey nasty and not so tuff.


Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+5</span>)


Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+1</span>)


Your faction standing with [Green Blood Knights](/faction/261) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/5025" data-url="5025" class="tooltip-link link">Rusty Two Handed Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5023" data-url="5023" class="tooltip-link link">Rusty Two Handed Sword</a>) (+550 exp)

 

**This NPC *should* return incorrect items given.**






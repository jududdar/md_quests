# Linadian
## Dialog

**You say:** `hail`



>**Linadian says:** Greetings! Please look through my fine wares. I have spent most of my life practicing my skills in tailoring. I do my best to compete with the other local merchants, but I have yet to make a profit. I pray to Tunare that my [banded orc vests] will finally bring me a few extra coins.

**You say:** `banded orc vest`



if **Faction** >= Indifferent then



>**Linadian says:** Glad you are interested. I can create a leather vest I call a banded orc vest. It will aid you in repelling any disease and offers quite a bit of protection in battle. I will need some materials. For a Deathfist banded orc vest, I require two legionnaire pads worn by the clan Deathfist, one Deathfist slashed belt, and ten gold coins. For a Crushbone banded orc vest, I require two legionnaire pads worn by the Clan Crushbone, one Crushbone belt, and one silk swatch.'


else



>**Linadian says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.

end

## Turn-Ins





if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/13319" data-url="13319" class="tooltip-link link">Crushbone Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/13319" data-url="13319" class="tooltip-link link">Crushbone Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/13318" data-url="13318" class="tooltip-link link">Crushbone Belt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/16482" data-url="16482" class="tooltip-link link">Silk Swatch</a>) then


>**Linadian says:** Grand doing business with you. Hold your nose. I can never get rid of the orc stench of the vests. That is why the other merchants do not pay me much for them.


Your faction standing with [Kelethin Merchants](/faction/276) got better (<span class='text-success'>+5</span>)


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+1</span>)


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+1</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_538.png" alt="" /> <a
                                href="/item/12187" data-url="12187" class="tooltip-link link">Banded Orc Vest</a> (+100 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/13917" data-url="13917" class="tooltip-link link">Deathfist Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/13917" data-url="13917" class="tooltip-link link">Deathfist Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/13916" data-url="13916" class="tooltip-link link">Deathfist Slashed Belt</a>,gold = 10) then


>**Linadian says:** Grand doing business with you. Hold your nose. I can never get rid of the orc stench of the vests. That is why the other merchants do not pay me much for them.


Your faction standing with [Kelethin Merchants](/faction/276) got better (<span class='text-success'>+5</span>)


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+1</span>)


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+1</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_538.png" alt="" /> <a
                                href="/item/12187" data-url="12187" class="tooltip-link link">Banded Orc Vest</a> (+100 exp)

 

**This NPC *should* return incorrect items given.**

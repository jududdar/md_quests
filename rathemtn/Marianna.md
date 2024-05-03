# Marianna


## Dialog

**You say:** `hail`



>**Marianna says:** Rodcet Nife welcomes you into our noble camp.  I am the keeper of the [Vambraces of Ro].

**You say:** `vambraces of ro`



if **Faction** >= Indifferent +50 then



>**Marianna says:** The mold will be offered to you when you have performed a task for the Temple of Life.  The oceans near our home are host to a plague..  the plague sharks!!  They have been infected with a deadly malady which has been turning up in the Qeynos Hills.  Kill the sharks and bring me two of their rotten shark portions as proof.


elseif **Faction** >= Indifferent then



>**Marianna says:** In the name of Rodcet Nife, I must ask you to venture to Qeynos and find the Temple of Life.  There you shall serve until High Priestess Jhanda responds when you ask her, am [I an honored member]?


else



>**Marianna says:** Foolish person!! The word is out amongst the followers of the Prime Healer not to trust you.

end



## Turn-Ins



local text = "I said two portions of rotten shark meat.";



if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_814.png" alt="" /> <a
                                href="/item/12310" data-url="12310" class="tooltip-link link">Rotten Shark Meat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_814.png" alt="" /> <a
                                href="/item/12310" data-url="12310" class="tooltip-link link">Rotten Shark Meat</a>) then


>**Marianna says:** You now own a mold for the Vambraces of Ro.  Go and ask Thomas of [Lord Searfire] for the final component.


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+20</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+6</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+10</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/12300" data-url="12300" class="tooltip-link link">Mold of Ro Vambrace</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**








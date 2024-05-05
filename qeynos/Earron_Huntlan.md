# Earron Huntlan



[Earron Huntlan](/npc/1106) is a level 13 Human Shopkeeper that spawns in [South Qeynos](/zone/1).



## Dialog

**You say:** `hail`



>**Earron Huntlan says:** Greetings, thirsty adventurer! Please help yourself to the free salty snacks. We are here to serve you at the Lion's Main Tavern. Allow yourself to indulge from our wide selection oof fine spirits.

**You say:** `kwint`



if **Faction** >= Apprehensive then 



>**Earron Huntlan says:** Kwint? Gave you the line about being my brother, huh? That boy sends me more customers, I tells ya! I give him one free drink for every person he gets to come in. Hey, could you do me a favor and take this voucher to him when you are done drinking? Thanks.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18821" data-url="18821" class="tooltip-link link">A Scrap of Parchment</a>


else



**Earron Huntlan says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18821" data-url="18821" class="tooltip-link link">A Scrap of Parchment</a>) then


>**Earron Huntlan says:** What the..? This voucher was for Kwint, not you! I will find someone more trustworthy to take it to him.







Your faction standing with [Merchants of Qeynos](/faction/291) got worse (<span class='text-danger'>-25</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+5</span>)


Your faction standing with [Antonius Bayle](/faction/219) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Coalition of Tradefolk](/faction/229) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-5</span>)

**This NPC *should* return incorrect items given.**

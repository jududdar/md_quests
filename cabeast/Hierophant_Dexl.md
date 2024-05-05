# Hierophant Dexl



[Hierophant Dexl](/npc/106101) is a level 61 Iksar GM Shaman that spawns in [Cabilis East](/zone/106).





## Dialog

**You say:** `Hail`



>*Hierophant Dexl seems to be preocupied. He is examining an egg. 'What?!! Who has [sent] you to me? Bah!! Away with you.' He ignores you and continues chanting.'*

**You say:** `di nozok sent`



if **Faction** >= Amiable then



>*Hierophant Dexl drops the egg he was holding. Egg yolk splatters on your foot. His eyes roll back into his head. He speaks, but his voice is that of a female. 'I await you, Soandso . My sisters and I yearn for the return of our skulls. We are the [Sisters of Scale]. Find us and bring to this hierophant our skulls and your iron cudgel of the Channeler. Go.*


elseif **Faction** >= Indifferent then



>**Hierophant Dexl says:** You will only obtain that which you seek by assisting the wills of the Scaled Mystics.


else



**Hierophant Dexl says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




**You say:** `sisters`



>*Hierophant Dexl wipes egg yolk from his clothing. 'My, what a mess!! Hmmph!! What did you say? Sisters of Scale? They were a legendary trio of mystics. We once had their skulls sealed within this temple, but now they are lost. I sent a channeler to retrieve them. His name was Vagnar. I am sure he shall find them.*


e.self:DoAnim(33);

**You say:** `vagnar`



>**Hierophant Dexl says:** He's a capable channeler, I trust he knows where to look and will prepare himself. Any competent servant of our Lord would prepare potions and supplies before going on such a quest. If he doesn't come back, it's no great loss, he wasn't Hierophant material anyway.
end



## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/5145" data-url="5145" class="tooltip-link link">Iron Cudgel of the Channeler</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12748" data-url="12748" class="tooltip-link link">An Iksar Skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12750" data-url="12750" class="tooltip-link link">An Iksar Skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12749" data-url="12749" class="tooltip-link link">An Iksar Skull</a>) then


>*Hierophant Dexl goes into a trance and speaks with the voice of an ancient. 'You have returned the skulls of the Sisters of Scale. For this you shall be rewarded. Take this hierophant's weapon. May you use it to smite the foes of our people.' Dexl comes out of the trance. 'What?!! Whew. Hey!! Where is my cudgel?*


Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+10</span>)







Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+10</span>)







 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/5146" data-url="5146" class="tooltip-link link">Iron Cudgel of the Hierophant</a> (+140000 exp)

 


**This NPC *should* return incorrect items given.**






# Hierophant Zand



[Hierophant Zand](/npc/106102) is a level 61 Iksar GM Shaman that spawns in [Cabilis East](/zone/106).





## Dialog

**You say:** `chosen savior`



if **Faction** >= Amiable then



>**Hierophant Zand says:** I am honored to meet the one who shall pledge his life to the return of the Skulls of the Ancients. However, I must see proof of our prowess as of yet. Go to the outlands and retrieve one Froglok Hexdoll, and no, they are not found on Frogloks. They are shaman dolls made by the goblin tribe.


elseif **Faction** >= Indifferent then



>**Hierophant Zand says:** You will only obtain that which you seek by assisting the wills of the Scaled Mystics.


else



**Hierophant Zand says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




**You say:** `hail`



>*Hierophant Zand raises his hand and looks up.  'May the wisdom of the ancients lead your soul to suffering and everlasting pain.  Such is the will of Cazic-Thule.  I see something in your eyes, Hatz.  Have you lost something... your cudgel perhaps?*

**You say:** `no`



>**Hierophant Zand says:** That is good to hear.  Continue to follow the path of pain.  Suffering awaits.

**You say:** `yes`





>**Hierophant Zand says:** That is most unfortunate for you.  Your suffering will be extended on this plane, until you find your way back to us. Take this and read it on your way to speak with the Toilmaster.  He will guide you.  Yesssss...' You feel as if something is peering at you from behind the speaker's soulless eyes as the last letter he speaks transforms into a sigh.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/18271" data-url="18271" class="tooltip-link link">A Ragged Book</a>





**You say:** `skulls of di nozok`



>**Hierophant Zand says:** What?! I have read of them, but that is all I know of the legendary mystic, err, mystics... whatever! Where their remains rest is a mystery, but those filthy goblins always seem to get ahold of things that are lost, all that infernal digging you see.


e.self:DoAnim(65);
end



## Turn-Ins



local text1 = "seems to black out, and then recover. He speaks with the voice of an ancient. 'We are Dai and Die and we await our skulls and your iron cudgel of the prophet. Become a channeler.";




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/18272" data-url="18272" class="tooltip-link link">Rites of Exoneration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/24770" data-url="24770" class="tooltip-link link">Filled Penance Bag</a>) then 


>*Hierophant Zand takes the bag and tome from you and in return gives you the item that you have been thinking of all of this time. 'Lucky you. You have earned a second chance. Praise Cazic-Thule!'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/5140" data-url="5140" class="tooltip-link link">Iron Cudgel of the Petitioner</a> 

 







if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1007.png" alt="" /> <a
                                href="/item/12734" data-url="12734" class="tooltip-link link">A Froglok Hex Doll</a>) then


>**Hierophant Zand says:** Fine work! I hope for your sake, you did not purchase it from a brave adventurer. Take this note to the one for whom it is written. This lizard has knowledge of a large number of skulls.


Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+10</span>)






Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+10</span>)






 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/18054" data-url="18054" class="tooltip-link link">The Bone Garrison</a> (+80000 exp)

**You receive coin:** 5 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 




elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12741" data-url="12741" class="tooltip-link link">Iksar Skull Helm</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/5144" data-url="5144" class="tooltip-link link">Iron Cudgel of the Prophet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12740" data-url="12740" class="tooltip-link link">Iksar Skull</a>) then


>*Hierophant Zand closes his eyes and reopens them. They have no pupils. He speaks and you hear his voice echo. 'We are Di Nozok. You have earned the weapon of a channeler. We hope to fill your thoughts with ours some day. Go and seek out Dexl. We send you to him. Farewell , Channeler of Cabilis.*


Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+20</span>)






Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+5</span>)






 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/5145" data-url="5145" class="tooltip-link link">Iron Cudgel of the Channeler</a> (+120000 exp)

 


**This NPC *should* return incorrect items given.**







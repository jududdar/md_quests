# Maesyn Trueshot
## Dialog

**You say:** `hail`



>**Maesyn Trueshot says:** Welcome to Kelethin, Soandso! I am Maesyn Trueshot, commander of Faydark's Champions. We are the finest marksmen in all of Norrath. With our trusty [Trueshot longbows] we can miss no target regardless of the distance or the conditions.

**You say:** `trueshot longbows`



>**Maesyn Trueshot says:** The Trueshot Longbow was created by my famed father. Eldin Trueshot. It is quite accurate and takes a ranger's skill to wield. We use our new recruits to [gather materials] needed by my father.  We shall soon begin to release the formula to good elves so all may fletch such a bow.

**You say:** `correct component`



>**Maesyn Trueshot says:** Now that I have crafted the Treant Bow Staff, you shall need one Planing Tool, one Treant Bow Staff, one Micro Servo and one spool of Dwarven Wire. These items will be used with your Fletching Kit as all other bows. Be forewarned, only a Master Fletcher can create such a bow and even a master fails from time to time. Good Luck.

**You say:** `next incarnation`



>**Maesyn Trueshot says:** The Trueshot Longbow was once enchanted by the Koada'Dal enchanters.  Once it was enchanted now it is no more.  I am sure if you were ask the Koada'Dal [where the enchanted bows] are you will get an answer.

**You say:** `gather material`



if **Faction** >= Amiable then 



>**Maesyn Trueshot says:** Take this pack. Go to Kaladim, find Trantor Everhot and ask for dwarven wire. Then go to Freeport to meet Jyle Windshot. Search the inns for him and ask him for treant wood. Then, collect some spiderling silk from spiderlings and finally, in Steamfont, we have the permission of the gnomes to use any micro servos we find while destroying rogue spiders. Combine them all and return the pack to me.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_689.png" alt="" /> <a
                                href="/item/17951" data-url="17951" class="tooltip-link link">Material Pack</a>


elseif( **Faction is** == Indifferent) then



>**Maesyn Trueshot says:** Faydark's Champions cannot call you foe. but you have yet to earn our trust.


else



>**Maesyn Trueshot says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.

end

## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/12112" data-url="12112" class="tooltip-link link">Pack of Materials</a>) then 


>**Maesyn Trueshot says:** I shall see that my father gets the materials. I hope this can be of use to you. It will serve as your starting point toward fletching a Trueshot longbow. It is unfortunate that we are unable to enchant the bow to its [next incarnation], but it is still a fine weapon. You do know the [correct components] needed for fletching such a bow, do you not?


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+5</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+1</span>)


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+1</span>)


Your faction standing with [Soldiers of Tunare](/faction/310) got better (<span class='text-success'>+1</span>)


Your faction standing with [Crushbone Orcs](/faction/234) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/8091" data-url="8091" class="tooltip-link link">Treant Bow Staff</a> (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18785" data-url="18785" class="tooltip-link link">A tattered note</a>) then 


>**Maesyn Trueshot says:** Hail, Soandso, and welcome.. I am Maesyn Trueshot, leader of Faydark's Champions. I will teach and train you, as I have done for many others. Let's get started.. Here, put this on.. it'll help protect you from the elements. You look pretty bright. Train hard, and I'm sure you'll do well.


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+100</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+25</span>)


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+25</span>)


Your faction standing with [Soldiers of Tunare](/faction/310) got better (<span class='text-success'>+25</span>)


Your faction standing with [Crushbone Orcs](/faction/234) got worse (<span class='text-danger'>-25</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13536" data-url="13536" class="tooltip-link link">Dirty Green Tunic*</a> (+20 exp)

 

**This NPC *should* return incorrect items given.**



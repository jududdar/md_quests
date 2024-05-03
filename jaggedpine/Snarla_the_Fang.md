# Snarla the Fang


## Dialog

**You say:** `hail`



if( **Faction is** > Dubious) then



**You say:** `hail`





>**Snarla the Fang says:** Shhh. quiet! This is place of solitude and peace! You [respect temple] while you here if you know what good for you!



**You say:** `respect temple`





>**Snarla the Fang says:** One way guests show respect is to bring the host [food]. Something really good would be nice.



**You say:** `food`





>**Snarla the Fang says:** Lessee. . . Dryad Pate is what I want. Bring me some [Dryad Pate] and then you be a good guest. Maybe then I return a favor for you.



**You say:** `dryad pate`





>**Snarla the Fang says:** I don't know how it made. Talk to the Brargus about it. He the cook.



**You say:** `necklace`





>**Snarla the Fang says:** I make many different kinds of necklaces for my friends from fangs of powerful creatures like bear, panther and wolf. You give me your token of friendship and I give you a pouch to keep some stuff in. After you get the stuff and seal the bag, bring it back and I make you a nice necklace to wear. Stuff I need is one Anaconda Skin and three Fangs. Fangs that make good necklaces are Wolf, Bear and Panther. Make sure all fangs are same. Necklaces with different fangs are neat but not as nice as ones with all same fangs, so I only make those ones.




else



**Snarla the Fang says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins





if( **Faction is** > Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/8199" data-url="8199" class="tooltip-link link">Dryad Pate</a>) then 


>**Snarla the Fang says:** Ohh. . . This really good, thanks! You take this token of friendship. You all smell the same so this way I know who you are. I can make nice [necklaces] for my friends.


Your faction standing with [Anchorites of Brell Serilis](/faction/1598) got better (<span class='text-success'>+20</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/8270" data-url="8270" class="tooltip-link link">Token of Friendship</a> 

 

elseif( **Faction is** > Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/8270" data-url="8270" class="tooltip-link link">Token of Friendship</a>) then 


>**Snarla the Fang says:** Ok, here pouch to collect stuff. Come back when pouch full. Make sure you seal pouch or stuff may fall out.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_679.png" alt="" /> <a
                                href="/item/17263" data-url="17263" class="tooltip-link link">Necklace Component Pouch</a> 

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/8270" data-url="8270" class="tooltip-link link">Token of Friendship</a> 

 

elseif( **Faction is** > Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_667.png" alt="" /> <a
                                href="/item/9228" data-url="9228" class="tooltip-link link">Sealed Wolf Fang Pouch</a>) then 


>**Snarla the Fang says:** Oh hello friend, I make this nice necklace for you! You wear this and feel the spirit of the wolf run through you!


Your faction standing with [Anchorites of Brell Serilis](/faction/1598) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1237.png" alt="" /> <a
                                href="/item/8258" data-url="8258" class="tooltip-link link">Wolf Fang Necklace</a> 

 

elseif( **Faction is** > Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_667.png" alt="" /> <a
                                href="/item/9229" data-url="9229" class="tooltip-link link">Sealed Bear Fang Pouch</a>) then 


>**Snarla the Fang says:** My friend returns again! I make this nice necklace for you. Wear this and feel the essence of the bear flow through you.


Your faction standing with [Anchorites of Brell Serilis](/faction/1598) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1237.png" alt="" /> <a
                                href="/item/8261" data-url="8261" class="tooltip-link link">Bear Fang Necklace</a> 

 

elseif( **Faction is** > Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_667.png" alt="" /> <a
                                href="/item/9230" data-url="9230" class="tooltip-link link">Sealed Panther Fang Pouch</a>) then 


>**Snarla the Fang says:** Hello again friend. This nice panther fang, here you take this necklace I make you. It imbued with spirit of the cat.


Your faction standing with [Anchorites of Brell Serilis](/faction/1598) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1237.png" alt="" /> <a
                                href="/item/8257" data-url="8257" class="tooltip-link link">Panther Fang Necklace</a> 

 

**This NPC *should* return incorrect items given.**

# Expin
## Dialog

**You say:** `hail`



>**Expin says:** How are you, my friend?  You must be a [new scout of Kelethin].  I would hope so.  We dearly need more recruits.  Most of the Fier'Dal choose the path of the ranger.

**You say:** `new scout of kelethin`



if **Faction** >= Amiable then



>**Expin says:** Good. I have an easy, but very important, task for you. We require all young members to cleanse these woods of the troublesome pixie tricksters. Take this pouch, fill it with pixie dust, and when it is combined, return it to me. I just may have some used armor lying around for you.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/17957" data-url="17957" class="tooltip-link link">Empty Pouch</a>


elseif( **Faction is** == Indifferent) then



>**Expin says:** The Scouts of Tunare have no quarrel with you, but perhaps a few less Crushbone Orcs would prove your worth. Then we shall speak.


else



>**Expin says:** You dare to speak with a loyal member of the Scouts of Tunare?!  You are truly foolish!  Run away, while you still can.


**You say:** `dark assassin`



>*Expin squints at you and says, 'So you have heard about him as well? I had heard of him through the rogue grapevine, so I was wary when the home guard spoke of the arrival of a dark stranger. I was approaching him from behind and some loud ranger clompipng about in the bushes must of spooked him, for off he ran. As he was running I took the liberty to swipe a piece of paper protruding from his pocket.' Expin mumbles to himself, 'Now where did I put that note?'*

**You say:** `not satisfied`



>**Expin says:** I told you not to tell me.
end

## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/12109" data-url="12109" class="tooltip-link link">Pouch of Pixie Dust</a>) then 


>**Expin says:** Good work, scout!!  You have earned this reward.  It is all we have at the time.  I am certain you are satisfied.  If not, then do not let me hear of it.


Your faction standing with [Scouts of Tunare](/faction/316) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2104" data-url="2104" class="tooltip-link link">Patchwork Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2106" data-url="2106" class="tooltip-link link">Patchwork Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2108" data-url="2108" class="tooltip-link link">Patchwork Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2111" data-url="2111" class="tooltip-link link">Patchwork Pants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2112" data-url="2112" class="tooltip-link link">Patchwork Boots</a>) (+800 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/16390" data-url="16390" class="tooltip-link link">Crumpled Piece of Paper</a>) then 


>**Expin says:** Ahhh! You found it! Here let me make you a copy and put this in a secure spot so I don't lose it again.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1005.png" alt="" /> <a
                                href="/item/24098" data-url="24098" class="tooltip-link link">Remiss Sketch</a> (+50 exp)

 

**This NPC *should* return incorrect items given.**



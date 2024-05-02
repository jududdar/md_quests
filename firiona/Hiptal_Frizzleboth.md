# Hiptal Frizzleboth
## Dialog

**You say:** `Hail`



>**Hiptal Frizzleboth says:** Bah!! It's not been a good day! Reports from the Outlands are even worse than I was led to believe. Many would-be adventurers have turned up missing of late. One of them was one of my messenger. He was out collecting some of the various new and [interesting scrolls] that have been surfacing in the farthest reaches of this land. I fear for his safety and that of the others searching for the lost travelers. I wish there was more I could do.

**You say:** `interesting scrolls`



>*Hiptal Frizzleboth reaches into his pouch. 'Well, let's see what I have in here. Ah, yes. The scrolls are definitely worth finding. Possibly even dangerous if they should fall into the wrong hands. But that is why the Collective sent me here. To procure all of the scrolls so that they may be studied at the Library of Mechanimagica. Bah!! But my messenger is missing! I can't fail them. Would you be willing to [help locate] some of the scrolls I am missing?*

**You say:** `help locate`



>**Hiptal Frizzleboth says:** You would do that for me? Of course you would, you realize how important my work is here. Your task is quite simple, really. I'll part with one of my rare scrolls if you bring me one of the common ones from the surrounding areas. To be more precise, I am looking for the scrolls Gift of Xev and Bristlebane's Bundle. Oh, my nephew is going to love these! I can't wait to get my hands on them! I'm also looking for the scrolls Quiver of Marr and Scars of Sigil. Bring them back to me as soon as you find one.
end

## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19351" data-url="19351" class="tooltip-link link">Spell: Bristlebane\`s Bundle</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19347" data-url="19347" class="tooltip-link link">Spell: Gift of Xev</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19354" data-url="19354" class="tooltip-link link">Spell: Quiver of Marr</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19358" data-url="19358" class="tooltip-link link">Spell: Scars of Sigil</a>}

if(count > 0) then


repeat



>**Hiptal Frizzleboth says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19368" data-url="19368" class="tooltip-link link">Spell: Boon of Immolation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19346" data-url="19346" class="tooltip-link link">Spell: Scintillation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19355" data-url="19355" class="tooltip-link link">Spell: Vocarate: Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19357" data-url="19357" class="tooltip-link link">Spell: Vocarate: Air</a>) (+1000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**






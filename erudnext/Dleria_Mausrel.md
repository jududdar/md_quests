# Dleria Mausrel
## Dialog

**You say:** `Hail`



>**Dleria Mausrel says:** Hail! You appear to be a [new priest]. Ah, I so enjoy the presence of youth within Deepwater Temple. I am sure Prexus is smiling upon us as we speak.

**You say:** `new priest`



if **Faction** >= Amiable then 



**You say:** `new priest`





>**Dleria Mausrel says:** As I suspected. I shall assist you with your training and you shall assist the temple with your service. A young priest can help out by asking to [convert fishermen in Qeynos] or maybe even something truly great such as requesting to [protect the depths].



**You say:** `protect the depth`





>**Dleria Mausrel says:** We have heard of zombies inhabiting the depths of Erud's Crossing. Go and seek them out. Destroy them. This evil should not exist within the realm of the Ocean Lord. Take this bag. Fill it with their rotting flesh. combine it and return it to me. May Prexus guide you.




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17939" data-url="17939" class="tooltip-link link">Empty Bag</a>



**You say:** `convert fishermen in qeynos`





>**Dleria Mausrel says:** So you wish to journey to Qeynos? So be it. Go to Qeynos and find me a willing convert. Ask them if they wish the blessing of Prexus. If so, they should snap their pole in two and you will return it to me. Do this and be rewarded.




elseif **Faction** >= Indifferent then



>**Dleria Mausrel says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Dleria Mausrel says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.

end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_749.png" alt="" /> <a
                                href="/item/13922" data-url="13922" class="tooltip-link link">Snapped Pole</a>) then 


>**Dleria Mausrel says:** Good work, young priest. Soon you shall carry the word of the Ocean Lord to distant lands. For now, continue your training. As for your reward, I have this which has been sitting in our vault. I hope it can be of use to a young priest such as yourself.





Your faction standing with [Deepwater Knights](/faction/242) got better (<span class='text-success'>+5</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+1</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2144" data-url="2144" class="tooltip-link link">Raw-hide Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2146" data-url="2146" class="tooltip-link link">Raw-hide Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2147" data-url="2147" class="tooltip-link link">Raw-hide Leggings</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/17005" data-url="17005" class="tooltip-link link">Backpack</a>) (+4000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/13880" data-url="13880" class="tooltip-link link">Bag of Zombie Flesh</a>) then 


>**Dleria Mausrel says:** Peeuww!! That most certainly is zombie flesh!! Here is your reward. You have done a fine service in the name of Prexus. Soon you shall advance and we may tell you of greater dangers lurking in the depths.





Your faction standing with [Deepwater Knights](/faction/242) got better (<span class='text-success'>+10</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+1</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2144" data-url="2144" class="tooltip-link link">Raw-hide Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2146" data-url="2146" class="tooltip-link link">Raw-hide Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2147" data-url="2147" class="tooltip-link link">Raw-hide Leggings</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/17005" data-url="17005" class="tooltip-link link">Backpack</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15205" data-url="15205" class="tooltip-link link">Spell: True North</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15203" data-url="15203" class="tooltip-link link">Spell: Cure Poison</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15207" data-url="15207" class="tooltip-link link">Spell: Divine Aura</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15201" data-url="15201" class="tooltip-link link">Spell: Flash of Light</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15208" data-url="15208" class="tooltip-link link">Spell: Lull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15209" data-url="15209" class="tooltip-link link">Spell: Spook the Dead</a>) (+4000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;


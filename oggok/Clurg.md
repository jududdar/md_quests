# Clurg
## Dialog

**You say:** `hail`



>**Clurg says:** Hello, friend. Have a drink. I have some [unique drinks]. Try one. And remember. You get rowdy, the [Bouncers] crush you.

**You say:** `bouncers`



>**Clurg says:** The Bouncers were organized by me. As I traveled to many of the world's taverns I encountered great enforcers called bouncers. It was their duty to keep order amongst chaos. When I returned and rose to greatness after the creation of the [Flaming Clurg]. I organized the Oggok Bouncers to keep order amongst the [rival guilds].

**You say:** `flaming clurg`



>**Clurg says:** The Flaming Clurg was my greatest creation. It brought me great respect in Oggok. Unfortunately, I have heard tales of an [imposter drink].

**You say:** `imposter drink`



if **Faction** >= Indifferent +50 then 



>**Clurg says:** I have heard there is a barkeep who dares to sell a similar drink in Neriak's Foreign Quarter. I have put a price on his head. Anyone who returns with his head shall be greatly rewarded.


elseif **Faction** >= Indifferent then




>**Clurg says:** Find ways to help all in Oggok. Then we will have conversation.


else



>**Clurg says:** You are brave. An enemy are you of Oggok. Leave while you still can.








**You say:** `rival guilds`



>**Clurg says:** Oggok has been the battleground for the feud between the Greenblood knights and shamans and the Craknek warriors. It is fueled by the superior intellect of the Greenbloods. Few remember that I, Clurg, was once dim, but now I speak with great words.

**You say:** `unique drinks`



>**Clurg says:** I have been all over Norrath and even served with some very great [barkeeps in Freeport]. I am the creator of both [Flaming Clurg] and Ogre Swill.

**You say:** `barkeeps in freeport`



>**Clurg says:** Yes. I have journeyed to many taverns, but it was in Freeport that I acquired most of my art. I compiled all my drink recipes in a [special book].


**You say:** `special book`



if **Faction** >= Indifferent +50 then 




>**Clurg says:** I compiled all my drinks into one book. I lost this book while in Freeport. No doubt some barkeep is experimenting with it. I would pay dearly for the return of my Barkeep Compendium.


elseif **Faction** >= Indifferent then




>**Clurg says:** Find ways to help all in Oggok. Then we will have conversation.


else



>**Clurg says:** You are brave. An enemy are you of Oggok. Leave while you still can.








end

## Turn-Ins




if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/13379" data-url="13379" class="tooltip-link link">Barkeep Compendium</a>) then 


>**Clurg says:** Ahhh!! My Barkeep Compendium has been returned!! I am in your debt. I do not like to be in any man's debt. Let me offer you this as payment for your great service. Obtaining my book could not have been a simple task.





Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+50</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Green Blood Knights](/faction/261) got better (<span class='text-success'>+50</span>)


Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+50</span>)


Your faction standing with [Oggok Guards](/faction/337) got better (<span class='text-success'>+50</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_709.png" alt="" /> <a
                                href="/item/13380" data-url="13380" class="tooltip-link link">Stein of Moggok</a> (+500 exp)

 

elseif **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_920.png" alt="" /> <a
                                href="/item/13378" data-url="13378" class="tooltip-link link">Ogre Head</a>) then 


>**Clurg says:** Haha! He shall mix no more Flaming Pungla's! I shall drink from his rotting skull tonight. As for you, take this and call it yours. Consider yourself a friend of Clurg.





Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+15</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Green Blood Knights](/faction/261) got better (<span class='text-success'>+15</span>)


Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+15</span>)


Your faction standing with [Oggok Guards](/faction/337) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_543.png" alt="" /> <a
                                href="/item/3132" data-url="3132" class="tooltip-link link">Large Ringmail Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_527.png" alt="" /> <a
                                href="/item/3128" data-url="3128" class="tooltip-link link">Large Ringmail Coat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_526.png" alt="" /> <a
                                href="/item/3134" data-url="3134" class="tooltip-link link">Large Ringmail Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_540.png" alt="" /> <a
                                href="/item/3135" data-url="3135" class="tooltip-link link">Large Ringmail Pants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_545.png" alt="" /> <a
                                href="/item/3136" data-url="3136" class="tooltip-link link">Large Ringmail Boots</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_950.png" alt="" /> <a
                                href="/item/10021" data-url="10021" class="tooltip-link link">Star Rose Quartz</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_953.png" alt="" /> <a
                                href="/item/10024" data-url="10024" class="tooltip-link link">Pearl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_581.png" alt="" /> <a
                                href="/item/6302" data-url="6302" class="tooltip-link link">Ogre War Maul</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_708.png" alt="" /> <a
                                href="/item/13355" data-url="13355" class="tooltip-link link">A Crude Stein</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6006" data-url="6006" class="tooltip-link link">Warhammer</a>) (+500 exp)

**You receive coin:** 5 <img src='/static/icons/item_644.png' width='14' height='14'/> 1 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

else


e.other:Say("I am no dumb ogre. I take gift when handed.");



**This NPC *should* return incorrect items given.**






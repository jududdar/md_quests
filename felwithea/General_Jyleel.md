# General Jyleel


## Dialog

**You say:** `hail`



>**General Jyleel says:** Stand at attention!!  I am General Jyleel. of the Koada'Vie. defenders of Felwithe.  Do you [follow Tunare]. the Mother of All. or do you still [seek your enlightenment]?

**You say:** `follow tunare`



if **Faction** >= Amiable then




>**General Jyleel says:** Then you are wise indeed.  Would you like to [assist the defenders] in our conflicts or have you other business to attend to?


elseif( **Faction is** == Indifferent) then



>**General Jyleel says:** No.  You have yet to prove yourself a truly faithful defender of the Clerics of Tunare.  I await your return when you complete your service to the temple.


else



>**General Jyleel says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!


**You say:** `seek my enlightenment`



>**General Jyleel says:** Then seek it within these walls.  We welcome all fine upstanding Koada'Dal.

**You say:** `assist the defenders`



if **Faction** >= Amiable then



>**General Jyleel says:** Seek out the Crushbone orcs of the Faydarks.  We must have their oracle scrolls.  They are illegible to you, but we will study them here in Felwithe.  Only the orc oracles will carry them, so be very careful.  There is also the problem with the [Crushbone runners].


elseif( **Faction is** == Indifferent) then



>**General Jyleel says:** No.  You have yet to prove yourself a truly faithful defender of the Clerics of Tunare.  I await your return when you complete your service to the temple.


else



>**General Jyleel says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!


**You say:** `crushbone runners`



if **Faction** >= Amiable then



>**General Jyleel says:** The Crushbone orcs are sending messages across the Ocean of Tears to Antonica.  Why. we do not know.  The runner is usually spotted on the open pathways of Butcherblock. running toward the docks.  Find him. kill him. and return his note pouch.


elseif( **Faction is** == Indifferent) then



>**General Jyleel says:** No.  You have yet to prove yourself a truly faithful defender of the Clerics of Tunare.  I await your return when you complete your service to the temple.


else



>**General Jyleel says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!


**You say:** `faithful paladin`



if **Faction** >= Amiable then



>**General Jyleel says:** I command you to seek out this Ambassor DVinn and rip his heart from his lifeless body. Next, find the supreme caster of the orcs and, finally, find the spot where supplies are dropped by the Teir\`Dal for the orcs. There you should find the supply crate. Return all 3 items and you shall wield the falchion.


elseif( **Faction is** == Indifferent) then



>**General Jyleel says:** No.  You have yet to prove yourself a truly faithful defender of the Clerics of Tunare.  I await your return when you complete your service to the temple.


else



>**General Jyleel says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!

end



## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13225" data-url="13225" class="tooltip-link link">Illegible Scroll</a>) then


>**General Jyleel says:** Very fine work. A pity you are not Koada'Vie. Here is a small reward for you. Anytime you come upon an oracle. remember to return its scroll to me. Go and find your fate on the field of battle.


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+5</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+5</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+3</span>)


if(math.random(100) > 10) then



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_684.png" alt="" /> <a
                                href="/item/13003" data-url="13003" class="tooltip-link link">Small Lantern</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_728.png" alt="" /> <a
                                href="/item/13004" data-url="13004" class="tooltip-link link">Large Lantern</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_599.png" alt="" /> <a
                                href="/item/14013" data-url="14013" class="tooltip-link link">Potion of Sustenance</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7001" data-url="7001" class="tooltip-link link">Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13005" data-url="13005" class="tooltip-link link">Iron Ration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>) (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 


else



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15025" data-url="15025" class="tooltip-link link">Spell: Pillage Enchantment</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15033" data-url="15033" class="tooltip-link link">Spell: Brilliance</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15032" data-url="15032" class="tooltip-link link">Spell: Plague</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15623" data-url="15623" class="tooltip-link link">Spell: Minor Conjuration: Air</a>) (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 


elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/13226" data-url="13226" class="tooltip-link link">Runner Pouch</a>) then


>**General Jyleel says:** So, you succeeded in stopping a Crushbone runner! That is good. Now take this as reward. Keep up your fine work. The people of Felwithe are grateful.


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+5</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+5</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+3</span>)


if(math.random(100) > 10) then 



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_684.png" alt="" /> <a
                                href="/item/13003" data-url="13003" class="tooltip-link link">Small Lantern</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_728.png" alt="" /> <a
                                href="/item/13004" data-url="13004" class="tooltip-link link">Large Lantern</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_599.png" alt="" /> <a
                                href="/item/14013" data-url="14013" class="tooltip-link link">Potion of Sustenance</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7001" data-url="7001" class="tooltip-link link">Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13005" data-url="13005" class="tooltip-link link">Iron Ration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>) (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 


else



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15025" data-url="15025" class="tooltip-link link">Spell: Pillage Enchantment</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15033" data-url="15033" class="tooltip-link link">Spell: Brilliance</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15032" data-url="15032" class="tooltip-link link">Spell: Plague</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15623" data-url="15623" class="tooltip-link link">Spell: Minor Conjuration: Air</a>) (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 



elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18840" data-url="18840" class="tooltip-link link">A Sealed Letter</a>) then


>**General Jyleel says:** So, the Teir'Dal are behind the recent advances of the orcs?!! Your news has shed light on their union. It is time to step forth and prove yourself a [faithful paladin of this court].


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+10</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+10</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+7</span>)


 &#127873; **You receive:** 0 (+1000 exp)

 

elseif **Faction** >= Amiable +100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/12330" data-url="12330" class="tooltip-link link">A Large Locked Crate</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_920.png" alt="" /> <a
                                href="/item/12329" data-url="12329" class="tooltip-link link">Blue Orc Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/13227" data-url="13227" class="tooltip-link link">Black Heart</a>) then 


>**General Jyleel says:** A noble deed has been done and the alliance of evil has been stalled. I present you with the falchion of the Koada\`Vie. You are now an honorable member of our order. Hail Felwithe, and may you defender her with honor.


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+50</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+50</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/5379" data-url="5379" class="tooltip-link link">Falchion of the KoadaVie</a> (+1500 exp)

 

**This NPC *should* return incorrect items given.**
;


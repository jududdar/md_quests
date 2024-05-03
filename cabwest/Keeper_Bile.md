# Keeper Bile


## Dialog

**You say:** `hail`



>*Keeper Bile bows before you as a gesture of kindness and respect. 'Greetings. I am Bile, Keeper of the Apprentice Ranks. My knowledge is that of the first circle of necromancy. I was once a great necromancer, but now i have a greater calling to protect the words of Kotiz. I also Conduct many tests to ensure the spells are deciphered correctly. I am in need of an apprentice to [collect components.]*

**You say:** `collect components`



if **Faction** >= Amiable then



>*Keeper Bile takes out a tattered scroll and looks upon its words.'Hmm. Yes. I will need the following; One large scorpion pincer, one sabertooth cub canine and two brittle skulls. Bring these to me and I shall pay you and if I have an overscribed spell, I shall give you that also.*


elseif **Faction** >= Indifferent then



>**Keeper Bile says:** No Iksar resident will have anything to do with you!


else



>**Keeper Bile says:** No Iksar resident will have anything to do with you!   Away from here before you find yourself dead.

end



## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12739" data-url="12739" class="tooltip-link link">Brittle Iksar Skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12739" data-url="12739" class="tooltip-link link">Brittle Iksar Skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_807.png" alt="" /> <a
                                href="/item/12659" data-url="12659" class="tooltip-link link">Large Scorpion Pincer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_801.png" alt="" /> <a
                                href="/item/12426" data-url="12426" class="tooltip-link link">Sabertooth Cub Canine</a>) then


>*Keeper Bile tosses the items into a nearby box and reaches into a sack at his feet. He hands you your reward. 'This spell is going to need some major testing. I can always use more of the same components.'*


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+2</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15338" data-url="15338" class="tooltip-link link">Spell: Cavorting Bones</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15344" data-url="15344" class="tooltip-link link">Spell: Clinging Darkness</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15339" data-url="15339" class="tooltip-link link">Spell: Coldlight</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15340" data-url="15340" class="tooltip-link link">Spell: Disease Cloud</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15225" data-url="15225" class="tooltip-link link">Spell: Endure Cold</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15229" data-url="15229" class="tooltip-link link">Spell: Fear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15346" data-url="15346" class="tooltip-link link">Spell: Grim Aura</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15491" data-url="15491" class="tooltip-link link">Spell: Leering Corpse</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15502" data-url="15502" class="tooltip-link link">Spell: Lifespike</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15341" data-url="15341" class="tooltip-link link">Spell: Lifetap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15342" data-url="15342" class="tooltip-link link">Spell: Locate Corpse</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15347" data-url="15347" class="tooltip-link link">Spell: Numb the Dead</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15348" data-url="15348" class="tooltip-link link">Spell: Poison Bolt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15331" data-url="15331" class="tooltip-link link">Spell: Reclaim Energy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15221" data-url="15221" class="tooltip-link link">Spell: Sense the Dead</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15343" data-url="15343" class="tooltip-link link">Spell: Siphon Strength</a>) (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

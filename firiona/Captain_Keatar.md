# Captain Keatar


## Dialog

**You say:** `hail`



>**Captain Keatar says:** Hail! Beware of the [goblin raiders] roaming the plains outside of Firiona Vie. They ahve caused much trouble and continue to assault this outpost.

**You say:** `goblin raider`



>**Captain Keatar says:** The goblin raiders have been quite a nuisance to my trackers. I implore you to aid my men and lessen teh presence of the vile beasts. Bring me proof that you ahve taken at least four of these raiders down. You shall earn the respect of this outpost and insure your own well-being.

**You say:** `goblin battlemaster`



if **Faction** >= Amiable then





>**Captain Keatar says:** The goblin battlemasters are formidable fighters.  They have defeated many of the patrols I sent into the plains.  Bring me proof of four of these fallen goblins and I shall reward you with a piece of Faydark ringmail armor.




elseif **Faction** >= Indifferent then



>**Captain Keatar says:** I cannot trust you fully.  When you have performed more deeds in the name of the Union of Vie, then and only then shall I trust you.


else



>**Captain Keatar says:** You are no ally of the Union of Vie!  Leave my sight before I incarcerate you.

end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/12922" data-url="12922" class="tooltip-link link">Red Headband</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/12922" data-url="12922" class="tooltip-link link">Red Headband</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/12922" data-url="12922" class="tooltip-link link">Red Headband</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/12922" data-url="12922" class="tooltip-link link">Red Headband</a>) then


>**Captain Keatar says:** You serve this outpost well. Here is a small reward. You should try to hunt down [goblin battlemasters]. I have very few resources to send into the plains to track them down. Perhaps you can help us.


Your faction standing with [Inhabitants of Firiona Vie](/faction/248) got better (<span class='text-success'>+5</span>)


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+3</span>)


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+3</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Pirates of Gunthak](/faction/313) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** 0 (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 8 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_620.png" alt="" /> <a
                                href="/item/12923" data-url="12923" class="tooltip-link link">Goblin Bracer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_620.png" alt="" /> <a
                                href="/item/12923" data-url="12923" class="tooltip-link link">Goblin Bracer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_620.png" alt="" /> <a
                                href="/item/12923" data-url="12923" class="tooltip-link link">Goblin Bracer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_620.png" alt="" /> <a
                                href="/item/12923" data-url="12923" class="tooltip-link link">Goblin Bracer</a>) then


>**Captain Keatar says:** Good work! Please accept this piece of armor. It was crafted in Felwithe for the swiftly moving rangers of this outpost.


Your faction standing with [Inhabitants of Firiona Vie](/faction/248) got better (<span class='text-success'>+10</span>)


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+6</span>)


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+6</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Pirates of Gunthak](/faction/313) got worse (<span class='text-danger'>-2</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_625.png" alt="" /> <a
                                href="/item/12924" data-url="12924" class="tooltip-link link">Faydark Ringmail Coif</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_627.png" alt="" /> <a
                                href="/item/12925" data-url="12925" class="tooltip-link link">Faydark Ringmail Collar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_538.png" alt="" /> <a
                                href="/item/12926" data-url="12926" class="tooltip-link link">Faydark Ringmail Coat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_769.png" alt="" /> <a
                                href="/item/12927" data-url="12927" class="tooltip-link link">Faydark Ringmail Mantle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_562.png" alt="" /> <a
                                href="/item/12928" data-url="12928" class="tooltip-link link">Faydark Ringmail Skirt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_543.png" alt="" /> <a
                                href="/item/12929" data-url="12929" class="tooltip-link link">Faydark Ringmail Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_620.png" alt="" /> <a
                                href="/item/12930" data-url="12930" class="tooltip-link link">Faydark Ringmail Bracer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_526.png" alt="" /> <a
                                href="/item/12931" data-url="12931" class="tooltip-link link">Faydark Ringmail Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_540.png" alt="" /> <a
                                href="/item/12932" data-url="12932" class="tooltip-link link">Faydark Ringmail Pants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_545.png" alt="" /> <a
                                href="/item/12933" data-url="12933" class="tooltip-link link">Faydark Ringmail Boots</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 8 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

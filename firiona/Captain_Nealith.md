# Captain Nealith


## Dialog

**You say:** `Hail`



>**Captain Nealith says:** Hail. adventurer!!  Stand tall and fight for the forest folk and all good races of Norrath. We shall claim this land for the kingdom of Thex!  My warriors shall not fail.  Already we patrol deep in the wilds of Kunark.  We welcome all mercenaries and urge adventurers to [join the defense of the outpost].


e.self:DoAnim(60);

**You say:** `join the defense`



e.self:Say("I salute you!!  Join the hunt.  Reports from the front line indicate a rise in the drolvarg
population.  Abandon your fear and slay these beasts for the greater good.  Already. they have taken far too many lives. even my sibling's!!  I shall pay you your wages upon the return of four drolvarg teeth.");


e.self:DoAnim(67);

**You say:** `sibling`



>*Captain Nealith appears saddened by the mention of his sibling. 'My brother Marltek has been missing for quite some time. I found coarse Drolvarg hair inside his tent which leads me to believe he has become a meal for the dogs. CURSE THE EVIL DOGS!! I shall see them all dead!!'*


e.self:DoAnim(28);
end



## Turn-Ins



local text = "holds the canine in his palm. 'Good work, but you will have to slay more than this to earn your wages.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_801.png" alt="" /> <a
                                href="/item/12977" data-url="12977" class="tooltip-link link">A Canine</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_801.png" alt="" /> <a
                                href="/item/12977" data-url="12977" class="tooltip-link link">A Canine</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_801.png" alt="" /> <a
                                href="/item/12977" data-url="12977" class="tooltip-link link">A Canine</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_801.png" alt="" /> <a
                                href="/item/12977" data-url="12977" class="tooltip-link link">A Canine</a>) then


>*Captain Nealith tosses the teeth into a very large cask full of similar teeth. 'Fine work, Soandso. I wish all my own troops showed the same tenacity. I salute you. This will keep you well fed during your long patrols. Use your wages to better equip yourself. Continue the fight!! The General is pleased.'*





Your faction standing with [Inhabitants of Firiona Vie](/faction/248) got better (<span class='text-success'>+5</span>)


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+3</span>)


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+3</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Pirates of Gunthak](/faction/313) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1145.png" alt="" /> <a
                                href="/item/13155" data-url="13155" class="tooltip-link link">Elven Trail Mix</a> (+10000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18076" data-url="18076" class="tooltip-link link">blood soaked note</a>) then 


>*Captain Nealith nearly faints after reading the letter. 'Dear Marltek!! I shall miss you. There is more evil in this land!! Madness beyond description. Thank you Soandso. You put my soul at ease and give me new direction. Please accept my brothers blade. He found it in the wilds. May you use it to slay many Drolvarg!!'*


Your faction standing with [Inhabitants of Firiona Vie](/faction/248) got better (<span class='text-success'>+5</span>)


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+3</span>)


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+3</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Pirates of Gunthak](/faction/313) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1177.png" alt="" /> <a
                                href="/item/12978" data-url="12978" class="tooltip-link link">Glaive of Marltek</a> (+25580 exp)

**You receive coin:** 4 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

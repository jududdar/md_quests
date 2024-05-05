# Capt Linarius



[Capt Linarius](/npc/13053) is a level 45 Human Warrior that spawns in [Northern Plains of Karana](/zone/13).



## Dialog

**You say:** `hail`



>**Capt Linarius says:** Hail, traveler! You are free to rest within this keep or within any of my towers along the roads to Qeynos. My guards shall keep watch over you. While you tread upon the roads, be warned that there are [local dangers] as well as rumors of [corrupt guards].

**You say:** `corrupt guards`



>**Capt Linarius says:** I have heard rumors of dissension among my guards. I will reward any fine resident for the death of these traitorous guards. If you find you must kill one, bring his guard bracelet back to me. I cannot allow such men among my guards. Be sure they are corrupt, or I shall have your head as well.

**You say:** `local dangers`



>**Capt Linarius says:** My guards report daily to me of dangers in the plains. Lately, they've been telling me of rumors of [Lord Grimrot].

**You say:** `lord grimrot`



>**Capt Linarius says:** My guards have heard rumors of this Lord Grimrot. It is said that he is a powerful shadowknight who is raising an army of undead. Such things should be reported to the Temple of Life. Journey to Qeynos and speak with Camlend Serbold. Tell him of Lord Grimrot.
end



## Turn-Ins



local cgb =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_620.png" alt="" /> <a
                                href="/item/13303" data-url="13303" class="tooltip-link link">Guard Bracelet</a>}


if **Faction** >= Apprehensive and (cgb > 0))  then 


repeat


>**Capt Linarius says:** What a pity. Such a promising soldier. I thank you for ridding us of this corruption and offer you this as a reward. It is nothing more than junk which littered the roadways of the Plains of Karana. I hope you can find a use for it.





Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+10</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5369" data-url="5369" class="tooltip-link link">Bunker Battle Blade</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_542.png" alt="" /> <a
                                href="/item/9002" data-url="9002" class="tooltip-link link">Round Shield</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/4209" data-url="4209" class="tooltip-link link">Bronze Bracers</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5028" data-url="5028" class="tooltip-link link">Bronze Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5034" data-url="5034" class="tooltip-link link">Bronze Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2248" data-url="2248" class="tooltip-link link">Reinforced Boots</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_596.png" alt="" /> <a
                                href="/item/5310" data-url="5310" class="tooltip-link link">Tentacle Whip</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_676.png" alt="" /> <a
                                href="/item/9003" data-url="9003" class="tooltip-link link">Targ Shield</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7350" data-url="7350" class="tooltip-link link">Fine Steel Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5350" data-url="5350" class="tooltip-link link">Fine Steel Long Sword</a>) (+50000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_647.png' width='14' height='14'/> 



cgb = cgb - 1;


until cgb == 0



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_620.png" alt="" /> <a
                                href="/item/13304" data-url="13304" class="tooltip-link link">Guard Bracelet</a>) then 


>**Capt Linarius says:** You fool! You have killed a fine and outstanding guard. You shall pay dearly for this!


**Capt Linarius attacks you.**

**This NPC *should* return incorrect items given.**

end
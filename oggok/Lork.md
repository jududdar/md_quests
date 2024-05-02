# Lork
## Dialog

**You say:** `hail`



>**Lork says:** You Soandso. We hear of you. We need help. You [help Crakneks] or you [help self]?

**You say:** `help crakneks`



if **Faction** >= Amiable then 



>**Lork says:** Ha!! We hear of great adventurer. You?!! Me no think so. You prove self to Crakneks before you help us. Go to Innoth.. Innotu.. Innooth.. Arghh!! You go to outside Oggok. Find fat alligator bit Lork brother in two. Bring brother, Nork, body back. Then me know you strong.


elseif **Faction** >= Indifferent then




>**Lork says:** You help Crakneks more. Helps Horgus you must.  Den we trusts yoo!


else



>**Lork says:** Me smell the blood of Craknek enemy. Hey! It you!



**You say:** `help self`



>**Lork says:** You help self to leave Oggok before me bash you. We no need cowards.

**You say:** `uglan`



if **Faction** >= Amiable then 



>**Lork says:** Uglan brave warrior of Oggok. He now in Neriak. Work for dark elves. He NO LIKE dark elves!! He work because we make him. He spy for Crakneks.


elseif **Faction** >= Indifferent then




>**Lork says:** You help Crakneks more. Helps Horgus you must.  Den we trusts yoo!


else



>**Lork says:** Me smell the blood of Craknek enemy. Hey! It you!



**You say:** `help self`



>**Lork says:** You help self to leave Oggok before me bash you. We no need cowards.
end

## Turn-Ins



local text = "This one dead. Where other? Lork say Crushbone heart and Oggok heart.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_614.png" alt="" /> <a
                                href="/item/20523" data-url="20523" class="tooltip-link link">Intricate Toothed Ring</a>) then


>**Lork says:** Ay danks. Take dis to Uglan.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_708.png" alt="" /> <a
                                href="/item/16547" data-url="16547" class="tooltip-link link">A Stein</a> 

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_918.png" alt="" /> <a
                                href="/item/13356" data-url="13356" class="tooltip-link link">Ogre Arm</a>) then


>**Lork says:** Ahhh!! Boohoohoo. Nork!! That you arm. Me will take care of you now. Thank you for killing gator. You must be strong. Now you help Crakneks. We hear.. ohh, poor Nork, we hear trouble begins. Find ogre warrior [Uglan]. Give him this. It broken. He know where you from. Go. Nork.. Poor Nork.


Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+10</span>)


Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+1</span>)


Your faction standing with [Green Blood Knights](/faction/261) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_708.png" alt="" /> <a
                                href="/item/13357" data-url="13357" class="tooltip-link link">A Cracked Stein</a> (+500 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18840" data-url="18840" class="tooltip-link link">A Sealed Letter</a>) then


>**Lork says:** What this!! So, dark elves think they can bash ogres. Replace with blue orcs. Dumb Zulort friend with dark elf ambassador in Oggok. We kill him. We kill Crushbone dark elf ambassador also. This slow down plan. We need a hero. Me guess you do. You go. Go bring Lork both Crushbone and Oggok dark elf hearts. Then you be hero.


Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+10</span>)


Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+1</span>)


Your faction standing with [Green Blood Knights](/faction/261) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5030" data-url="5030" class="tooltip-link link">Bronze Two Handed Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6021" data-url="6021" class="tooltip-link link">Bronze Two Handed Hammer</a>) (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 7 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_797.png" alt="" /> <a
                                href="/item/13358" data-url="13358" class="tooltip-link link">Black Heart</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/13227" data-url="13227" class="tooltip-link link">Black Heart</a>) then


>**Lork says:** That show dark elves who strongest. Me hope you kill many blue orcs. You Craknek Hero now. You take this. It mine. Hero reward. You great ogre now. Smash best.


Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+25</span>)


Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+3</span>)


Your faction standing with [Green Blood Knights](/faction/261) got worse (<span class='text-danger'>-3</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_581.png" alt="" /> <a
                                href="/item/13359" data-url="13359" class="tooltip-link link">Gatorsmash Maul</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_708.png" alt="" /> <a
                                href="/item/13355" data-url="13355" class="tooltip-link link">A Crude Stein</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2136" data-url="2136" class="tooltip-link link">Large Patchwork Boots</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2130" data-url="2130" class="tooltip-link link">Large Patchwork Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2135" data-url="2135" class="tooltip-link link">Large Patchwork Pants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2132" data-url="2132" class="tooltip-link link">Large Patchwork Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2128" data-url="2128" class="tooltip-link link">Large Patchwork Tunic</a>) (+500 exp)

 

**This NPC *should* return incorrect items given.**






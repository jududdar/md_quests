# Regren



[Regren](/npc/54093) is a level 61 Wood Elf GM Warrior that spawns in [Greater Faydark](/zone/54).



## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Regren says:** Welcome, warrior! Show the Emerald Warriors your mettle and bring me a ruined wolf pelt, some bat fur, some bone chips, and a spiderling eye from the depths of Greater Faydark. If you succeed, my admiration and a reward will be yours. To battle!


elseif( **Faction is** == Indifferent) then



>**Regren says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Regren says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins



local text = "Impressive, do you have the rest?";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18782" data-url="18782" class="tooltip-link link">Recruitment Letter</a>) then 


>**Regren says:** Welcome to the Emerald Warriors. Hmmm, you have a lot of training to do, so let's get started right away. Here's our guild tunic, represent us well, young Soandso.


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+100</span>)


Your faction standing with [Indigo Brotherhood](/faction/270) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Merchants of Felwithe](/faction/325) got better (<span class='text-success'>+10</span>)


Your faction standing with [Kelethin Merchants](/faction/276) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13533" data-url="13533" class="tooltip-link link">Old Green Tunic*</a> (+20 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_553.png" alt="" /> <a
                                href="/item/13782" data-url="13782" class="tooltip-link link">Ruined Wolf Pelt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_885.png" alt="" /> <a
                                href="/item/13253" data-url="13253" class="tooltip-link link">Spiderling Eye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_792.png" alt="" /> <a
                                href="/item/13069" data-url="13069" class="tooltip-link link">Bat Fur</a>) then


>**Regren says:** Fine work! You are on your way to becoming an adequate combatant.


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+10</span>)


Your faction standing with [Indigo Brotherhood](/faction/270) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Kelethin Merchants](/faction/276) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Felwithe](/faction/325) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/5013" data-url="5013" class="tooltip-link link">Rusty Short Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5014" data-url="5014" class="tooltip-link link">Rusty Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_579.png" alt="" /> <a
                                href="/item/5015" data-url="5015" class="tooltip-link link">Rusty Scythe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_605.png" alt="" /> <a
                                href="/item/5016" data-url="5016" class="tooltip-link link">Rusty Broad Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5019" data-url="5019" class="tooltip-link link">Rusty Long Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5020" data-url="5020" class="tooltip-link link">Rusty Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5021" data-url="5021" class="tooltip-link link">Rusty Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_577.png" alt="" /> <a
                                href="/item/5022" data-url="5022" class="tooltip-link link">Rusty Bastard Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5023" data-url="5023" class="tooltip-link link">Rusty Two Handed Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/5024" data-url="5024" class="tooltip-link link">Rusty Halberd</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/5025" data-url="5025" class="tooltip-link link">Rusty Two Handed Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/5042" data-url="5042" class="tooltip-link link">Tarnished Short Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5043" data-url="5043" class="tooltip-link link">Tarnished Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_605.png" alt="" /> <a
                                href="/item/5044" data-url="5044" class="tooltip-link link">Tarnished Broad Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5045" data-url="5045" class="tooltip-link link">Tarnished Long Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5046" data-url="5046" class="tooltip-link link">Tarnished Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5047" data-url="5047" class="tooltip-link link">Tarnished Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_577.png" alt="" /> <a
                                href="/item/5048" data-url="5048" class="tooltip-link link">Tarnished Bastard Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_579.png" alt="" /> <a
                                href="/item/5049" data-url="5049" class="tooltip-link link">Tarnished Scythe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5070" data-url="5070" class="tooltip-link link">Tarnished Two Handed Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/5071" data-url="5071" class="tooltip-link link">Tarnished Two Handed Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/6011" data-url="6011" class="tooltip-link link">Rusty Mace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6013" data-url="6013" class="tooltip-link link">Rusty Two Handed Hammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6014" data-url="6014" class="tooltip-link link">Rusty Warhammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6015" data-url="6015" class="tooltip-link link">Rusty Flail</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6016" data-url="6016" class="tooltip-link link">Rusty Morning Star</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/6030" data-url="6030" class="tooltip-link link">Tarnished Mace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6031" data-url="6031" class="tooltip-link link">Tarnished Warhammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6032" data-url="6032" class="tooltip-link link">Tarnished Flail</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6033" data-url="6033" class="tooltip-link link">Tarnished Morning Star</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7007" data-url="7007" class="tooltip-link link">Rusty Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_762.png" alt="" /> <a
                                href="/item/7008" data-url="7008" class="tooltip-link link">Rusty Rapier</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_776.png" alt="" /> <a
                                href="/item/7009" data-url="7009" class="tooltip-link link">Rusty Spear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/7010" data-url="7010" class="tooltip-link link">Rusty Shortened Spear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7021" data-url="7021" class="tooltip-link link">Tarnished Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/7022" data-url="7022" class="tooltip-link link">Tarnished Shortened Spear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_762.png" alt="" /> <a
                                href="/item/7023" data-url="7023" class="tooltip-link link">Tarnished Rapier</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_776.png" alt="" /> <a
                                href="/item/7024" data-url="7024" class="tooltip-link link">Tarnished Spear</a>) (+1000 exp)

 

**This NPC *should* return incorrect items given.**



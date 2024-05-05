# Conium Darkblade



[Conium Darkblade](/npc/70002) is a level 40 Dwarf Shopkeeper that spawns in [Dagnor's Cauldron](/zone/70).



## Dialog

**You say:** `hail`



>**Conium Darkblade says:** You seek Conium Darkblade, do you? Often I am here. To test my [wasp poison], yes. Fewer aqua gobs there now are. Ha! A true rogue am I with no leader or guild. Just the wind and shadows and much treasure to be had.

**You say:** `wasp poison`



>**Conium Darkblade says:** Giant wasp venom made from the giant wasp venom sacs. An interest in poison we share? Need the insect venom, you do. It comes not cheap. My time is precious, my talent supreme... 30 Gold is my price and you must also provide me three giant wasp venom sacs.

**You say:** `who once owned it`



>**Conium Darkblade says:** The human who gave me the axe remains nameless. We were separated during the battle. If he ever got out of there with all his gold, I do not know. The only clue I know of is the axe itself. The words 'Top of the World' were once printed on its handle.

**You say:** `top of the world`



>**Conium Darkblade says:** High in the pass you can find Top of the World. It sits near the highest bridge. It is one of the newest additions to our community. It specializes in imported items for adventuring.
end



## Turn-Ins



local text = "There shall be no wasp venom until three giant wasp venom sacs and 30 gold coins cross my palm."


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/13260" data-url="13260" class="tooltip-link link">Giant Wasp Venom Sac</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/13260" data-url="13260" class="tooltip-link link">Giant Wasp Venom Sac</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/13260" data-url="13260" class="tooltip-link link">Giant Wasp Venom Sac</a>,gold = 30) then


>**Conium Darkblade says:** Take the giant wasp venom. Good or evil it is not. That is up to you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_808.png" alt="" /> <a
                                href="/item/14024" data-url="14024" class="tooltip-link link">Giant Wasp Venom</a> (+500 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18955" data-url="18955" class="tooltip-link link">a sealed note</a>) then


>**Conium Darkblade says:** So Lon has sworn allegiance to a temple. What a fool, but he is a skilled fool. My word is my bond and if he asks for the gem, then so be it. Unfortunately I traded it for a much-needed axe. It was in the middle of a dungeon and... well, that is a long story. If you want to get the gem, take this axe back to the [one who once owned it].


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/12366" data-url="12366" class="tooltip-link link">never stop chopping</a> 

 

**This NPC *should* return incorrect items given.**
;

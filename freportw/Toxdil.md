# Toxdil


## Dialog

**You say:** `hail`



>**Toxdil says:** Correct. Toxdil is my name. No last name. I swear allegiance to no house nor guild. What brings you down here? Perhaps you seek my [deadly liquid], perhaps not. Whatever your reasons, I warn you to keep an eye out for the militia. They have begun to patrol the sewers.

**You say:** `deadly liquid`



>**Toxdil says:** The deadly liquid I offer to rogues is called snake venom. I will be glad to make it for you, but first you must supply me with two snake venom sacs and my fee of 20 gold pieces. You may find the sacs upon the giant snakes of the Commonlands.

**You say:** `gem of righteousness`



>**Toxdil says:** That gem is worthless!! If you want it, you can have it. Oh, but I forgot! I sold it to some gem merchant. I can't seem to remember her name, but she paid highly for it. Ha!! Imagine that. Worthless hunk of crystal. Do not bother looking for it.
end



## Turn-Ins



local text = "I require two snake venom sacs and my fee of 20 gold coins before I shall create the snake venom."


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/12353" data-url="12353" class="tooltip-link link">A Sparkling Sapphire</a>) then


>**Toxdil says:** The gem!! I would notice it's sparkle anywhere!! I cannot believe you are handing it back to me!! What a fool. Here you are fool. You can have this worthless key now.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1077.png" alt="" /> <a
                                href="/item/12351" data-url="12351" class="tooltip-link link">A Tiny Key</a> (+15000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_818.png" alt="" /> <a
                                href="/item/14017" data-url="14017" class="tooltip-link link">A Snake Venom Sac</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_818.png" alt="" /> <a
                                href="/item/14017" data-url="14017" class="tooltip-link link">A Snake Venom Sac</a>,gold = 20) then


>**Toxdil says:** Here is your snake venom. May you... shall we say... apply it to good use.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_806.png" alt="" /> <a
                                href="/item/14016" data-url="14016" class="tooltip-link link">Snake Venom</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**

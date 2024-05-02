# Strandar Pinemist
## Dialog

**You say:** `hail`



>**Strandar Pinemist says:** Greetings, young one. Are you a [child of the trees]?

**You say:** `child of the trees`



>**Strandar Pinemist says:** Then you are welcome in my presence. I shall call forth some loyal children if you but speak the name. Will or Fenalla will serve you well.

**You say:** `will`



>**Strandar Pinemist says:** Please read this tome. It will explain how Will Treewalker is able to assist. When you are finished, please return it to me. We have but a single copy of such a tome, for which a tree gave its life.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18528" data-url="18528" class="tooltip-link link">The Long Walk</a>

**You say:** `fenalla`



>**Strandar Pinemist says:** Please read this tome. It wll explain what Fenalla Moonshadow can assist you with. When you are finished, please return this to me. We have but a single copy of such a tome in the world, for which a tree gave its life.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18529" data-url="18529" class="tooltip-link link">The Gift</a>
end


## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18528" data-url="18528" class="tooltip-link link">The Long Walk</a>) then 


>**Strandar Pinemist says:** Welcome, Will Treewalker.


**Spawn NPC:**  [Will Treewalker](/npc/71099) at (**y:** 1311.4, **x:** 563)


**Strandar Pinemist despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18529" data-url="18529" class="tooltip-link link">The Gift</a>) then 


>**Strandar Pinemist says:** Welcome, Fenalla Moonshadow.


**Spawn NPC:**  [Fenalla Moonshadow](/npc/71086) at (**y:** 1329.3, **x:** 562.5)


**Strandar Pinemist despawns.**

**This NPC *should* return incorrect items given.**

end
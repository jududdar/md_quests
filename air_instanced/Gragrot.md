# Gragrot
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Gragrot says:** Hail! So you think you are a mighty Knight of Shadows? We must test these skills. Are you ready to begin the test?

**You say:** `ready`



>**Gragrot says:** Great, let us waste no more time! I offer to you three challenges: Bash, smash, or slash. What do you wish to be tested in?

**You say:** `bash`




>**Gragrot says:** Gragrot like bashin.  Gragrot say you like bashin too!  Give Gragrot an ebon tessera, a sphinx eye opal, and a finely crafted amulet.  Gragrot then give you amulet of the sphinx eye.

**You say:** `smash`




>**Gragrot says:** Gragrot wants you smashin.  Smash, smash, and return a copper disk, a small sapphire, and a silvery ring.  Then Gragrot give you crimson ring of the djinni.

**You say:** `slash`




>**Gragrot says:** Gragrot see you is powerful, but Gragrot wonders if you is good at Slashin. Gragrot says return with a Diaphanous Globe, a piece of dried leather, and a Finely Woven Cloth Belt. Gragrot then give you pegasus hide belt.
end

## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/20929" data-url="20929" class="tooltip-link link">Ebon Tessera</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_959.png" alt="" /> <a
                                href="/item/20997" data-url="20997" class="tooltip-link link">Sphinx Eye Opal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_753.png" alt="" /> <a
                                href="/item/20998" data-url="20998" class="tooltip-link link">Finely Crafted Amulet</a>) then 



>**Gragrot says:** You is powerful! Take this!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_753.png" alt="" /> <a
                                href="/item/27705" data-url="27705" class="tooltip-link link">Amulet of the Sphinx Eye</a> (+100000 exp)

 


**Gragrot despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_647.png" alt="" /> <a
                                href="/item/20936" data-url="20936" class="tooltip-link link">Copper Disc</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/20999" data-url="20999" class="tooltip-link link">Small Sapphire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_675.png" alt="" /> <a
                                href="/item/20700" data-url="20700" class="tooltip-link link">Silvery Ring</a>) then 


>**Gragrot says:** You is powerful! Take this!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_872.png" alt="" /> <a
                                href="/item/27706" data-url="27706" class="tooltip-link link">Crimson Ring of the Djinni</a> (+100000 exp)

 


**Gragrot despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_947.png" alt="" /> <a
                                href="/item/20943" data-url="20943" class="tooltip-link link">Diaphanous Globe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_532.png" alt="" /> <a
                                href="/item/20701" data-url="20701" class="tooltip-link link">Dried Leather</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1124.png" alt="" /> <a
                                href="/item/20702" data-url="20702" class="tooltip-link link">Finely Woven Cloth Belt</a>) then 


>**Gragrot says:** Take this belt with the blessing of Veeshan, Soandso.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_560.png" alt="" /> <a
                                href="/item/2704" data-url="2704" class="tooltip-link link">Pegasus-Hide Belt</a> (+100000 exp)

 


**Gragrot despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Gragrot despawns.**




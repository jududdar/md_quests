# Joyce




## Dialog

if **Faction** >= Indifferent then



**You say:** `hail`




>**Joyce says:** I am Joyce of the Temple of Solusek Ro. I am the guardian of four of the items of the elementalist. If you are a magician, ask me about the [Robe of the Elements], the [Clay Bracelet], the [Earthen Boots] or the [Circlet of Mist]


**You say:** `mist`




>**Joyce says:** The Circlet of Mist is a beautiful hoop that would look good atop your head. It produces a fine gleam, and is known to increase your mental power. Are you [interested in the circlet]?


**You say:** `circlet`




>**Joyce says:** I will construct for you a Circlet of Mist, but I will need you to bring me the proper components. Bring me a globe of mist from a festering hag in the Estate of Unrest, a watery ring from an aqua goblin tidal lord in Dagnor's Cauldron, a ring of Evoluoy from one of the larger alligators in the Temple of Cazic-Thule and a sapphire. Bring me these components, and I will construct for you a Circlet of Mist.


**You say:** `clay`




>**Joyce says:** The clay bracelet is a wonderful piece of jewelry to wear on your wrist. It provides fine protection, enhances your resistance to magic, and lets you call forth a mystic eye to help you in your travels. Are you [interested in the bracelet]?


**You say:** `bracelet`




>**Joyce says:** I will make you a clay bracelet, but you will need to bring me the proper components. I will need each of the four runes of clay. Three of them can be found in the Rathe Mountains, held by gnomish necromancers. The fourth one is somewhere in the Ocean of Tears, held by a goblin headmaster. Bring me these four components, and I will make you a clay bracelet.


**You say:** `earthen`




>**Joyce says:** Earthen Boots are a fine adornment for the feet of any Magician. They have a wonderful brown color, and are known to enhance the stamina of any Magician who wears them. As an added bonus, animals do not tend to notice those who wear Earthen Boots. Are you [interested in the boots]?


**You say:** `boots`




>**Joyce says:** I will cobble you a pair of earthen boots, but you will need to bring me the proper components. I need a stone marker from a glyphed guard in Castle Mistmoore, a heart of stone from the stone skeleton near Lake Rathe, soiled boots from a froglok tonta knight in the caverns of Guk and a cat's eye agate. Bring me these four items, and I will cobble you a pair of earthen boots.


**You say:** `elements`




>**Joyce says:** The Robe of the Elements is a fine cloak for a Magician. It provides protection from the elements, protection from melee attacks and aids the Magician with her focus. Are you [interested in the robe]?


**You say:** `robe`




>**Joyce says:** I will make for you the Robe of the Elements, but I will be needing the proper components. I will be needing a fire goblin skin, a frost goblin skin, a Twice-Woven Cloak which can be found on Faerie Guards in the Faydark, and a scroll of elemental armor. Return to me with these items and I will craft your robe.


else


**Joyce says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end



## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";





if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10545" data-url="10545" class="tooltip-link link">Globe of Mist</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_615.png" alt="" /> <a
                                href="/item/10547" data-url="10547" class="tooltip-link link">Ring of Evoluoy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10034" data-url="10034" class="tooltip-link link">Sapphire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_616.png" alt="" /> <a
                                href="/item/10546" data-url="10546" class="tooltip-link link">Water Ring</a>) then


>**Joyce says:** Astounding! You found all four components that I need to make the Circlet of Mist. Wasn't that ring annoying ? I always find goblins hard to deal with. Well done! Take this circlet with my complements.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1124.png" alt="" /> <a
                                href="/item/2358" data-url="2358" class="tooltip-link link">Circlet of Mist</a> (+500 exp)

 



elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10539" data-url="10539" class="tooltip-link link">Rune of Clay</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10542" data-url="10542" class="tooltip-link link">Rune of Clay</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10540" data-url="10540" class="tooltip-link link">Rune of Clay</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10541" data-url="10541" class="tooltip-link link">Rune of Clay</a>) then


>**Joyce says:** One, two, three.. all four runes of clay! I knew you looked competent. I am very impressed! Please take the Clay Bracelet that you have earned.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_505.png" alt="" /> <a
                                href="/item/2359" data-url="2359" class="tooltip-link link">Clay Bracelet</a> (+500 exp)

 



elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10543" data-url="10543" class="tooltip-link link">A Stone Marker</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_955.png" alt="" /> <a
                                href="/item/10026" data-url="10026" class="tooltip-link link">Cat's Eye Agate</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/10544" data-url="10544" class="tooltip-link link">Heart of Stone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_525.png" alt="" /> <a
                                href="/item/2363" data-url="2363" class="tooltip-link link">Soiled Boots</a>) then


>**Joyce says:** Marker, heart, boots and gem. All four items that I need to cobble earthen boots for you. Well done! Take these boots, and may they serve you well!


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2357" data-url="2357" class="tooltip-link link">Earthen Boots</a> (+500 exp)

 



elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/2361" data-url="2361" class="tooltip-link link">Fire Goblin Skin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_835.png" alt="" /> <a
                                href="/item/2362" data-url="2362" class="tooltip-link link">Frost Goblin Skin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_931.png" alt="" /> <a
                                href="/item/1356" data-url="1356" class="tooltip-link link">Robe of the Elements</a> (+500 exp)

 
end







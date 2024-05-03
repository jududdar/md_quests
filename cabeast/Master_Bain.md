# Master Bain


## Dialog

**You say:** `Hail`



>**Master Bain says:** Welcome.  Who has [sent] you to me?

**You say:** `Grand Master Glox`



if **Faction** >= Amiable then



>**Master Bain says:** So Grand Master Glox has sent you?  You must be new to the court.  We are of the Swifttail caste as are you.  Under the guidance of masters such as I. You will forge your body into a weapon of pure destruction.  Do not bother the Grand Master.  He is in constant meditation and is bothered with only the most paramount of concerns.  Are you [ready to train]?


elseif **Faction** >= Indifferent then



>**Master Bain says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Bain says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `ready to train`



if **Faction** >= Amiable then



>**Master Bain says:** Then I can offer training in the martial arts as well as other skills.  Please remember to obtain knowledge from our court chronicler.  You shall also begin to aid your brothers and sisters with [menial tasks].  All begin upon the rung of dust and all have done these tasks in order to climb to the next rung.


elseif **Faction** >= Indifferent then



>**Master Bain says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Bain says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `menial tasks`



if **Faction** >= Amiable then



>**Master Bain says:** We have a few menial tasks we require our young members to perform.  Young members must [tailor training bags] for our court.


elseif **Faction** >= Indifferent then



>**Master Bain says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Bain says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `tailor training bags`



if **Faction** >= Amiable then



>**Master Bain says:** Then take this leech husk pouch and fill it with the obvious.  Once done, combine the skins and take the full leech husk pouch to a local tailor by the name of Klok Mugruk.  He is the one who cleans and toughens the husks for us. He shall hand you a ready-made training bag husk.  He will instruct you further.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/17998" data-url="17998" class="tooltip-link link">Leech Husk Pouch</a>


elseif **Faction** >= Indifferent then



>**Master Bain says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Bain says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `master rinmark`



>**Master Bain says:** Seeking Master Rinmark? He has left the Court of Pain. Gone to focus his thoughts on the elements of wind and thunder. I believe he was headed toward the Overthere. That was the last I heard of his trek.
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_789.png" alt="" /> <a
                                href="/item/18468" data-url="18468" class="tooltip-link link">Pale White Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/22923" data-url="22923" class="tooltip-link link">Vine Woven Basket</a>) then


>*Master Bain smiles at your dedication to Cazic Thule and hands you a small gem.*


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+5</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/7881" data-url="7881" class="tooltip-link link">Mark of Clarity</a> (+20000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_789.png" alt="" /> <a
                                href="/item/18467" data-url="18467" class="tooltip-link link">Dim White Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1010.png" alt="" /> <a
                                href="/item/22922" data-url="22922" class="tooltip-link link">Earthenware Bowl</a>) then


>*Master Bain smiles at your dedication to Cazic Thule and hands you a small gem.*


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+5</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/7881" data-url="7881" class="tooltip-link link">Mark of Clarity</a> (+20000 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/12688" data-url="12688" class="tooltip-link link">Monk Training Bag</a>) then 










>**Master Bain says:** We thank you, young " .. e.other:Class() .. ". In exchange for your prompt service, please accept this piece of training armor. Please continue with your training.





Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+5</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_639.png" alt="" /> <a
                                href="/item/4350" data-url="4350" class="tooltip-link link">Sparring Headgear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/4351" data-url="4351" class="tooltip-link link">Sparring Facemask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_643.png" alt="" /> <a
                                href="/item/4352" data-url="4352" class="tooltip-link link">Sparring Collar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/4353" data-url="4353" class="tooltip-link link">Sparring Harness</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_665.png" alt="" /> <a
                                href="/item/4354" data-url="4354" class="tooltip-link link">Sparring Shoulder Pads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_562.png" alt="" /> <a
                                href="/item/4355" data-url="4355" class="tooltip-link link">Sparring Rib Pad</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_670.png" alt="" /> <a
                                href="/item/4356" data-url="4356" class="tooltip-link link">Sparring Arm Guards</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/4357" data-url="4357" class="tooltip-link link">Sparring Grappler Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_631.png" alt="" /> <a
                                href="/item/4358" data-url="4358" class="tooltip-link link">Sparring Shin Guards</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_666.png" alt="" /> <a
                                href="/item/4359" data-url="4359" class="tooltip-link link">Sparring Clogs</a>) (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**






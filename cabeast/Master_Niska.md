# Master Niska


## Dialog

**You say:** `hail`



>*Master Niska bows with elegance and grace. You can see her arms rippling with muscles. 'Greetings. We are the Swifttails. We are the harnessers of the elements. We are the tails of discipline. To achieve rebirth into our caste is a great honor indeed. We can be identified by our adornments. You should display that which we have given you to adorn your arms with pride. You do have your Shackle of Dust, correct?'*

**You say:** `no`



>**Master Niska says:** You dare disgrace us?' She hisses at you. 'If you have truely lost the marking of our caste, you will need to take this note and speak to the Toilmaster immediately. Read it on the way and praise the will of Cazic Thule.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/18271" data-url="18271" class="tooltip-link link">A Ragged Book</a>

**You say:** `yes`



>**Master Niska says:** Very good Broodling. Display your adornment with pride so that the enemies of the Brood may see our might as you rip through the weak will of their ranks. Now be gone from my sight.

**You say:** `shackle of rock`



if **Faction** >= Amiable then



>*Master Niska strikes within inches of your snout with amazing speed. 'The Shackle of Rock is your interest? Then learn well our ways and prepare yourself. If the stone embraces your wrist, you are ready indeed. To complete the second rung you must find for me the [Fists of Talon].'*


elseif **Faction** >= Indifferent then



>**Master Niska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Niska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `fists of talon`



if **Faction** >= Amiable then



>*Master Niska points to the Court Chronicler. 'All that is known of Talon has been chronicled. Should you obtain the fists then you shall hand them to me. This shall earn you the Shackle of Rock.'*


elseif **Faction** >= Indifferent then



>**Master Niska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Niska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `troubles with.* outlander`



if **Faction** >= Amiable then



>**Master Niska says:** It seems Klok Ephmir has encountered an outlander who was hunting the food we lizards enjoy. The legion will not act without proof of this outlanders existence. We were asked by the Baron to find this proof. We shall do this. You shall provide me with the outlanders head and the Shackles of Rock and Stone!!


elseif **Faction** >= Indifferent then



>**Master Niska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Niska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `will be your personal courier`



if **Faction** >= Amiable then



>*Master Niska grabs a tin box resting by her feet. 'Take this to Master Rinmark and be quick about it!!'*



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/12829" data-url="12829" class="tooltip-link link">A Tin Box</a>


elseif **Faction** >= Indifferent then



>**Master Niska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Niska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.

end



## Turn-Ins



local text1 = "Tsk, tsk, tsk. There were more of Talon's Fists than this. Only by gathering all of his fists shall you earn the shackle of rock and bring you closer to the third rung.";

local text2 = "This is not all. Bring me the item this caste seeks and the shackles of stone and rock.";


if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_980.png" alt="" /> <a
                                href="/item/12821" data-url="12821" class="tooltip-link link">An Outlander's Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1235.png" alt="" /> <a
                                href="/item/4192" data-url="4192" class="tooltip-link link">Shackle of Stone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1235.png" alt="" /> <a
                                href="/item/4193" data-url="4193" class="tooltip-link link">Shackle of Rock</a>) then


>**Master Niska says:** Very good!! Here is your Shackle of Copper. The Emperor shall be pleased that I, Mistress Niska, have slain the outlander. Do you have some time? I need someone to be my [personal courier]. Will you?


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/4194" data-url="4194" class="tooltip-link link">Shackle of Copper</a> (+40000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_789.png" alt="" /> <a
                                href="/item/18466" data-url="18466" class="tooltip-link link">Light Grey Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1055.png" alt="" /> <a
                                href="/item/22921" data-url="22921" class="tooltip-link link">Kromdul Bracelet</a>) then


>*Master Niska smiles at your dedication to Cazic Thule and hands you a small gem.*


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+5</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/7881" data-url="7881" class="tooltip-link link">Mark of Clarity</a> (+20000 exp)

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_789.png" alt="" /> <a
                                href="/item/18465" data-url="18465" class="tooltip-link link">Greyed Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_875.png" alt="" /> <a
                                href="/item/22920" data-url="22920" class="tooltip-link link">Ring of the Construct</a>) then


>*Master Niska smiles at your dedication to Cazic Thule and hands you a small gem.*


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+5</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/7881" data-url="7881" class="tooltip-link link">Mark of Clarity</a> (+20000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/18272" data-url="18272" class="tooltip-link link">Rites of Exoneration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/24770" data-url="24770" class="tooltip-link link">Filled Penance Bag</a>) then


>**Master Niska says:** You dare disgrace us?' She hisses at you. 'If you have truly lost the marking of our caste, you will need to take this note and speak to the Toilmaster immediately. Read it on the way and praise the will of Cazic-Thule.


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+100</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+25</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/4190" data-url="4190" class="tooltip-link link">Shackle of Dust</a> (+500 exp)

 


**This NPC *should* return incorrect items given.**



## Signals

>**Master Niska says:** You dare disgrace us?' She hisses at you. 'If you have truly lost the marking of our castle, you will need to take this note and speak to the Toilmaster immediatley. Read it on the way and praise the will of Cazic-Thule.'
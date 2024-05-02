# General Staginar
## Dialog

**You say:** `hail`



>**General Staginar says:** Greetings. Soandso. Are you here to serve in the war against the grimling horde?

**You say:** `i am here to serve in the war`



>**General Staginar says:** As you probably know, we've been battling the grunts for nearly a generation now. They have proven to be a challenging opponent. We've inflicted great casualties upon their kind in this war, yet somehow, they seem to grow even more numerous. Barring some miracle, they will become a serious threat to Shar Vahl very soon. One remaining strategy has a chance of bringing us victory, but none have met the requirements for its implementation.

**You say:** `what requirements`



>**General Staginar says:** Our intelligence has provided us with some information about the enemy. They blindly follow a being they refer to as 'the master'. Our high spiritists have sensed a powerful presence from the caverns beyond our mines, but only those who possess a special key can venture there. None who have obtained the key and ventured into the caverns have been seen alive again.

**You say:** `what key`



>**General Staginar says:** The grimling high commander holds half of a magical acrylia obelisk that will transport the wielder to their master's stronghold. I have slain the high commander who held the other half of the obelisk and I have the knowledge of it's construction. I will only give it to one who has proven to be a powerful soldier, for nothing less would stand a chance against the enemy ruler.

**You say:** `what high commander`



>**General Staginar says:** The grimling high commander will only appear if their compound to the north is overrun. There are two encampments near the compound that will need to be invaded as well in order to secure the area. It is a very complex mission and I will only authorize you to lead it if you have demonstrated competence. Serve our people by successfully completing the lesser raids here in the forest. Bring me the Golden Medal of the Shar Vahl as proof of your prowess, or, if you are already at least as powerful as I am, there is another test that will give me confidence in your abilities.

**You say:** `what test`



>**General Staginar says:** If you are less experienced than I am, performing this task will gain you nothing. With that in mind, take this box and venture through the mines and into the caverns. Combine in it Gooplart's tooth, Gizgargank's scalp, Grikplag's skull, Gnildaria's eye, Gnerpokkel's heart, Gilgaplank's toes, the husk of the summoned burrower, and the shackles of a Vah Shir captive. Return to me with the Box of the Hero of Shar Vahl and I will send a team of our veterans to escort you into battle.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17867" data-url="17867" class="tooltip-link link">Box of the General's challenge</a>
end

## Turn-Ins





if (  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/6190" data-url="6190" class="tooltip-link link">Box of the Hero of Shar Vahl</a>  ) then 


>**General Staginar says:** Soldier, that's some fine work! The horde will not easily recover from the destruction you have inflicted upon their kind. You have earned an opportunity to wrestle the key from the grimling high commander. Take these orders to Veteran Cullin. If you can take possession of the grimling bases to the north and defeat the grimling high commander, return to me with his half of the obelisk and the battle orders. Show the grunts no mercy, Soandso! Good luck!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_861.png" alt="" /> <a
                                href="/item/6191" data-url="6191" class="tooltip-link link">Staginar's Battle Orders</a> 

 


elseif (  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5989" data-url="5989" class="tooltip-link link">Golden Medal of the Shar Vahl</a>  ) then 







>**General Staginar says:** Soldier, that's some fine work! The horde will not easily recover from the destruction you have inflicted upon their kind. You have earned an opportunity to wrestle the key from the grimling high commander. Take these orders to Veteran Cullin. If you can take possession of the grimling bases to the north and defeat the grimling high commander, return to me with his half of the obelisk and the battle orders. Show the grunts no mercy, Soandso! Good luck!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_861.png" alt="" /> <a
                                href="/item/6191" data-url="6191" class="tooltip-link link">Staginar's Battle Orders</a> 

 


elseif (  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1091.png" alt="" /> <a
                                href="/item/6192" data-url="6192" class="tooltip-link link">Acrylia Obelisk Half</a>  ) then 


e.self:Say(e.other:GetCleanName()..", your actions have earned you the respect of all Vah Shir. Upon your shoulders now rests the hope of our people. This hollow acrylia obelisk is the key that will gain you entry to the stronghold of the master of the grimling horde. Once there, you will need to collect enchanted pieces of acrylia from the enemy's vile minions. Once you have collected all five of them, you must place the obelisk into this smelting pot with the acrylia pieces. A special key will form inside that will grant you access to the deepest chamber of the stronghold.");


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1091.png" alt="" /> <a
                                href="/item/5972" data-url="5972" class="tooltip-link link">Hollow Acrylia Obelisk</a> 

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1016.png" alt="" /> <a
                                href="/item/17868" data-url="17868" class="tooltip-link link">Enchanted Acrylia Smelting Pot</a> 

 





**Set a timer** named *talk2* for 20 seconds

else


**This NPC *should* return incorrect items given.**
;
end

## Timer(s)

**Stop timer** named *talk2*



>**General Staginar says:** No one knows what lie beyond, what dangers you may face, or what trials you must overcome. No one who has ventured into the stronghold has returned to inform us of the dangers it may hold. Now, more than ever, we pray for the spirits of our ancestors to watch over and protect you. Now, round up an army of your most skilled and trusted friends and rid us of this menace!'
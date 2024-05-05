# Dain Frostreaver IV



[Dain Frostreaver IV](/npc/129003) is a level 70 Coldain Warrior that spawns in [Icewell Keep](/zone/129).



## Dialog

**You say:** `greetings and good fortune to you, honored dain frostreaver iv`



if( **Faction is** <= Indifferent) then



>*Dain Frostreaver IV seems to stare right into your soul with his one good eye. A chill runs down your spine.*


elseif( **Faction is** <= Kindly) then



>*Dain Frostreaver IV smiles at you and nods his head indicating he has been pleased with your progress.*


else



>**Dain Frostreaver IV says:** Greetin's and good fortune to yerself, " .. e.other:Race() .. ". Chamberlain Krystorf speaks highly of the deeds you have performed for our people and so I welcome you to my Keep. I ask you now to take up a most dangerous duty for our people. Would you accept such a challenge from the King of a people not your own?



e.self:DoAnim(48);


**You say:** `accept`



if( **Faction is** > Kindly) then



>*Dain Frostreaver IV smiles at you with pride and says, 'Something told me you would, Soandso. For years upon years the plagues of King Tormax have been unleashed upon my people. And indeed it was also by Tormax's hand that me own father, Dain Frostreaver the Third was slain. My attempts at assassinating him have only met with failure, and our forces, while strong, are not yet mighty enough to assault Kael Drakkel. Therefore I have ye and yer companions as my last hope, Soandso. Kill that bastard who calls himself King Tormax... and bring me his head!'*


**You say:** `mission`



if( **Faction is** > Kindly) then



>**Dain Frostreaver IV says:** After General Bragmur has equipped the armor you have created for him, give him these orders. He is a skilled diplomat and will need to reach the pirate Gnomes. We must enter into a pact with them. We will supply them the velium that they need to build their silly gadgets, and they will take their ship back to Antonica and call for reinforcements from out ancestors. We hope they will acceppt this pact, after all Brell has been known to align himself with Bristlebane whom the Gnomes of Iceclad follow. You may be an important [factor] in their success.


**You say:** `factor`



if( **Faction is** > Kindly) then



>**Dain Frostreaver IV says:** I fear that spies lurk in every corner. You may need to help the General reach the gnomish camp if the Kromrif have gotten word of our efforts. You should call on any allies that you have to assist in case they ambush you. Brell bless you Soandso, good luck.


**You say:** `count on my help`



>**Dain Frostreaver IV says:** Several of our greatest officers, including a few veterans from the war on Yesterwinter are assembling just outside our city. Gather your army at once and give this parchment and the ninth ring to Sentry Badian. I will remain inside the city with a few of my troops to defend it against any who might penetrate your defense. May Brell be with you, Soandso.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/1567" data-url="1567" class="tooltip-link link">Declaration of War</a>
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/8886" data-url="8886" class="tooltip-link link">Coldain Standard Issue Kit</a>) then 


>**Dain Frostreaver IV says:** Excellent work Soandso. If I didn't know I would assume this was made by our most skilled artisans.  You must hurry, General Bragmur has formed camp in Iceclad. Take the kit to the General, he had to drudge forward without any armor. His [mission] must be a success if we hope to successfully defend Thurgadin against the Giants.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/8898" data-url="8898" class="tooltip-link link">Approved Issue Kit</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/8897" data-url="8897" class="tooltip-link link">Expedition Orders</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_642.png" alt="" /> <a
                                href="/item/1199" data-url="1199" class="tooltip-link link">Runed Coldain Prayer Shawl</a> or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_642.png" alt="" /> <a
                                href="/item/8895" data-url="8895" class="tooltip-link link">Runed Coldain Prayer Shawl</a>) then


>**Dain Frostreaver IV says:** Ah Soandso. I was hoping to see you. We require your skilled hand. The Armory is overtaxed preparing armor for the war we are preparing to wage on the Kromzek. We need you to help by creating some Field Plate for a mission that is near to execution. Go see Loremaster Solstrin in the Hall of Ancestors, give him these orders. He holds the lore recorded on how to make the field plate. Return to me when you have completed a Standard Issue Kit.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_642.png" alt="" /> <a
                                href="/item/8895" data-url="8895" class="tooltip-link link">Runed Coldain Prayer Shawl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/8896" data-url="8896" class="tooltip-link link">Royal Coldain Orders</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_574.png" alt="" /> <a
                                href="/item/1465" data-url="1465" class="tooltip-link link">Dirk of the Dain</a>) then


>**Dain Frostreaver IV says:** My good Soandso, you have served me well. You have flushed out all who sought to oppose me and my people. I am afraid I need to call upon you and your friends one final time. The dissention and treason ran deeper than I had anticipated. Our population has been cleansed, but we lost a full third of our army to the poisonous words of those rebels. In retaliation for your deeds, the Kromrif have made plans to attack us in this, our weakest hour. Can I count on your help outlander?


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_574.png" alt="" /> <a
                                href="/item/1465" data-url="1465" class="tooltip-link link">Dirk of the Dain</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_980.png" alt="" /> <a
                                href="/item/30516" data-url="30516" class="tooltip-link link">King Tormax's Head</a>) then


if( **Faction is** >= Warmly) then 



>**Dain Frostreaver IV says:** You have done what no Coldain could do, Soandso! This is indeed a glorious say in our people's history. In return for your invaluable service I present you with the Tri-plated Golden Hackle Hammer. Its magic is powerful and I am sure it will serve you well.



**Dain Frostreaver IV shouts:** <span class="text-danger">Let it be know from this day forth that Soandso and their companions are Heros of the Coldain Kingdom. King Tormax has been slain, it is a time for celebration. Let no tankard go unfilled!</span>



Your faction standing with [Dain Frostreaver IV](/faction/405) got better (<span class='text-success'>+100</span>)



Your faction standing with [Coldain](/faction/406) got better (<span class='text-success'>+100</span>)



Your faction standing with [King Tormax](/faction/429) got worse (<span class='text-danger'>-50</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/30502" data-url="30502" class="tooltip-link link">Tri-Plated Golden Hackle Hammer</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_515.png" alt="" /> <a
                                href="/item/30385" data-url="30385" class="tooltip-link link">Ring of Dain Frostreaver IV</a>) then 


if( **Faction is** >= Ally) then



>**Dain Frostreaver IV says:** Soandso, your deeds have changed the fate of my people forever. Not since the sacrifice of Colin Dain himself has anyone so selflessly risked so much for our well being. Accept this blessing as a token of my gratitude.



 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/1747" data-url="1747" class="tooltip-link link">Protection of the Dain</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_515.png" alt="" /> <a
                                href="/item/30385" data-url="30385" class="tooltip-link link">Ring of Dain Frostreaver IV</a>) 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/1500" data-url="1500" class="tooltip-link link">Box of the Guilty</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_616.png" alt="" /> <a
                                href="/item/30164" data-url="30164" class="tooltip-link link">Velium Coldain Insignia Ring</a>) then


>**Dain Frostreaver IV says:** The people of Thurgadin are in your debt, Soandso. Please accept the Coldain Hero's Ring as a token of our gratitude. The curse has been removed from the blade as well. I hope you find it useful against our common foes. When you are interested in assisting me further please show me the blade. Until that day, may Brell bless and protect you.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_574.png" alt="" /> <a
                                href="/item/1465" data-url="1465" class="tooltip-link link">Dirk of the Dain</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_617.png" alt="" /> <a
                                href="/item/30369" data-url="30369" class="tooltip-link link">Coldain Hero's Insignia Ring</a>) 

 

**This NPC *should* return incorrect items given.**

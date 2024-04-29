# Dain Frostreaver IV
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


**You receive:**  [Declaration of War](/item/1567)
end

## Turn-Ins





if( **You turn in:** [Coldain Standard Issue Kit](/item/8886)) then 


>**Dain Frostreaver IV says:** Excellent work Soandso. If I didn't know I would assume this was made by our most skilled artisans.  You must hurry, General Bragmur has formed camp in Iceclad. Take the kit to the General, he had to drudge forward without any armor. His [mission] must be a success if we hope to successfully defend Thurgadin against the Giants.


 **You receive:** GiveAll( [Approved Issue Kit](/item/8898), [Expedition Orders](/item/8897)) 

elseif( **You turn in:** [Runed Coldain Prayer Shawl](/item/1199) or  **You turn in:** [Runed Coldain Prayer Shawl](/item/8895)) then


>**Dain Frostreaver IV says:** Ah Soandso. I was hoping to see you. We require your skilled hand. The Armory is overtaxed preparing armor for the war we are preparing to wage on the Kromzek. We need you to help by creating some Field Plate for a mission that is near to execution. Go see Loremaster Solstrin in the Hall of Ancestors, give him these orders. He holds the lore recorded on how to make the field plate. Return to me when you have completed a Standard Issue Kit.


 **You receive:** GiveAll( [Runed Coldain Prayer Shawl](/item/8895), [Royal Coldain Orders](/item/8896)) 

elseif( **You turn in:** [Dirk of the Dain](/item/1465)) then


>**Dain Frostreaver IV says:** My good Soandso, you have served me well. You have flushed out all who sought to oppose me and my people. I am afraid I need to call upon you and your friends one final time. The dissention and treason ran deeper than I had anticipated. Our population has been cleansed, but we lost a full third of our army to the poisonous words of those rebels. In retaliation for your deeds, the Kromrif have made plans to attack us in this, our weakest hour. Can I count on your help outlander?


 **You receive:**  [Dirk of the Dain](/item/1465) 

elseif( **You turn in:** [King Tormax's Head](/item/30516)) then


if( **Faction is** >= Warmly) then 



>**Dain Frostreaver IV says:** You have done what no Coldain could do, Soandso! This is indeed a glorious say in our people's history. In return for your invaluable service I present you with the Tri-plated Golden Hackle Hammer. Its magic is powerful and I am sure it will serve you well.



**Dain Frostreaver IV shouts:** <span class="text-danger">Let it be know from this day forth that Soandso and their companions are Heros of the Coldain Kingdom. King Tormax has been slain, it is a time for celebration. Let no tankard go unfilled!</span>



* __Faction:__ [Dain Frostreaver IV](/faction/405) (100)



* __Faction:__ [Coldain](/faction/406) (100)



* __Faction:__ [King Tormax](/faction/429) (-50)



 **You receive:**  [Tri-Plated Golden Hackle Hammer](/item/30502) 


elseif( **You turn in:** [Ring of Dain Frostreaver IV](/item/30385)) then 


if( **Faction is** >= Ally) then



>**Dain Frostreaver IV says:** Soandso, your deeds have changed the fate of my people forever. Not since the sacrifice of Colin Dain himself has anyone so selflessly risked so much for our well being. Accept this blessing as a token of my gratitude.



 **You receive:** GiveAll( [Protection of the Dain](/item/1747), [Ring of Dain Frostreaver IV](/item/30385)) 


elseif( **You turn in:** [Box of the Guilty](/item/1500), [Velium Coldain Insignia Ring](/item/30164)) then


>**Dain Frostreaver IV says:** The people of Thurgadin are in your debt, Soandso. Please accept the Coldain Hero's Ring as a token of our gratitude. The curse has been removed from the blade as well. I hope you find it useful against our common foes. When you are interested in assisting me further please show me the blade. Until that day, may Brell bless and protect you.


 **You receive:** GiveAll( [Dirk of the Dain](/item/1465), [Coldain Hero's Insignia Ring](/item/30369)) 

**This NPC *should* return incorrect items given.**

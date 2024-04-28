# Aid Grimel

## Dialog

local qglobals = eq.get_qglobals(e.other);



**You say:** `hail`





>**Aid Grimel says:** Greetings and Salutations Soandso! I am Grimel, aid to the mighty paladin Councilman Taldarius. In between his duties to the city, Taldarius and I spend most of our time in the Planes cleansing evil. Even now I am preparing for battle. Taldarius intends to go further into the Planes than ever before on our next trip and I am working on gathering the special supplies we need. If you are willing to help I may have some use for your skills if you are a master of trades and have traveled in the Planes.




**You say:** `willing to help`



>**Aid Grimel says:** Excellent! I am looking for a smith to add a special imbue to Councilman Taldarius's armor. Are you well versed in the art of smithing?




**You say:** `versed in the art of smithing`



if ( qglobals.fuirstel and qglobals.fuirstel == "5" ) then 



if ( e.other:GetRawSkill(63) > 219 ) then 




>**Aid Grimel says:** Thank you for offering to help Soandso. Take this breastplate and clean it with a diluted acid wash to get all of the debris out of it. Brew the wash by combining acid and three celestial essences. Once the armor is cleaned, coat it with hurricane temper. Finally add two black diamonds of nightmare to the breastplate. This should provide adequate protection for our next journey.




**You receive:**  [Filthy Breastplate](/item/15984)



else




e.self:DoAnim(52); 




>**Aid Grimel says:** I would not trust you to make a file, much less touch Councilman Taldarius's armor!  Come back when you are more skilled in the craft.




else



e.self:DoAnim(52);



>**Aid Grimel says:** I am sorry, but one who has such limited knowledge of the Planes would not be able to assist me.





**You say:** `have skill in brewing`



if ( qglobals.thelin and qglobals.thelin == "4" ) then 



if ( e.other:GetRawSkill(65) > 219 ) then 




>**Aid Grimel says:** I bet you could make a wicked brew! However I am forced to drink a refreshing drink while out adventuring. I do have this powder that will give the best drinks quite a bite though. Mix the powder in with two Kaladim Constitutionals and a flask of pure water. If you need more dust just ask for it! Put three twice brewed constitutionals and the signet in this drink barrel. As hard as drink barrels are to get these days, you need to return it to me along with the drink you create with it.




**You receive:**  [Portable Drink Barrel](/item/17179)




e.other:SummonCursorItem(15992,1); 




e.other:SummonCursorItem(15992,1); 




e.other:SummonCursorItem(15992,1); 



else




e.self:DoAnim(63); 




>**Aid Grimel says:** I am not picky with what I drink however the swill you could brew I wouldn't force on a Bubonian!  Come back when you have gained more skill.




else



e.self:DoAnim(52);



>**Aid Grimel says:** I am sorry, but one who has such limited knowledge of the Planes would not be able to assist me.





**You say:** `jewel craft skills to the test`



if ( qglobals.saryrn or qglobals.cipher ) then 



if ( e.other:GetRawSkill(68) > 219 ) then 




>**Aid Grimel says:** My hand was crushed when I used it to deflect a blow from a War Boar that was headed towards Taldarius's back. For some time afterwards my hand was crippled but Brell saw to it I regained full use of it. The ring I used to wear was damaged beyond repair and my hand was never steady enough to etch a new one. If you would make me a new one by combining a mounted blue diamond, the etching dust and etching tools in a jewelry kit. Then take the faceted gem and combine it with a bar of pure enchanted velium and my signet. I have no idea how the pure bars are made. You may want to seek the help of the ice dwarves.




**You receive:**  [Etching Dust](/item/15988)



else




>**Aid Grimel says:** While you may have mastered the arts of smithing and brewing, I still find your ability to work with gems lacking.  Return when you are more skilled.




else



e.self:DoAnim(52);



>**Aid Grimel says:** While you do have some knowledge of the Planes, you are lacking what I require for any further tasks.





**You say:** `ready to use some clay`



if ( qglobals.zeks and (qglobals.zeks == "6" or qglobals.zeks == "7") ) then 



if ( e.other:GetRawSkill(69) > 219 ) then 




>**Aid Grimel says:** On our last tome gathering expedition a stray arrow in the Plane of War struck our urn filled with sacred water. It was quite a waste of sacred water! Three large enchanted blocks of clay, three lacquered opals, a vial of purified mana, a ceramic lining, sculpting tools and the urn pattern should make an unfired urn. The urn is so large you will need to fire it with three divine crystalline glazes. Once you have the urn it needs to be filled with three sacred waters and the signet as a cap.




**You receive:**  [Urn Pattern](/item/16243)



else




e.self:DoAnim(63); 




>**Aid Grimel says:** I once saw a house built out of sun-fired clay, with your skills I wouldn't wager you could build more than a rickety birdhouse.  Please don't crush any birds.




else



e.self:DoAnim(52);



>**Aid Grimel says:** While you do have some knowledge of the Planes, you are lacking what I require for any further tasks.





**You say:** `skilled with the needle`



if ( qglobals.pofire and qglobals.pofire == "2" ) then 



if ( e.other:GetRawSkill(61) > 219 ) then 




>**Aid Grimel says:** I appreciate the help Soandso. I need a new tunic made for Councilman Taldarius. Last trip through the Plane of Disease, one of those flies spit mucus on him and it dripped through his armor seams! The result was a gooey mess that ate away all the leather underneath. It was a blessing he was wearing something under all that metal! Combine three firesilk swatches, a vial of purified mana, an emblem of fire, a firestrand curing agent, a tunic pattern and the signet. Bring it to me when you have completed it.



else




e.self:DoAnim(63); 




>**Aid Grimel says:** With your ability I think you would have trouble mending a pair of socks!  Seek me out when you are more skilled.




else



e.self:DoAnim(52);



>**Aid Grimel says:** Your knowledge of the Planes is impressive, however you still have much to learn.





**You say:** `skills with a fletching knife`



if ( qglobals.pofire and qglobals.pofire == "2" ) then 



if ( e.other:GetRawSkill(64) > 219 ) then 




>**Aid Grimel says:** Aye I can see you are skilled with the fletching knife Soandso. It is good too, I need to replace Councilman Taldarius's bow from Plane of Air. Combine a planing tool, two wind metal bow cams, an air arachnid silk string, a featherwood staff and the signet. I hope the bow will be up to his standards, he sure loved his old bow.



else




e.self:DoAnim(63); 




>**Aid Grimel says:** Stringing a bow requires much time and patience.  I am afraid I have a limited amount of both right now to watch your fruitless attempts.  I would go observe some elves working the craft, and hope to learn something.




else



e.self:DoAnim(52);



>**Aid Grimel says:** Your knowledge of the Planes is impressive, however you still have much to learn.




**You say:** `master chef`



if ( qglobals.pofire and qglobals.pofire == "2" and qglobals.zebuxoruk and qglobals.zebuxoruk == "2" ) then 



if ( e.other:GetRawSkill(60) > 219 ) then 




>**Aid Grimel says:** When we adventure in the Planes there is only one meal that keeps us in top fighting shape. It is called a Bristlebane's Party Platter. Unfortunately the platter is awkward and not easy to adventure with so you need to place them in this satchel. I know not how to make the Platter, a rather nice female Halfling cleric always used to deliver them to us but I heard she was crushed by a Regrua while hunting for a rare component in the Plane of Water. Brell bless her soul! Combine three of the platters and the signet inside the satchel.




**You receive:**  [Field Satchel](/item/17180)



else




e.self:DoAnim(63); 




>**Aid Grimel says:** If I wanted bad food I would still be in Rivervale consuming that slop Ella passes off as fine cuisine.  Seek me out when you have mastered the frying pan.




else



e.self:DoAnim(52);



>**Aid Grimel says:** Your knowledge of the Planes is impressive, however you still have much to learn.

end

## Turn-Ins



if **You turn in:** [Imbued Breastplate](/item/15985)


>*Aid Grimel smiles. 'What a wonderful job!  Councilman Taldarius shall wear this on our next adventure, I am sure he will find it more protective than his old one.   Take this signet as a token of my gratitude.  If you are not too busy I have another task, do you have any brewing skill?'*


 **You receive:**  [Hardened Leather Signet](/item/16249) 

if **You turn in:** [Portable Drink](/item/15993), [Portable Drink Barrel](/item/17179)


>*Aid Grimel gulps down a Twice Brewed Constitutional and burps loudly! 'Ahhhh that was refreshing! That should hold me over for quite some time. I see you are quite deft of hand, perhaps you would care to put your jewel craft skills to the test?'*


 **You receive:**  [Clay Signet](/item/16250) 

if **You turn in:** [Velium Blue Diamond Ring](/item/15991)


>*Aid Grimel grins. 'Quite a nice ring you have made for me Soandso. May it serve me as well as my old ring. Here take this signet. We seem to be finishing the tasks on my list at a nice pace. Tell me when you are ready to use some clay.*


 **You receive:**  [Wooden Signet](/item/16251) 

if **You turn in:** [Filled Sacred Urn](/item/16246)


>**Aid Grimel says:** Outstanding work Soandso! I can feel the purity of the water radiating through the clay. Are ye skilled with the needle as well as an accomplished potter?


 **You receive:**  [Metal Signet](/item/16252) 

if **You turn in:** [Fire Undergarment Tunic](/item/15986)


>*Aid Grimel Aid Grimel inspects the tunic. 'Good work Soandso.  This will definitely serve Councilman Taldarius well.  Here take this!  If you have skills with a fletching knife I may have a job for you to do.'*


 **You receive:**  [Marked Signet](/item/1079) 

if **You turn in:** [Signet Featherwood Bow](/item/16247)


>**Aid Grimel says:** Masterful work Soandso! I can see your skill in the curves of the bow. Take this as a sign of my respect for your skill. The last item I need before we can be off is some food. I warn you this will truly test your skills. Do you fancy yourself a master chef?


 **You receive:**  [Runed Signet](/item/16254) 

if **You turn in:** [Food Satchel](/item/16248)


>**Aid Grimel says:** Truly amazing! Now the Councilman and I can be off on our expedition to the Elemental Planes!' He takes out a tool and marks his signet before handing it to you, 'Before we depart you may want to ask the Councilman about the signet.


 **You receive:**  [Marked Runed Signet](/item/16256) 

**This NPC *should* return incorrect items given.**

# Waltor Felligan
## Dialog

**You say:** `Hail`



>**Waltor Felligan says:** Hello, me friend! I'm the resident healer o' Halas. Please inform me when ye've a need fer me talents to [bind wounds], [cure disease] or [cure poison]. Might I add, if ye're a young shaman o' Halas, ye can also [assist in gathering fungus].

**You say:** `assist in gathering fungus`



if( **Faction is** > Indifferent) then 



>**Waltor Felligan says:** As the wooly spiderlings get ready to molt, they'll carry wooly fungus. Oftentimes, one can find wooly fungus growing on their bellies. I use this in me healing practices. I'll reward ye if ye can fill this jar full o' the valuable fungus. Don't forget to combine them before ye return it to me. And have yerself some rations handy, or ye may find yerself snacking on this tasteless food source.



**You receive:**  [Empty Jar](/item/17946)


elseif( **Faction is** == Indifferent) then



>**Waltor Felligan says:** Ye're no criminal to the Shamans o' Justice, but ye've yet to prrove yer devotion to justice.




else



>**Waltor Felligan says:** The scales o' the Shamans o' Justice dinnae tip in yer favor. Ye'd best flee ye still have the chance.




**You say:** `cure disease`



if( **Faction is** > Apprehensive) then 



**You say:** `cure disease`





>**Waltor Felligan says:** Two small quantities o' wooly fungus are needed before we can cure yer malady.



**You say:** `bind wounds`





>**Waltor Felligan says:** Before I bind yer wounds, ye must pay tribute to the Tribunal in the amount of ten gold coins.



**You say:** `cure poison`





>**Waltor Felligan says:** I'll be needing mammoth steaks to feed the unfortunate.  Then we'll drain the poison from yer veins.




else






>**Waltor Felligan says:** The scales o' the Shamans o' Justice dinnae tip in yer favor. Ye'd best flee ye still have the chance.

end

## Turn-Ins



if( **Faction is** > Indifferent and  **You turn in:** [Jar of Fungus](/item/13966)) then 








>**Waltor Felligan says:** Aye! Ye've filled the jar. I'll see to it that Holana locks this away. Tis difficult to obtain and we can only spare the talents of our young shamans. Allow me to give ye a reward. Thank ye kindly fer yer service.





* __Faction:__ [Shamen of Justice](/faction/327) (10)



* __Faction:__ [Merchants of Halas](/faction/328) (1)



* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)



* __Faction:__ [Coalition of Tradefolk](/faction/229) (-1)




* __Faction:__ [Ebon Mask](/faction/244) (-2)


 **You receive:** eq.ChooseRandom( [Spell: Cure Poison](/item/15203), [Spell: Drowsy](/item/15270), [Spell: Fleeting Fury](/item/15271), [Spell: Frost Rift](/item/15275), [Spell: Gate](/item/15036), [Spell: Sicken](/item/15075), [Spell: Endure Fire](/item/15224), [Spell: Feet like Cat](/item/15269)) (+3000 exp)

elseif( **You turn in:** gold = 10) then


>**Waltor Felligan says:** The scales have been balanced and the Tribunal has spoken. Yer body shall be saved.


**Waltor Felligan casts:** [Light Healing](/spell/17) on target.

elseif( **You turn in:** [Mammoth Steaks](/item/13445)) then


**Waltor Felligan casts:** [Cure Poison](/spell/203) on target.


>**Waltor Felligan says:** The scales have been balanced and the Tribunal has spoken. Yer body shall be saved.

elseif( **You turn in:** [Wooly Fungus](/item/13967), [Wooly Fungus](/item/13967)) then


**Waltor Felligan casts:** [Cure Disease](/spell/213) on target.


>**Waltor Felligan says:** The scales have been balanced and the Tribunal has spoken. Yer body shall be saved.

**This NPC *should* return incorrect items given.**






# Camin
## Dialog

**You say:** `hail`



>**Camin says:** Go away! I have no time for you!

**You say:** `What are you searching for`



>**Camin says:** Ah! A smart one, I see! If you really wish to know about such a thing, you will have to help me finance my studies. The knowledge I have acquired and researched did not come cheaply.
end

## Turn-Ins



local qglobals = eq.get_qglobals(e.self,e.other);


if( **You turn in:** [Note to Camin](/item/18088)) then


>**Camin says:** So you have met Solomen, eh? He is a man with a wealth of knowledge. It is good to hear he is well.


 **You receive:** 0 (+500 exp)


eq.set_global("wizepic","1",0,"D30");

elseif( **You turn in:** [Ro's Breath](/item/14330)) then


if(qglobals["wizepic"] == "2") then



>**Camin says:** Very interesting... I've seen this work before. Yes, yes! It's the work of Arantir Karondor! Give this back to the person you got it from. Maybe they will have a clue to Arantir's Location.



* __Faction:__ [Truespirit](/faction/404) (10)



 **You receive:**  [Ro's Breath](/item/14331) (+10000 exp)



eq.delete_global("wizepic");


else



>**Camin says:** I have no need for this item Soandso, you can have it back.



 **You receive:**  [Ro's Breath](/item/14330) 


elseif( **You turn in:** platinum = 1000) then


if(qglobals["wizepic"] == "1") then



>**Camin says:** Good, good, you show a willingness to learn of this with your offer. What I can tell you is that Solusek Ro had four followers who had shown exceptional aptitude in the arts of wizardry. Solusek Ro himself tutored them. He considered them to be like his own children. I know of one who still exists. He goes by the name of Arantir Karondor. He used to specialize in the storing of magic into physical objects. Arantir has been hiding for many, many years and will most assuredly be going by another name, so keep your eyes open. Anyway, be off, I need to continue my research. Return to me if you ever find Arantir Karondor.



* __Faction:__ [Truespirit](/faction/404) (10)



 **You receive:** 0 (+500 exp)



eq.set_global("wizepic","2",0,"D30");


else



>**Camin says:** I have no need for this item Soandso, you can have it back.



e.other:GiveCash(0,0,0,1000);


**This NPC *should* return incorrect items given.**
;
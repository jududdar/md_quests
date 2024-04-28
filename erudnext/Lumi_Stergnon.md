# Lumi Stergnon
## Dialog

local fac = e.other:GetFaction(e.self);


**You say:** `hail`



>**Lumi Stergnon says:** Peace and tranquility be with you. Soandso.  Are you a [new acolyte of peace] or are you [here to pay homage] to the child of tranquility?

**You say:** `new acolyte of peace`



if **Faction** >= Amiable then 




**You say:** `new acolyte of peace`





>**Lumi Stergnon says:** Then you shall learn the ways of Quellious and learn to do as you are told by higher ranking members. It is time for you to do the lesser duties of a young priest. Which will it be? [Retrieve the Peacekeeper staffs] or [battle the undead]?



**You say:** `retrieve the Peacekeeper staffs`





>**Lumi Stergnon says:** Then take this note to the woodworker in Toxxulia Forest. His name is Emil Parsini. He shall have the staff to be returned to the temple.




**You receive:**  [a sealed letter](/item/18833)



**You say:** `battle the undead`





>**Lumi Stergnon says:** Then you shall venture to Toxxulia Forest. There has been an increase in skeleton sightings lately. I do not know their origin, but I believe that your efforts will reduce their numbers! Take this box. Return it to me when you have filled it with the bones of these undead creatures and combined it. May Quellious' light guide you.




**You receive:**  [Box For Bones](/item/17941)




**You say:** `important missions`





>**Lumi Stergnon says:** We have need of skilled priests. We have learned that a High Guard battle staff has been stolen. We require a priest to [track down the staff].



**You say:** `track down the staff`





>**Lumi Stergnon says:** In the mountain keep called High Hold, we have heard there is a person hiring mercenaries for an attempt to obtain a High Guard battle staff. We are missing one of our staffs and believe this person has it. Go to Highpass Hold and find this person. Return the High Guard battle staff to me!








elseif **Faction** >= Indifferent then



>**Lumi Stergnon says:** You have not done much to upset the Peacekeepers of this temple, but we must ask you to prove yourself to us before we may discuss things such as this.


else



>**Lumi Stergnon says:** Leave my sight at once! You are no friend to the Peacekeepers of the Temple of Divine Light.


**You say:** `here to pay homage`




>**Lumi Stergnon says:** Then respect our temple and keep your prayers silent.
end





## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [A Box of Bones](/item/13882)


>**Lumi Stergnon says:** This is fabulous work, my friend! You have served your people well. Take this as a gift. I hope it can be of use to you. We need proof of these skeletons' origins. Continue the eradication of the undead and find out who creates them. Once you know, bring their head to me.





* __Faction:__ [Peace Keepers](/faction/298) (10)
  


* __Faction:__ [High Council of Erudin](/faction/266) (2)
  


* __Faction:__ [Heretics](/faction/265) (-2)





 **You receive:** None 

elseif **You turn in:** [Peacekeeper Staff](/item/13816)


>**Lumi Stergnon says:** You have done well, neophyte.Let me add the touch of harmony to finish the job.. Here, then. Take these supplies. I am sure you'll need them. Soon you may be able to assist us in [important missions].





* __Faction:__ [Peace Keepers](/faction/298) (10)
  


* __Faction:__ [High Council of Erudin](/faction/266) (2)
  


* __Faction:__ [Heretics](/faction/265) (-2)
  


 **You receive:** None 

**This NPC *should* return incorrect items given.**
;


# Hoyce MacTaegan
## Dialog

**You say:** `hail`



>**Hoyce MacTaegan says:** Greetings to you brother. Did [Keven] send you?

**You say:** `keven`



if **Faction** >= Amiable then 



>**Hoyce MacTaegan says:** Very well, then let us begin. We are at home in the wilderness and thus it is important that we learn all we can about our surroundings. Now is the time of your learning. You are to venture out, hunt and learn about Everfrost. Return to me with a White Wolf Skin as proof of your successful hunt. We will then continue your training.


else



>**Hoyce MacTaegan says:** Hmmm... I don't know if I believe that.




**You say:** `the land`



if **Faction** >= Amiable then 



>**Hoyce MacTaegan says:** There is a bounty waiting for us in the wilderness for those with the wisdom to use it. Your next task is to find that wisdom within yourself and to use it. I shall task you with the creation of a few simple items from the materials available to us all. Go forth and harvest silk to make thread. Then when you feel you have learned enough, make a cap for yourself from the pelt of a bear. Return three Silk Thread and a Large Tattered Skullcap to me and I shall reward you.


else



>**Hoyce MacTaegan says:** Hmmm... I don't know if I believe that.




**You say:** `fight`



if **Faction** >= Amiable then 



>**Hoyce MacTaegan says:** That's the spirit! No doubt you know by now that our people are under constant attack by the goblins that infest our lands. Go out and fight against our enemies and bring justice to our people. Return to me with four Goblin Ice Necklaces and you shall have your just reward.


else



>**Hoyce MacTaegan says:** Hmmm... I don't know if I believe that.




**You say:** `challenge`



if **Faction** >= Amiable then 



>**Hoyce MacTaegan says:** Your zeal for justice is indeed a virtue. You make us all proud. Very well, venture out and into the home of those accursed dogs. Go to Blackburrow the home of the gnolls. There you are to fight against them and to retrieve the weapons of our mortal enemies. Return to me with a Gnoll Fang, a Giant Snake Fang and a Hunting Bow. I shall give you a weapon suitable for one such as yourself.


else



>**Hoyce MacTaegan says:** Hmmm... I don't know if I believe that.




**You say:** `favor`



if **Faction** >= Amiable then 



>**Hoyce MacTaegan says:** I thank you for your willingness to help. Many of our people hunt the mighty mammoth and the cougar out in the vast and frigid plains. Aside from the risk of injury that often comes from hunting such fearsome and mighty creatures, there is the added risk of being attacked by the terrible snow orcs. Go and protect our people hunting in the plains of Everfrost, fight against the snow orc and return to me with a Wrath Orc Wristband. Surely the spirits will forever guide you.


else



>**Hoyce MacTaegan says:** Hmmm... I don't know if I believe that.



end

## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** [White Wolf Skin](/item/13768)



>**Hoyce MacTaegan says:** Very good! I am sure by now you are learning much about your local surroundings. It is now time for you to learn to [live off the land].


* __Faction:__ [Shamen of Justice](/faction/327) (3)
  









* __Faction:__ [Merchants of Halas](/faction/328) (1)
  









* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)
  









* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-1)
   









* __Faction:__ [Ebon Mask](/faction/244) (-1)
 









 **You receive:**  [Field Priests Bracer](/item/7365) (+250 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Silk Thread](/item/16486), [Silk Thread](/item/16486), [Silk Thread](/item/16486), [Large Tattered Skullcap](/item/2125)







>**Hoyce MacTaegan says:** I see your wisdom grows, as does your skill. Wear this cap I have made for you. I believe you are now skilled enough to begin to pursue justice and to fight against our enemies. Are you [willing to fight]?


* __Faction:__ [Shamen of Justice](/faction/327) (1)
  









* __Faction:__ [Merchants of Halas](/faction/328) (1)
  









* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)
  









* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-1)
   









* __Faction:__ [Ebon Mask](/faction/244) (-1)
 









 **You receive:**  [Field Priests Cap](/item/7366) (+400 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Goblin Ice Necklace](/item/13897), [Goblin Ice Necklace](/item/13897), [Goblin Ice Necklace](/item/13897), [Goblin Ice Necklace](/item/13897)



>**Hoyce MacTaegan says:** I see you have brought many of our enemies to justice. You have done an excellent job and should be proud. No doubt your efforts saved lives. It is now time for you to venture out and fight stronger foes. Are you [up to the challenge]?


* __Faction:__ [Shamen of Justice](/faction/327) (5)
  









* __Faction:__ [Merchants of Halas](/faction/328) (1)
  









* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)
  









* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-1)
   









* __Faction:__ [Ebon Mask](/faction/244) (-1)
 









 **You receive:**  [Field Priests Kilt](/item/7367) (+600 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Gnoll Fang](/item/13915), [Giant Snake Fang](/item/7005), [Hunting Bow](/item/8011)











>**Hoyce MacTaegan says:** You truly have justice in your heart. The spirits know this too. No doubt you are now beginning to hear their faint whispers. Soon you shall hear them clearly and you shall no longer need my guidance. I have one more [favor] to ask of you if you are [willing].


* __Faction:__ [Shamen of Justice](/faction/327) (10)
  









* __Faction:__ [Merchants of Halas](/faction/328) (1)
  









* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)
  









* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-1)
   









* __Faction:__ [Ebon Mask](/faction/244) (-2)
 









 **You receive:**  [Field Priests Claw](/item/7368) (+1000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Wrath Orc Wristbands](/item/12223)











>**Hoyce MacTaegan says:** Thank you very much, you have our thanks. Perhaps you will find some use for this. I have shown you all that I can young one. Now it is up to you. Listen to the spirits and work with them and they will work with you. Now go forth and continue to spread justice throughout the world.


* __Faction:__ [Shamen of Justice](/faction/327) (50)
  









* __Faction:__ [Merchants of Halas](/faction/328) (7)
  









* __Faction:__ [Circle of Unseen Hands](/faction/223) (-7)
  









* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-7)
   









* __Faction:__ [Ebon Mask](/faction/244) (-10)
 









 **You receive:**  [Field Priests Leather](/item/7369) (+1000 exp)

**This NPC *should* return incorrect items given.**

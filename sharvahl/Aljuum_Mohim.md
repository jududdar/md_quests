# Aljuum Mohim


## Dialog

**You say:** `wolves`



>**Aljuum Mohim says:** The wolves that I speak of have no need for sight. They are products of the darkness that surrounds us. Their ability to move in the darkness and attack in packs makes them a serious threat to any Vah Shir that walks beyond our city's gates. I fear them more than I fear the twisted little people that live in the caves around here. It is the duty of each citizen to help control the number of these creatures. Fill the bag that I just handed you with the jawbones of two young sonic wolves and I'll know that you have a real understanding of the ferocity of those creatures. If you return, I'll have something that you may find interesting.
end

## Turn-Ins



if( **You turn in:** [Lute of the Jharin Apprentice](/item/5967)) then


>**Aljuum Mohim says:** That is quite a lute. Gawfed has an incredible gift in that area. I don't have the patience to build instruments. I prefer to use my time for other things. I'm sure that Gawfed will fill you in on the more delicate side of our craft when he gets over his holiday. Until that time, I'll get you started on the other part of being a Jharin. Here, take your lute and this bag. Once you get that stowed away, buy me a drink. If you can guess my favorite drink, I'll start you on your lesson.


 **You receive:** GiveAll( [Lute of the Jharin Apprentice](/item/5967), [Blue Cloth Bag](/item/17112)) 

elseif( **You turn in:** [Sonic Wolf Pale Ale](/item/22154)) then


>**Aljuum Mohim says:** Very good! I guess I should get you started.' He says as he finishes the drink that you just purchased. 'Our kin have encountered a number of beasts since the time of our arrival here. Your lesson today will center around one such creature. Maybe that will give you a better understanding of our role here. Bah, Taruun scouts... a real Jharin can do twice as much in combat... well, I digress. You're here to learn about [wolves], not my petty animosities.

elseif( **You turn in:** [Bloody Cloth Bag](/item/6157)) then


>**Aljuum Mohim says:** How was your little encounter with those beasts? Quite nasty in combat, eh? I told you as much. Well, now that you've seen them firsthand, I'll tell you how to deal with them like a true hunter. Take this hilt piece and show Hana Sulm. She'll give you some sketches. Once you have those sketches, go to Arms Historian Qua and purchase the tomes on Wolf Bane Lore or something like that. He'll know what you mean. You can use those books and the sketches to make a weapon that offers considerable power against those wolves. Once you have the weapon, bring it to me with your apprentice cloak. I'll have something for you. Now go away and let me finish this drink.


* __Faction:__ [Guardians of Shar Vahl](/faction/1513) (10)


 **You receive:**  [Jharin Hilt Piece](/item/6144) 

elseif( **You turn in:** [Sonic Wolf Bane Dagger](/item/6158), [Cloak of the Jharin Apprentice](/item/5966)) then


>**Aljuum Mohim says:** Congratulations Soandso.  You have successfuly navigated to the status of Journeyman.  Take your dagger and this cloak, wear it with pride.


 **You receive:** GiveAll( [Cloak of the Jharin Journeyman](/item/6159), [Sonic Wolf Bane Dagger](/item/6158)) (+10000 exp)

**This NPC *should* return incorrect items given.**

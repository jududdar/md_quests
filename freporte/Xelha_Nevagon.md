# Xelha Nevagon
## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Xelha Nevagon says:** A new recruit to our cause.  Just what I have been waiting for! How would you like to serve the great Xelha Nevagon? I need an apprentice necromancer to [assist the great Xelha].


else



**Xelha Nevagon says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `assist the great xelha`




if **Faction** >= Amiable then



>**Xelha Nevagon says:** Fantastic. Stick with me and you shall ascend in our ranks quickly. I am in need of some components for new spells.  Will you collect them for me?  I shall need four each of the following - fire beetle eyes. bone chips and spiderling silk.  Fetch these items for me at once. Well..? Did not you hear the great Xelha? Begone!


elseif( **Faction is** == Indifferent) then



>**Xelha Nevagon says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Xelha Nevagon says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



local text1 = "Do not flame beetles have two eyes?!! This will do me no good. I will not reward you until I have two pairs!!";

local text2 = "Oh wonderful!! A few strands of spiderling web. Aren't you quite the hunter... Despite your obviously great skills, you managed to only kill one spiderling?! Get your cowardly hide out there and get me a few more spiderling silks!.";


if **Faction** >= Indifferent and  **You turn in:** [Spiderling Silk](/item/13099), [Spiderling Silk](/item/13099), [Spiderling Silk](/item/13099), [Spiderling Silk](/item/13099)


>**Xelha Nevagon says:** Let's see here. One.. two.. three.. and.. four. Great!! Just enough for my needs. You are serving Xelha well. I give you Xelha's Sparkler. It is not much, but neither are you. You know what I really need is a cyclops eye. That would be worthy of a great reward.





* __Faction:__ [Dismal Rage](/faction/271) (10)


* __Faction:__ [Knights of Truth](/faction/281) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (2)


 **You receive:** None 

elseif **Faction** >= Indifferent and  **You turn in:** [Fire Beetle Eye](/item/10307), [Fire Beetle Eye](/item/10307), [Fire Beetle Eye](/item/10307), [Fire Beetle Eye](/item/10307)


>**Xelha Nevagon says:** This is a good sight. I needed these to complete the current mixture. Bah!! I shall reward you for this small, very small, deed!! I pass on to you the knowledge of summoning. The more you serve, the more your faith in Innoruuk grows.





* __Faction:__ [Dismal Rage](/faction/271) (10)


* __Faction:__ [Knights of Truth](/faction/281) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (2)


 **You receive:** None 

elseif **You turn in:** [Bone Chips](/item/13073), [Bone Chips](/item/13073), [Bone Chips](/item/13073), [Bone Chips](/item/13073)


>**Xelha Nevagon says:** Excellent work! You are quite the little helper. Here you go, then. A little something for your little work. Your service to me has caused Innoruuk to look upon you favorably. Your faith in our group has grown. Continue the work.





* __Faction:__ [Dismal Rage](/faction/271) (5)


* __Faction:__ [Knights of Truth](/faction/281) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (1)





 **You receive:** None 



elseif **Faction** >= Kindly and  **You turn in:** [Cyclops Eye](/item/13927)


>**Xelha Nevagon says:** A cyclops eye!! You are stronger than I believed. You will rise in the ranks of the Dismal Rage quickly with acts such as this!! I am most appreciative! Here, take this. It was lying around my shelves, just gettingg all dusty. I hope you can use it. And watch yourself in your journeys, the aura of your faith in Innoruuk surrounds you like a shroud. Our enemies will surely see you for what you are.





* __Faction:__ [Dismal Rage](/faction/271) (25)


* __Faction:__ [Knights of Truth](/faction/281) (-3)


* __Faction:__ [Opal Darkbriar](/faction/296) (5)


 **You receive:** None 

**This NPC *should* return incorrect items given.**





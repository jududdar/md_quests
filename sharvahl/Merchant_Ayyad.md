# Merchant Ayyad

## Dialog

**You say:** `hail`



>**Merchant Ayyad says:** Hello Soandso, sorry but I have no time to chitchat. I'm looking for the help of a citizen.

**You say:** `citizen`



>*Merchant Ayyad looks at you excitedly, 'Show me your acrylia slate and I'll explain my situation.'*

**You say:** `additional instruction`



>**Merchant Ayyad says:** Mastered those runes already, Soandso? You're learning very fast indeed. Your next lesson will be in the molding of a new type of item. You'll need to gather some gray mud from below the city and mix it with some Rockhopper blood to make a block of reddish clay. Take this block of reddish clay and combine it with a Vah Shir model sketch to create an unfired Vah Shir figurines. Fire the model in a kiln with a firing sheet to create a Finished Vah Shir figurine. Finally, use the Runequill Set to etch grimling blood into runes on the figurine.
end

## Turn-Ins



if **You turn in:** [Acrylia Slate of Shar Vahl](/item/2877)


>**Merchant Ayyad says:** Some of my wares are spoiling and I must place them in a container to preserve them. I cannot afford to take the loss that would result if they were to rot. Please Soandso, take this bowl and combine two lumps of gray mud with a flask of water and xakra bile. Take the resulting clay and this sketch with another water flask to fashion an unfired gray jar. Fire it in a kiln with a firing sheet and return to me with the product as soon as you can.


 **You receive:** None 

elseif **You turn in:** [Gray Jar](/item/3498)


>**Merchant Ayyad says:** Excellent! Please accept this knapsack as payment for your trouble. Here is my seal as well. I can always use more jars and if you give me four of my seals I will share with you a family secret.


 **You receive:** None 

elseif **You turn in:** [Ayyad's seal](/item/3499), [Ayyad's seal](/item/3499), [Ayyad's seal](/item/3499), [Ayyad's seal](/item/3499)


>**Merchant Ayyad says:** Excellent, Soandso, few of our kind show a true interest in the more refined arts of pottery these days. It is very good to see the young people taking interest in the old arts. Here is a Basic Runequill Set. Take the instruments in the set and practice marking runes on the gray jars that you previously brought to me. To etch the runes, simply cover a gray jar with some Xakra bile and use the Runequill Set to etch the runes on to the jar. You'll want to fire them in a kiln when you're finished. When those jars become trivial come back and give me those basic tools and we'll see about upgrading them.


 **You receive:**  [Basic Runequill Set](/item/3631) 

elseif(e.other:GetRawSkill(69) >= 100 and  **You turn in:** [Basic Runequill Set](/item/3631)


>**Merchant Ayyad says:** You're progressing nicely, Soandso. Take this sculpting tool and add it to the set you already have. This new quill set will be able to make some very nice urns that should help ease the burden of moving all that heavy clay around. Take a gray jar and use the new set of tools I've given you to etch Xakra blood into runes on the side of the jars. These should prove to be very useful in your labors in the future. Once you have mastered those runes, bring back your runequill set to me for another addition.


 **You receive:**  [Novice's Runequill Set](/item/3632) 

elseif(e.other:GetRawSkill(69) > 100 and  **You turn in:** [Novice's Runequill Set](/item/3632)


>**Merchant Ayyad says:** You're progressing nicely, Soandso. Take this sculpting tool and add it to the set you already have. This new quill set will be able to make some very nice urns that should help ease the burden of moving all that heavy clay around. Take a gray jar and use the new set of tools I've given you to etch Xakra blood into runes on the side of the jars. These should prove to be very useful in your labors in the future. Once you have mastered those runes, bring back your runequill set to me for another addition.


 **You receive:** None 

elseif **You turn in:** [Fareed's Note to Ayyad](/item/3643)


>**Merchant Ayyad says:** Welcome back Soandso, I trust you behaved well in the presence of the king's servants. It seems Fareed was very impressed with your work, as he has instructed me to give you a very nice reward. Here, take this Urn, it will surely prove very useful to you as you continue your study of the molding of the earth. Oh, I almost forgot to tell you, Grilo the mason was here earlier looking for you, he has heard of your talents and believes that you might do well in the school of masonry as well. Seek him out.


 **You receive:**  [Ayyad's Runed Urn](/item/17107) 

**This NPC *should* return incorrect items given.**

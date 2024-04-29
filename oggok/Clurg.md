# Clurg
## Dialog

**You say:** `hail`



>**Clurg says:** Hello, friend. Have a drink. I have some [unique drinks]. Try one. And remember. You get rowdy, the [Bouncers] crush you.

**You say:** `bouncers`



>**Clurg says:** The Bouncers were organized by me. As I traveled to many of the world's taverns I encountered great enforcers called bouncers. It was their duty to keep order amongst chaos. When I returned and rose to greatness after the creation of the [Flaming Clurg]. I organized the Oggok Bouncers to keep order amongst the [rival guilds].

**You say:** `flaming clurg`



>**Clurg says:** The Flaming Clurg was my greatest creation. It brought me great respect in Oggok. Unfortunately, I have heard tales of an [imposter drink].

**You say:** `imposter drink`



if **Faction** >= Indifferent +50 then 



>**Clurg says:** I have heard there is a barkeep who dares to sell a similar drink in Neriak's Foreign Quarter. I have put a price on his head. Anyone who returns with his head shall be greatly rewarded.


elseif **Faction** >= Indifferent then




>**Clurg says:** Find ways to help all in Oggok. Then we will have conversation.


else



>**Clurg says:** You are brave. An enemy are you of Oggok. Leave while you still can.








**You say:** `rival guilds`



>**Clurg says:** Oggok has been the battleground for the feud between the Greenblood knights and shamans and the Craknek warriors. It is fueled by the superior intellect of the Greenbloods. Few remember that I, Clurg, was once dim, but now I speak with great words.

**You say:** `unique drinks`



>**Clurg says:** I have been all over Norrath and even served with some very great [barkeeps in Freeport]. I am the creator of both [Flaming Clurg] and Ogre Swill.

**You say:** `barkeeps in freeport`



>**Clurg says:** Yes. I have journeyed to many taverns, but it was in Freeport that I acquired most of my art. I compiled all my drink recipes in a [special book].


**You say:** `special book`



if **Faction** >= Indifferent +50 then 




>**Clurg says:** I compiled all my drinks into one book. I lost this book while in Freeport. No doubt some barkeep is experimenting with it. I would pay dearly for the return of my Barkeep Compendium.


elseif **Faction** >= Indifferent then




>**Clurg says:** Find ways to help all in Oggok. Then we will have conversation.


else



>**Clurg says:** You are brave. An enemy are you of Oggok. Leave while you still can.








end

## Turn-Ins




if **Faction** >= Indifferent +50 and  **You turn in:** [Barkeep Compendium](/item/13379)) then 


>**Clurg says:** Ahhh!! My Barkeep Compendium has been returned!! I am in your debt. I do not like to be in any man's debt. Let me offer you this as payment for your great service. Obtaining my book could not have been a simple task.





* __Faction:__ [Clurg](/faction/228) (50)


* __Faction:__ [Kazon Stormhammer](/faction/274) (-50)


* __Faction:__ [Green Blood Knights](/faction/261) (50)


* __Faction:__ [Craknek Warriors](/faction/232) (50)


* __Faction:__ [Oggok Guards](/faction/337) (50)


 **You receive:**  [Stein of Moggok](/item/13380) (+500 exp)

elseif **Faction** >= Indifferent +50 and  **You turn in:** [Ogre Head](/item/13378)) then 


>**Clurg says:** Haha! He shall mix no more Flaming Pungla's! I shall drink from his rotting skull tonight. As for you, take this and call it yours. Consider yourself a friend of Clurg.





* __Faction:__ [Clurg](/faction/228) (15)


* __Faction:__ [Kazon Stormhammer](/faction/274) (-15)


* __Faction:__ [Green Blood Knights](/faction/261) (15)


* __Faction:__ [Craknek Warriors](/faction/232) (15)


* __Faction:__ [Oggok Guards](/faction/337) (15)


 **You receive:** eq.ChooseRandom( [Large Ringmail Sleeves](/item/3132), [Large Ringmail Coat](/item/3128), [Large Ringmail Gloves](/item/3134), [Large Ringmail Pants](/item/3135), [Large Ringmail Boots](/item/3136), [Star Rose Quartz](/item/10021), [Pearl](/item/10024), [Ogre War Maul](/item/6302), [A Crude Stein](/item/13355), [Warhammer](/item/6006)) (+500 exp)

else


e.other:Say("I am no dumb ogre. I take gift when handed.");



**This NPC *should* return incorrect items given.**






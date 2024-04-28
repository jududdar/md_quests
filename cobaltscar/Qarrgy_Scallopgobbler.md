# Qarrgy Scallopgobbler
## Dialog

**You say:** `hail`



>*Qarrgy Scallopgobbler sets down several large crustacean shells covered in foreign runes, then extends his large, coarse hands in a gesture of friendship. 'I am pleased to see friendly visitors to our villages. I am the head craftsman of the village. The crustacean shell armor worn by the warriors of our village was crafted by me and by my apprentices. I will craft other materials as well when they are available.'*

**You say:** `crustacean shell armor`



>**Qarrgy Scallopgobbler says:** It takes awhile to make each piece. It has to go through a long burning process to clean away all old meat and dirt. Then it needs shaping and etching with runes.

**You say:** `burning process`



>**Qarrgy Scallopgobbler says:** Usually I use a mixture made from the livers of barraccudas. Their liquids are very strong and make good burning liquid. If you want some you need to bring me two barraccuda livers.

**You say:** `other material`



>**Qarrgy Scallopgobbler says:** I am able to craft dragon scale armor but it has been a long time since I have had the opportunity to do so for my people. What kind of scales do you wish for me to craft?
 
**You say:** `emerald dragon scale`



>**Qarrgy Scallopgobbler says:** I will craft an emerald dragonscale tunic for emerald dragon scales, ulthork tusks, and an unstained fine plate breastplate.

**You say:** `sea dragon scale`



>**Qarrgy Scallopgobbler says:** Should you slay Kelorek'Dar, the sea dragon, I would craft you a sea dragon bracer from his scales. All I ask for are the scales of the dragon, an ornately runed shell necklace, and an unstained bracer crafted of the metal you strange ones call fine steel.
end

## Turn-Ins



local text1 = "I'm sorry strange one. That is not a sufficient barter.";




if **You turn in:** [Barracuda Liver](/item/30059), [Barracuda Liver](/item/30059)


>*Qarrgy Scallopgobbler slams a knife into the various livers and squeezes out all of their various goos and juices.  Eventually he separates a bit of it and pours it into a protective bladder.  'Excellent work.  This good catch.  Here, you have sack of ooze.  Its good for burning things off or etching metals.  Thank you for your help.*


 **You receive:**  [Bladder of Acidic Ooze](/item/30060) 

elseif **You turn in:** [Emerald Dragon Scales](/item/22823), [Ulthork Tusks](/item/24874), [Fine Plate Breastplate](/item/21004)


>*Qarrgy Scallopgobbler skillfully crafts the Emerald Dragon Scales into a tunic, hands it to Soandso, and claps enthusiastically.*


* __Faction:__ [Othmir](/faction/432) (5)


* __Faction:__ [Ulthork](/faction/431) (-1)


 **You receive:**  [Emerald Dragonscale Tunic](/item/11635) (+5000 exp)

elseif **You turn in:** [Sea Dragon Scales](/item/22814), [Ornately Runed Shell Necklace](/item/28515), [Fine Plate Bracer](/item/21009)


>*Qarrgy Scallopgobbler skillfully crafts the Sea Dragon Scales into a bracer, hands it to Soandso, and claps enthusiastically.*


* __Faction:__ [Othmir](/faction/432) (5)


* __Faction:__ [Ulthork](/faction/431) (-1)


 **You receive:**  [Sea Dragonscale Bracer](/item/11589) (+5000 exp)

**This NPC *should* return incorrect items given.**

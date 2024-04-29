# Zimloro Jalobottle
## Dialog

**You say:** `hail`



>**Zimloro Jalobottle says:** Oi there, Soandso. If you are lookin for a potion or an antidote I got just what the doctor ordered. Step right up! I also have many other special potions but sadly I do not have the correct [components] for them.

**You say:** `retrieve.* component`



>**Zimloro Jalobottle says:** Fantastic, Soandso! Elefan, my apprentice, is currently studying under my wing. He had been collecting samples in Shadeweaver lately and he probably has the items that I need. If you could go and speak with him and present him with this ingredient list, hopefully he will have what I need. Please bring the components back to me as soon as possible!


**You receive:**  [Zimloro Ingredient List](/item/4758)

**You say:** `components`



>**Zimloro Jalobottle says:** Well you see I can make some very magnificent potions. Unfortunately, I am in need of a few [ingredients] that I lost in a lab accident a few days back.

**You say:** `ingredient`



>**Zimloro Jalobottle says:** You sure seem interested in my work there, Soandso. So interested that I think you would be willing to go fetch the components I require for my studies for me! Am I correct? Will you [retrieve these components] for me?
end

## Turn-Ins





if( **You turn in:** [Antidote Ingredients](/item/4759)) then


>**Zimloro Jalobottle says:** You did it, Soandso! Finally I can finish these potions that I have been working on for such a long time. I will surely tell all of my friends of your willingness to help me!


* __Faction:__ [House of Stout](/faction/1512) (5)


* __Faction:__ [Traders of the Haven](/faction/1508) (1)


 **You receive:** 0 (+5000 exp)

elseif( **You turn in:** [Antidote Supplies](/item/4765)) then


>**Zimloro Jalobottle says:** Ah, of course, the antidote supplies I have been waiting for from Daksins. I hope he is ok, we all told him it was not wise to go out to the cursed mountains alone. I thank you for bringing me these supplies because Daksins was unable too. There have been many reports lately of people receiving the disease carried by the beasts you encountered. Should you come across these extracts in the future bring them to me if you like. Thank you again, your actions will not go unnoticed.





* __Faction:__ [House of Stout](/faction/1512) (25)


* __Faction:__ [Traders of the Haven](/faction/1508) (2)


 **You receive:** 0 (+5000 exp)

**This NPC *should* return incorrect items given.**

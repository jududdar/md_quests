# Walthin Fireweaver


## Dialog

if **Faction** >= Indifferent then


**You say:** `hail`




>**Walthin Fireweaver says:** Greetings, Soandso. I am Walthin Fireweaver of the Temple of Solusek Ro. I am the protector of an ancient armor invented by long dead bards of the temple. This armor will help any bard in their journey across Norrath. Are you a bard that would desire to own some of this armor?


**You say:** `no`




>**Walthin Fireweaver says:** Very well.


**You say:** `yes`




>**Walthin Fireweaver says:** Very well. I craft a type of bardic armor that I invented called Lambent Armor. I can craft for you [boots], [gauntlets], and [greaves]. My friend Cryssia Stardreamer will craft for you the other pieces. I require a special kind of lambent stone for each of my armor pieces.  Find my friends Orstorm, Genni, Gardern, and Vilissia within the temple and they will help you create them.


**You say:** `boots`




>**Walthin Fireweaver says:** Alright, I will require some items. Go and get me some Firewalker Boots, a Lambent Sapphire, and the middle piece of the Rune of the One Eye. Return to me with these items and I will craft your boots.


**You say:** `gauntlets`




>**Walthin Fireweaver says:** Alright, I need you to retrieve for me some Black Silk Gloves, a Lambent Star Ruby, and Shin Gauntlets. Return to me with these and I will craft your gauntlets.


**You say:** `greaves`




>**Walthin Fireweaver says:** Very well, return to me with these items and I will craft them. A set of Icy Greaves, a Lambent Fire Opal, and Shin Greaves.


else


**Walthin Fireweaver says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins



local text = "Wait, Soandso, are you not forgetting something?";



if **Faction** >= Indifferent and  **You turn in:** [Firewalker Boots](/item/2318), [Lambent Sapphire](/item/10119), [Rune of the One Eye](/item/10561)) then


>**Walthin Fireweaver says:** Quality boots for a quality bard. Well done, Soandso.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (10)




* __Faction:__ [Shadowed Men](/faction/416) (-1)
   


 **You receive:**  [Lambent Boots](/item/4159) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Black Silk Gloves](/item/2319), [Lambent Star Ruby](/item/10117), [Shin Gauntlets](/item/4114)) then


>**Walthin Fireweaver says:** Well done, Soandso, you have justly earned your pair of lambent gauntlets.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (10)




* __Faction:__ [Shadowed Men](/faction/416) (-1)
   


 **You receive:**  [Lambent Gauntlets](/item/4157) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Icy Greaves](/item/4115), [Lambent Fire Opal](/item/10128), [Shin Greaves](/item/4116)) then


>**Walthin Fireweaver says:** I always knew that you would earn these lambent greaves, Soandso, you just had that look about you. Well done!


* __Faction:__ [Temple of Solusek Ro](/faction/415) (10)




* __Faction:__ [Shadowed Men](/faction/416) (-1)
   


 **You receive:**  [Lambent Greaves](/item/4158) (+1000 exp)

**This NPC *should* return incorrect items given.**

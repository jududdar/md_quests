# Manik Compolten
## Dialog

**You say:** `hail`



>**Manik Compolten says:** Greetings, young one. I am Manik Compolten, High Watchman. Are you a [new warrior] or an [experienced fighter]?

**You say:** `new warrior`



if **Faction** >= Amiable then



>**Manik Compolten says:** It is always good to see new blood amongst the Gemchoppers. I have a small task for you. Take this keycard. I will give you only one at a time. Use each to obtain blackboxes for the C series clockworks. I am sure you are familiar with the clockworks. When you are done, bring them all to me. Let me know if you need another keycard.



**You receive:**  [Shiny Card](/item/13844)


elseif( **Faction is** == Indifferent) then



>**Manik Compolten says:** You must show a greater allegiance to the Gemchoppers before we can speak with you. Search the hills for rogue clockworks. Captain Compolten shall accept two of their blackboxes and you shall prove your loyalty to our hall.


else



>**Manik Compolten says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `another keycard`



if **Faction** >= Amiable then



>**Manik Compolten says:** Here. Remember, I will give you only one keycard at a time. These keycards only work for the C series clockworks.



**You receive:**  [Shiny Card](/item/13844)


elseif( **Faction is** == Indifferent) then



>**Manik Compolten says:** You must show a greater allegiance to the Gemchoppers before we can speak with you. Search the hills for rogue clockworks. Captain Compolten shall accept two of their blackboxes and you shall prove your loyalty to our hall.


else



>**Manik Compolten says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `experienced fighter`



if **Faction** >= Amiable then



>**Manik Compolten says:** Good. I require your talents to destroy rogue clockworks. After we sent the clockworks to destroy the Asylum of the Mad we found some of the clockworks went haywire and never returned. We must destroy them, not for the safety of the people, but to keep our technology from falling into the hands of any other nation. Go to the Steamfont Mountains and return their rogue blackboxes to me.


elseif( **Faction is** == Indifferent) then



>**Manik Compolten says:** You must show a greater allegiance to the Gemchoppers before we can speak with you. Search the hills for rogue clockworks. Captain Compolten shall accept two of their blackboxes and you shall prove your loyalty to our hall.


else



>**Manik Compolten says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `clockwork`



>**Manik Compolten says:** The clockworks were developed by the Eldritch Collective. They are used as our policing force in Ak'Anon. They come in many series. The letter following their number is the series model.

**You say:** `blackbox`



>**Manik Compolten says:** All the clockworks contain blackboxes. These are not containers for items, but rather containers of data of all the clockwork's experiencees. The data can only be extracted by using a blackbox definer.

**You say:** `red 5`



>**Manik Compolten says:** Red 5 is the infernal clockwork once owned by the mad gnome, Meldrath. I hear he has survived the scrap heap and is active once more. I offer a reward to all gnome warriors for the return of Red 5's Blackbox. Perhaps even the reward of a [Bull Smasher].

**You say:** `bull smasher`



>**Manik Compolten says:** The war hammer, Bull Smasher was crafted by our great blacksmiths and tinkers. It is not magical, but it is weighted to perform for only the short of stature. Certainly an item like Bull Smasher could only be crafted by gnomes.

**You say:** `meldrath`



>**Manik Compolten says:** Meldrath is the mad gnome.  He used to be a member of the Eldritch Collective.  Some say he lost his mind while he was working on a formula he obtained from other worlds.  He used to lead the cult called the [Asylum of the Mad].

**You say:** `asylum`



>**Manik Compolten says:** The Asylum of the Mad was formed by the mad gnome, Meldrath. Under his direction, they were trying to build some giant mechanical titan.  We recently sent all of our clockworks into the Steamfont Mountains to destroy their evil cult.
end

## Turn-Ins



local text = "Only two blackboxes shall prove your worth to this hall.";

local text1 = "There are a total of four C series clockworks.";



if **Faction** >= Amiable and  **You turn in:** [Rusted Blackbox](/item/13208), [Rusted Blackbox](/item/13208)) then


>**Manik Compolten says:** Excellent work! You were born to be a warrior. Here is a little bonus for the good job.





* __Faction:__ [Gem Choppers](/faction/255) (5)



* __Faction:__ [King Ak`Anon](/faction/333) (1)



* __Faction:__ [Merchants of Ak`Anon](/faction/288) (1)



* __Faction:__ [Clan Grikbar](/faction/1604) (-1)



* __Faction:__ [Dark Reflection](/faction/238) (-1)



**Experience:** Awards 15% experience at level 1.


 **You receive:** None 

elseif **Faction** >= Amiable and  **You turn in:** [Blackbox XIIC](/item/13212), [Blackbox XXVIC](/item/13211), [Blackbox XVIIC](/item/13213), [Blackbox XXVIIC](/item/13214)) then


>**Manik Compolten says:** Ah!! I see you had no problem finding all of the C series clockworks. Good work. Here. Take this blackbox. We received it from Clockwork 27C. Take it to Jogl Doobraugh. He is the operator of the only blackbox definer in Ak'Anon. He is out at the windmills checking on their operation.





* __Faction:__ [Gem Choppers](/faction/255) (1)



* __Faction:__ [King Ak`Anon](/faction/333) (1)



* __Faction:__ [Merchants of Ak`Anon](/faction/288) (1)



* __Faction:__ [Clan Grikbar](/faction/1604) (-1)



* __Faction:__ [Dark Reflection](/faction/238) (-1)



**Experience:** Awards 12% experience at level 1.


 **You receive:**  [Blackbox XXVIIC](/item/13209) 

elseif **Faction** >= Amiable and  **You turn in:** [Rusted Blackbox](/item/13215)) then


>**Manik Compolten says:** This is fabulous news!! You have done well, young one. Once you are ready for [further instruction] please let me know, I will guide you through your early most dangerous days. When you have become more experienced in our art, I wil be able to further instruct you on how to progress through your early ranks, as well as in some various [trades] you will have available to you.





* __Faction:__ [Gem Choppers](/faction/255) (10)



* __Faction:__ [King Ak`Anon](/faction/333) (2)



* __Faction:__ [Merchants of Ak`Anon](/faction/288) (2)



* __Faction:__ [Clan Grikbar](/faction/1604) (-2)



* __Faction:__ [Dark Reflection](/faction/238) (-1)



**Experience:** Awards 14% experience at level 1.


if(math.random(100) < 20) then



 **You receive:** eq.ChooseRandom( [Bull Smasher](/item/13219), [Iony's Absorber](/item/13220)) 


else



 **You receive:** eq.ChooseRandom( [Small Cloth Cap](/item/1013), [Small Cloth Cape](/item/1018), [Small Cloth Choker](/item/1015), [Small Cloth Cord](/item/1019), [Small Cloth Gloves](/item/1022), [Small Cloth Pants](/item/1023), [Small Cloth Sandals](/item/1024), [Small Cloth Shawl](/item/1017), [Small Cloth Shirt](/item/1016), [Small Cloth Sleeves](/item/1020), [Small Cloth Veil](/item/1014), [Small Cloth Wristband](/item/1021)) 




**This NPC *should* return incorrect items given.**

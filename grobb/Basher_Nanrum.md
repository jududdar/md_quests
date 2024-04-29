# Basher Nanrum




## Dialog

**You say:** `hail`



>**Basher Nanrum says:** Peh! What am you wanted?! I am Basher Nanrum. You? Soandso ? Heh, you look for works? Hmm, me tinks you too weakling for [job] me need done. Hmm.. You might do, mebbe.

**You say:** `skeleton`



>**Basher Nanrum says:** Yeah! Me see dat bone man. He over by da Cleaver. He tink he a butcher or sumting!


**Spawn NPC:**  [\#a skeleton](/npc/52125) at (**y:** 361, **x:** -466)



**You say:** `job`



>**Basher Nanrum says:** Me in charge of making torches for basher patrols. But Nanrum is much too mighty for such stupid job and Nanrum get idea. Dem fire bugses in da desert - dem eyes glowed. And dem don't burneded like torches. If Soandso getted Nanrum three fire beetle eyes me would giveded Soandso a shiny thingie dat you wanteded. Go ahed, Soandso , an' get me da eyes.

**You say:** `armor`



>**Basher Nanrum says:** Chain, plate, leather, Krung's Clubs and Junk inside you will find.  Grobb, in the center it be.

**You say:** `warrior guild`



>**Basher Nanrum says:** Da bashers warriors of Grobb close to entrance they be.

**You say:** `supplies`



>**Basher Nanrum says:** Entrance toward the front and right.  Gunthak's Belch inside you will find.

**You say:** `bank`



>**Basher Nanrum says:** Back, back to the rear, bank you will find.

**You say:** `tavern`



>**Basher Nanrum says:** Gunthak's Belch toward entrance.

**You say:** `food`



>**Basher Nanrum says:** If hungry you be Gunthak's Belch to entrance and side you will find.

**You say:** `shaman guild`



>**Basher Nanrum says:** Shaman of Grobb called the Darkones.  Back towards Carver is where you will find.

**You say:** `darkone`



>**Basher Nanrum says:** The Darkones to the back found are they.  Shaman of Grobb they be.

**You say:** `inn`



>**Basher Nanrum says:** Rocks and ground upon which you will lay.  No inn inside Grobb you will find.

**You say:** `shadowknight guild`



>**Basher Nanrum says:** Shadowknights of Knightkeep guild of shadowknights they be.  To the side and middle is where you find.
end

## Turn-Ins



local text = "Well dat be some of da eyeballses I askeded for. But I you needs ta give me three for da shiny.";



if ( **You turn in:** [Fire Beetle Eye](/item/10307), [Fire Beetle Eye](/item/10307), [Fire Beetle Eye](/item/10307)) then


>**Basher Nanrum says:** Heh heh. All da eyeballses! I didn't think ya could do it but ya did. Here is da shiny. If you gets more I always have more shinies.


* __Faction:__ [Da Bashers](/faction/235) (1)


* __Faction:__ [Broken Skull Clan](/faction/222) (-1)


 **You receive:** eq.ChooseRandom( [Brass Earring](/item/10351), 10026, 10060, 10018, 10006, 10017) (+1000 exp)

**This NPC *should* return incorrect items given.**

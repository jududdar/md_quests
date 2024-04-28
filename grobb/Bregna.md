# Bregna



## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then 



>**Bregna says:** Hail, Soandso, are ya a follower ob Innoruuk?  I hopes so.  We needs many ta spread His Hate.  None be as bicious as be dem dat follow Him.  We do brings fear and hate ta all dat does sees us.  Dis is well.  He likes it.  Can ya [help]?


else



>**Bregna says:** You die! Me Darkone!  We no frend to you.  You run now!



**You say:** `help`



if **Faction** >= Indifferent then 






>**Bregna says:** Me hears orcs nearby are trubble.  Da werd frum Neriak is dey wants us ta kills dem before dey organize.  Dark elf say ta looks for Deathfist Clan.  Say dey called cen-tu-ri-ons.  Dey try ta gets big orc army.  Shows me ya can strike fear and hate inta dem orcs... dey needs be more scared a us den dem humies.  Brings me a Deathfist slashed belt.


else



>**Bregna says:** You die! Me Darkone!  We no frend to you.  You run now!



end

## Turn-Ins



if  **Faction** >= Indifferent and  **You turn in:** [Deathfist Slashed Belt](/item/13916)


>**Bregna says:** Good job. Dat help lerns um. Takes dis ta help ya lerns how ta do more hateful tings. Ya gots a good starts fer Him ta be prouds a ya


* __Faction:__ [Dark Ones](/faction/237) (5)


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (1)


* __Faction:__ [Frogloks of Guk](/faction/251) (-1)


 **You receive:**  [Spell: Spirit Pouch](/item/15272) (+50 exp)

elseif  **You turn in:** [A Blood Raven Tailfeather](/item/26632), [A Wrulon Claw](/item/26640), [Arachnae Fangs](/item/29921), [Swirling Banshee Essence](/item/26662)


>**Bregna says:** Dis am gud. I see you've been talkin' to Garuuk. Methanks you fer da help. Take dis note back ta Garuuk so he knows you helped me. Tanks again!


* __Faction:__ [Dark Ones](/faction/237) (10)


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (2)


* __Faction:__ [Frogloks of Guk](/faction/251) (-1)


 **You receive:**  [Troll Receipt](/item/28740) (+1000 exp)

**This NPC *should* return incorrect items given.**

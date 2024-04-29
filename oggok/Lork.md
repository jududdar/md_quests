# Lork
## Dialog

**You say:** `hail`



>**Lork says:** You Soandso. We hear of you. We need help. You [help Crakneks] or you [help self]?

**You say:** `help crakneks`



if **Faction** >= Amiable then 



>**Lork says:** Ha!! We hear of great adventurer. You?!! Me no think so. You prove self to Crakneks before you help us. Go to Innoth.. Innotu.. Innooth.. Arghh!! You go to outside Oggok. Find fat alligator bit Lork brother in two. Bring brother, Nork, body back. Then me know you strong.


elseif **Faction** >= Indifferent then




>**Lork says:** You help Crakneks more. Helps Horgus you must.  Den we trusts yoo!


else



>**Lork says:** Me smell the blood of Craknek enemy. Hey! It you!



**You say:** `help self`



>**Lork says:** You help self to leave Oggok before me bash you. We no need cowards.

**You say:** `uglan`



if **Faction** >= Amiable then 



>**Lork says:** Uglan brave warrior of Oggok. He now in Neriak. Work for dark elves. He NO LIKE dark elves!! He work because we make him. He spy for Crakneks.


elseif **Faction** >= Indifferent then




>**Lork says:** You help Crakneks more. Helps Horgus you must.  Den we trusts yoo!


else



>**Lork says:** Me smell the blood of Craknek enemy. Hey! It you!



**You say:** `help self`



>**Lork says:** You help self to leave Oggok before me bash you. We no need cowards.
end

## Turn-Ins



local text = "This one dead. Where other? Lork say Crushbone heart and Oggok heart.";



if( **You turn in:** [Intricate Toothed Ring](/item/20523)) then


>**Lork says:** Ay danks. Take dis to Uglan.


 **You receive:**  [A Stein](/item/16547) 

elseif **Faction** >= Amiable and  **You turn in:** [Ogre Arm](/item/13356)) then


>**Lork says:** Ahhh!! Boohoohoo. Nork!! That you arm. Me will take care of you now. Thank you for killing gator. You must be strong. Now you help Crakneks. We hear.. ohh, poor Nork, we hear trouble begins. Find ogre warrior [Uglan]. Give him this. It broken. He know where you from. Go. Nork.. Poor Nork.


* __Faction:__ [Craknek Warriors](/faction/232) (10)


* __Faction:__ [Clurg](/faction/228) (1)


* __Faction:__ [Green Blood Knights](/faction/261) (-1)


 **You receive:**  [A Cracked Stein](/item/13357) (+500 exp)

elseif **Faction** >= Amiable and  **You turn in:** [A Sealed Letter](/item/18840)) then


>**Lork says:** What this!! So, dark elves think they can bash ogres. Replace with blue orcs. Dumb Zulort friend with dark elf ambassador in Oggok. We kill him. We kill Crushbone dark elf ambassador also. This slow down plan. We need a hero. Me guess you do. You go. Go bring Lork both Crushbone and Oggok dark elf hearts. Then you be hero.


* __Faction:__ [Craknek Warriors](/faction/232) (10)


* __Faction:__ [Clurg](/faction/228) (1)


* __Faction:__ [Green Blood Knights](/faction/261) (-1)


 **You receive:** eq.ChooseRandom( [Bronze Two Handed Sword](/item/5030), [Bronze Two Handed Hammer](/item/6021)) (+500 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Black Heart](/item/13358), [Black Heart](/item/13227)) then


>**Lork says:** That show dark elves who strongest. Me hope you kill many blue orcs. You Craknek Hero now. You take this. It mine. Hero reward. You great ogre now. Smash best.


* __Faction:__ [Craknek Warriors](/faction/232) (25)


* __Faction:__ [Clurg](/faction/228) (3)


* __Faction:__ [Green Blood Knights](/faction/261) (-3)


 **You receive:** eq.ChooseRandom( [Gatorsmash Maul](/item/13359), [A Crude Stein](/item/13355), [Large Patchwork Boots](/item/2136), [Large Patchwork Cloak](/item/2130), [Large Patchwork Pants](/item/2135), [Large Patchwork Sleeves](/item/2132), [Large Patchwork Tunic](/item/2128)) (+500 exp)

**This NPC *should* return incorrect items given.**






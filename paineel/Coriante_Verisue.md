# Coriante Verisue
## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then 



>**Coriante Verisue says:** Greetings, young one! There are many tasks to be performed aside from your studies to truly harness the powers passed down to us by our ancestor [Miragul]. The most basic of these tasks is the gathering of bat wings and snake fangs from the yard outside our city. I will reward you for every two bat wings and two snake fangs you bring to me.


else



**Coriante Verisue says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `miragul`



if **Faction** >= Apprehensive then 



>**Coriante Verisue says:** You do not know of Miragul?!! You have more to learn of the heritage of the Dark Truth than at first I thought. Miragul was the first High Man to unlock the secrets of necromancy and is the founder of our city as well as the creator of the treacherous Hole.


else



**Coriante Verisue says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



local text = "You must gather all four of the required items in order to receive your reward. I expect more reliability from you in the future."



if( **You turn in:** [Dark Truth Guild Note](/item/18018)) then 


>**Coriante Verisue says:** You are welcomed into the fold.  Now go out, and prove yourself, young one.  You have much to learn about the Dark Truth.


* __Faction:__ [Heretics](/faction/265) (100)


* __Faction:__ [Deepwater Knights](/faction/242) (-100)


* __Faction:__ [Gate Callers](/faction/254) (-100)


* __Faction:__ [Craftkeepers](/faction/231) (-100)


* __Faction:__ [Crimson Hands](/faction/233) (-100)


 **You receive:**  [Dirt Soiled Robe*](/item/13551) (+20 exp)

elseif **Faction** >= Apprehensive and  **You turn in:** [Bat Wing](/item/13068), [Bat Wing](/item/13068), [Snake Fang](/item/13067), [Snake Fang](/item/13067)) then 


>**Coriante Verisue says:** Very good, young acolyte. Maintain your diligence in your duties and you will quickly learn the secrets of the Dark Truth.


* __Faction:__ [Heretics](/faction/265) (2)


* __Faction:__ [Craftkeepers](/faction/231) (-2)


* __Faction:__ [Crimson Hands](/faction/233) (-2)


* __Faction:__ [Deepwater Knights](/faction/242) (-2)


* __Faction:__ [Gate Callers](/faction/254) (-2)


 **You receive:** eq.ChooseRandom( [Spell: Cavorting Bones](/item/15338), [Spell: Locate Corpse](/item/15342)) (+5000 exp)

**This NPC *should* return incorrect items given.**

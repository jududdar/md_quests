# Trizam N-Tan
## Dialog

**You say:** `hail`



>**Trizam N-Tan says:** And who do you think you are? To step into the Cauldron of Hate one should have the black soul of a warrior. For one to speak with Trizam he should have good reason. Perhaps you return with tales of [deathfist] agendas. If so, then you're a year too late.

**You say:** `deathfist`



if **Faction** >= Amiable then



>**Trizam N-Tan says:** Have you been spending day and night at the Malden's Fancy?!! The Deathfist Orcs in the Commonlands are up to something. As the inept humans in Freeport hunt down the warrior orcs, the pawns run about on some secret mission. I have been appointed by King Nathox to attend to this matter and hire young warriors who wish to [collect] pawn kills.


elseif **Faction** >= Indifferent then



>**Trizam N-Tan says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Trizam N-Tan says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `collect`



if **Faction** >= Amiable then



>**Trizam N-Tan says:** Yes, You will. You need not know the reason why. I command you by order of King Naythox Thex to venture forth to the Commonlands and slay all the orc pawns you see. Return with four pawn picks and maybe I shall even reward you. Leave at once or you shall find yourself hanging from the Hooks of Innoruuk!


elseif **Faction** >= Indifferent then



>**Trizam N-Tan says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Trizam N-Tan says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.



end

## Turn-Ins



local text = "I instructed you to return with no fewer than four pawn picks!";



if **Faction** >= Amiable and  **You turn in:** [Orc Pawn Pick](/item/13885), [Orc Pawn Pick](/item/13885), [Orc Pawn Pick](/item/13885), [Orc Pawn Pick](/item/13885)


>**Trizam N-Tan says:** So you have done your part to serve the King. As instructed, I shall reward your good deed. But I choose to reward you with provisions from the pantries of Neriak. They shall keep you strong.


* __Faction:__ [Indigo Brotherhood](/faction/270) (10)


* __Faction:__ [Emerald Warriors](/faction/326) (-1)


* __Faction:__ [Steel Warriors](/faction/311) (-1)


* __Faction:__ [Primordial Malice](/faction/1522) (-20)


 **You receive:** eq.ChooseRandom( [Rotgrub Rye](/item/13022), [Neriak Nectar](/item/13021)) (+1000 exp)

**This NPC *should* return incorrect items given.**









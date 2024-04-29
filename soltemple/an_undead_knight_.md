# an undead knight 


## Dialog

**You say:** `Hail`



>**an undead knight  says:** Leave this place or find yourself [bound to this land] as I am.

**You say:** `bound to this land`



>**an undead knight  says:** I was torn to pieces for my failure to complete a task for my master.  I lost my life, my precious [shadowknight armor] and most of all, my [lower body]!!

**You say:** `shadowknight armor`



>**an undead knight  says:** My darkforge armor!!  It was taken into the land of lizards by the lizardmen crusaders!!  It is worthless decayed armor now!! I cannot even wear it any more, but perhaps you can!!  Would you like me to make [darkforge armor] for you?

**You say:** `lower body`



>**an undead knight  says:** My lower body was taken from me, along with my hands.  I was pieced together using portions of other failed champions.  Now I can only create [darkforge armor] in the form of helms, breastplates, vambraces and bracers.

**You say:** `darkforge armor`



>**an undead knight  says:** Darkforge helms require my decayed helm and visor as well as two Freeport militia helms.  The breastplate requires the decayed breastplate, decayed mail and two enchanted platinum bars. Vambraces need both decayed vambraces and a Qeynos Guard kite shield.  The bracers require both decayed bracers and a horn from a minotaur lord.
end

## Turn-Ins



local text1 = "Two damaged Freeport Militia helms, the decayed helm and the decayed visor.";

local text2 = "The decayed breastplate, decayed mail and two enchanted platinum bars.";

local text3 = "The minotaur hero shackles and both right and left decayed bracers.";

local text4 = "A Qeynos kite shield and the right and left decayed vambraces.";



if( **You turn in:** [Decayed Helm](/item/12283), [Decayed Visor](/item/12284), [Damaged Militia Helm](/item/13921), [Damaged Militia Helm](/item/13921)) then


>**an undead knight  says:** You now own the darkforge helm.


 **You receive:**  [Darkforge Helm](/item/3140) (+5000 exp)

if( **You turn in:** [Decayed Breastplate](/item/12285), [Decayed Chainmail](/item/12286), [Enchanted Platinum Bar](/item/16507), [Enchanted Platinum Bar](/item/16507)) then


>**an undead knight  says:** I grant you the darkforge breastplate!!


 **You receive:**  [Darkforge Breastplate](/item/3141) (+5000 exp)

if( **You turn in:** [Decayed Left Vambrace](/item/12288), [Decayed Right Vambrace](/item/12287), [Qeynos Kite Shield](/item/9023)) then


>**an undead knight  says:** You now have the darkforge vambraces.


 **You receive:**  [Darkforge Vambraces](/item/3142) (+5000 exp)

if( **You turn in:** [Decayed Left Bracer](/item/12290), [Decayed Right Bracer](/item/12289), [Broken Minotaur Lord's Horn](/item/19075)) then


>**an undead knight  says:** You now own a darkforge bracer.


 **You receive:**  [Darkforge Bracer](/item/3143) (+5000 exp)

**This NPC *should* return incorrect items given.**







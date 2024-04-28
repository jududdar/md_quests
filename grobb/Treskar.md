# Treskar



## Dialog

**You say:** `hail`



>**Treskar says:** You dare speak to Master Treskar!  You be [sent by Hukulk] or you be hurtin'! Me have no time to waste with ugly one like you!

**You say:** `sent by hukulk`



>**Treskar says:** Ha!  Hukulk accept puny troll now?!  Ha!  You join us and you join fight.  Nightkeep enemy is Soandso enemy!  You help smash [other weak shadowknights].  Them weak.  We true power!  You bash good and maybe you do [secret mission] for Treskar.

**You say:** `other weak shadowknights`



if **Faction** >= Amiable then




>**Treskar says:** Other shadowknights is ogre shadowknights! They name is Greenbloods. They no match for Nightkeep! We tear arms from ogre bodies. You not as powerful as Treskar so you smash young Greenbloods. You hunt YOUNG members of Greenblood shadowknights. You bring me black shadow tunic and me share treasures from Nightkeep vault with puny Soandso. Go


elseif **Faction** >= Indifferent then



>**Treskar says:** Me talk to you 'bout dat when you do more to help Nightkeep!  Kill all Greenbloods!  Kill all froggies!


else



>**Treskar says:** <..Sniff, sniff, sniff..>  Me smell the blood of enemy in you.  You fool to talk to Nightkeep shadowknight!  Me bleed you if you no run!


**You say:** `secret mission`



if **Faction** >= Amiable then




>**Treskar says:** Nightkeep hear bashers see fungus man spore guardian at Innothule. Him protect young fungus man spores so they grow big, BIG an' attack trolls!! You go find spore guardian. Smash hi big red head!! Bring Treskar that huge mushroom head of his to prove he walk no more. You do this and me give you froglok skin mask.


elseif **Faction** >= Indifferent then



>**Treskar says:** Me talk to you 'bout dat when you do more to help Nightkeep!  Kill all Greenbloods!  Kill all froggies!


else



>**Treskar says:** <..Sniff, sniff, sniff..>  Me smell the blood of enemy in you.  You fool to talk to Nightkeep shadowknight!  Me bleed you if you no run!


end

## Turn-Ins



local text = "Me change mind! Me want total of THREE ogre black shadow tunics. Ha Ha! And you also pay two gold for Nightkeep tax! Ha! Ha!";




if **Faction** >= Amiable and  **You turn in:** [Huge Mushroom Head](/item/12190)


>**Treskar says:** You do it! You am great knight. Me give you special froglok skin mask. Shaman make for Nightkeep. It am make you smarter like Treskar... Me tink so!


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (20)



* __Faction:__ [Broken Skull Clan](/faction/222) (-3)



* __Faction:__ [Broken Skull Clan](/faction/222) (-5)



* __Faction:__ [Da Bashers](/faction/235) (1)



 **You receive:**  [Froglok Skin Mask](/item/2308) (+10000 exp)

elseif  **Faction** >= Amiable and  **You turn in:** [Black Shadow Tunic](/item/12199), [Black Shadow Tunic](/item/12199), [Black Shadow Tunic](/item/12199), gold = 2


>**Treskar says:** Hmm... You do good job. You surprise Treskar. Maybe you good after all. Maybe Treskar give you [secret mission]. Maybe not


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (20)



* __Faction:__ [Broken Skull Clan](/faction/222) (-3)



* __Faction:__ [Broken Skull Clan](/faction/222) (-5)



* __Faction:__ [Da Bashers](/faction/235) (1)



 **You receive:** eq.ChooseRandom( [Rusty Warhammer](/item/6014), 5023, 6013, 7009, 5013, 5021) (+1000 exp)

**This NPC *should* return incorrect items given.**

# Venox Tarkog
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Venox Tarkog says:** Welcome to the shrine of the Dismal Rage.  May [Innoruuk] guide your every move in life.  Here, we will teach you to release your rage unto the world.  My priests are at your disposal.


**You say:** `innoruuk`




>**Venox Tarkog says:** You do not even know the name of the Prince of Hate! That is a crime in here. Our god Innoruuk speaks with Pietro Zarn himself. It was Innoruuk who told him to create the Dismal Rage. You should speak with our family. Perhaps someone will help you better understand our beliefs.


**You say:** `bayle list`




>**Venox Tarkog says:** Oh. You must be the shadowknight who is to return the list to [Pietro Zarn]. The Bayle List is actually three scrolls with coded words. Alone they are nonsense. Together they can be decoded and tell something of value. Antonius Bayle had them created and gave them to three of his most trusted friends. Of these, I know Lady Shae, his old love. Then there is Captain Linarius Grafe, captain of the outer Qeynos Guards. Lastly, there is Frenway Marthank, Antonius Bayle's oldest friend. He is a resident of the Jaggedpine. When you recover the scrolls, you must take them to Rathmana Allin. He is a master scribe. He will decode the scrolls for us. He can be found in the deserts of South Ro. Now you'd best be off, before some other finds the scrolls. You must get there first and return the decoded list to Pietro Zarn.




elseif(eq.get_current_expansion() < 4.0) then


**You say:** `hail`




>**Venox Tarkog says:** Welcome to the shrine of the Dismal Rage.  May Innoruuk guide your every move in life.  Here, we will teach you to release your rage unto the world.  My priests are at your disposal.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 1.0 and  **You turn in:** [A tattered note](/item/18744)


>**Venox Tarkog says:** Here we find a new follower.. Here we find a tunic of the Dismal Rage. Put the two together and let the hate grow. Let it be known from now on that your soul belongs to the Prince of Hate, Innoruuk. It is his power which flows within you. Destroy all those who oppose us. Please introduce your hate to the others in this shrine.


* __Faction:__ [Dismal Rage](/faction/271) (100)


* __Faction:__ [Knights of Truth](/faction/281) (-15)


* __Faction:__ [Opal Darkbriar](/faction/296) (20)


 **You receive:**  [Faded Crimson Tunic*](/item/13561) (+20 exp)

**This NPC *should* return incorrect items given.**


# Captain Nealith
## Dialog

**You say:** `Hail`



>**Captain Nealith says:** Hail. adventurer!!  Stand tall and fight for the forest folk and all good races of Norrath. We shall claim this land for the kingdom of Thex!  My warriors shall not fail.  Already we patrol deep in the wilds of Kunark.  We welcome all mercenaries and urge adventurers to [join the defense of the outpost].


e.self:DoAnim(60);

**You say:** `join the defense`



e.self:Say("I salute you!!  Join the hunt.  Reports from the front line indicate a rise in the drolvarg
population.  Abandon your fear and slay these beasts for the greater good.  Already. they have taken far too many lives. even my sibling's!!  I shall pay you your wages upon the return of four drolvarg teeth.");


e.self:DoAnim(67);

**You say:** `sibling`



>*Captain Nealith appears saddened by the mention of his sibling. 'My brother Marltek has been missing for quite some time. I found coarse Drolvarg hair inside his tent which leads me to believe he has become a meal for the dogs. CURSE THE EVIL DOGS!! I shall see them all dead!!'*


e.self:DoAnim(28);
end

## Turn-Ins



local text = "holds the canine in his palm. 'Good work, but you will have to slay more than this to earn your wages.";



if( **You turn in:** [A Canine](/item/12977), [A Canine](/item/12977), [A Canine](/item/12977), [A Canine](/item/12977)) then


>*Captain Nealith tosses the teeth into a very large cask full of similar teeth. 'Fine work, Soandso. I wish all my own troops showed the same tenacity. I salute you. This will keep you well fed during your long patrols. Use your wages to better equip yourself. Continue the fight!! The General is pleased.'*





* __Faction:__ [Inhabitants of Firiona Vie](/faction/248) (5)


* __Faction:__ [Emerald Warriors](/faction/326) (3)


* __Faction:__ [Storm Guard](/faction/312) (3)


* __Faction:__ [Legion of Cabilis](/faction/441) (-1)


* __Faction:__ [Pirates of Gunthak](/faction/313) (-1)


 **You receive:**  [Elven Trail Mix](/item/13155) (+10000 exp)

elseif( **You turn in:** [blood soaked note](/item/18076)) then 


>*Captain Nealith nearly faints after reading the letter. 'Dear Marltek!! I shall miss you. There is more evil in this land!! Madness beyond description. Thank you Soandso. You put my soul at ease and give me new direction. Please accept my brothers blade. He found it in the wilds. May you use it to slay many Drolvarg!!'*


* __Faction:__ [Inhabitants of Firiona Vie](/faction/248) (5)


* __Faction:__ [Emerald Warriors](/faction/326) (3)


* __Faction:__ [Storm Guard](/faction/312) (3)


* __Faction:__ [Legion of Cabilis](/faction/441) (-1)


* __Faction:__ [Pirates of Gunthak](/faction/313) (-1)


 **You receive:**  [Glaive of Marltek](/item/12978) (+25580 exp)

**This NPC *should* return incorrect items given.**

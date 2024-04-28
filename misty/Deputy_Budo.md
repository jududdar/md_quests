# Deputy Budo
## Dialog

**You say:** `hail`



>**Deputy Budo says:** Hail, Soandso. I am Deputy Budo Bullnose, the squad leader of the Great Wall Patrol. Be very careful in the lands beyond the wall. They are filled with dangerous beasts, as well as [Clan Runnyeye].

**You say:** `clan Runnyeye`



>**Deputy Budo says:** Beyond this wall lies Runnyeye, the lair of the goblins of Clan Runnyeye. They have been a nuisance to Rivervale for quite some time. If you wish to join the fight, go to Rivervale and ask Sheriff Roglio about Clan Runnyeye.

**You say:** `I am reporting for duty`



if **Faction** >= Amiable then



>**Deputy Budo says:** Stand tall then, Deputy Soandso. Your orders are to keep the creatures from venturing into the community of Rivervale and to kill many goblins. Check the goblin bodies, if you should find unbroken warrior beads on them, take them to Sheriff Roglio Bruth and should you be lucky enough to find a bizarre grappling device, you are to take it to Marshal Ghobber Truppack immediately! One more thing - should you defeat any orcs in battle, bring me their leather belts and I shall reward you for the great victory. May the power of Underfoot be with you!


elseif( **Faction is** == Indifferent) then



>**Deputy Budo says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Deputy Budo says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




end

## Turn-Ins




local count =  **You turn in:**  { [Deathfist Slashed Belt](/item/13916)}

if(count > 0) then


repeat



>**Deputy Budo says:** Grand work. Deputy Soandso! You will become a full-fledged deputy in no time. You should check in with Marshal Ghobber from time to time to see if you have earned your squad ring. Just go up to him and ask. 'Am I one with the Wall?' He will know. but you must first show your bravery in many battles against the goblins.



* __Faction:__ [Guardians of the Vale](/faction/263) (5)



* __Faction:__ [Mayor Gubbin](/faction/286) (1)



* __Faction:__ [Storm Reapers](/faction/355) (1)



* __Faction:__ [Merchants of Rivervale](/faction/292) (1)



* __Faction:__ [Dreadguard Outer](/faction/334) (-1)



 **You receive:**  [Tagglefoot Tingle Drink](/item/13024) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**


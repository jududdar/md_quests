# Sheriff Roglio
## Dialog

**You say:** `hail`



if **Faction** >= Amiable +100 then



>**Sheriff Roglio says:** Hail, Soandso! Stand tall whenever you are speaking to the Sheriff of Rivervale. I command the warriors of this vale. You must be new to the ranks of the Guardians of the Vale, so be sure to report to your squad at once. We must protect our people. The [danger] has come closer to home. If you are not a deputy, then please leave these halls.


else



>**Sheriff Roglio says:** Please come back when you have proven yourself more and I may have a task for you.



**You say:** `danger`



if **Faction** >= Amiable then



>**Sheriff Roglio says:** What danger?!! You must be new to the community. The goblins of Clan Runnyeye have been scaling our wall somehow. You must join our forces in exterminating every one of those beasts. Your wages are earned with every four bloody goblin warbead necklaces you return to me. Now be off and fight the good fight.


elseif **Faction** >= Indifferent then



>**Sheriff Roglio says:** You are in good standing with the Guardians of the Vale. Continue with your good work and then we may speak.


else



**Sheriff Roglio says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


end

## Turn-Ins




if( **You turn in:** [Recruitment Summons](/item/18733)) then 


>**Sheriff Roglio says:** Welcome to the Guardians of the Vale. I'm Roglio Bruth, and I run this proud little outfit. You seem to be of hearty stock, let's put you to work. Here's your guild tunic - hope it fits. Start your training right away.  Speak with the marshals of this guild.


* __Faction:__ [Guardians of the Vale](/faction/263) (100)


* __Faction:__ [Mayor Gubbin](/faction/286) (15)


* __Faction:__ [Storm Reapers](/faction/355) (10)


* __Faction:__ [Merchants of Rivervale](/faction/292) (15)


* __Faction:__ [Dreadguard Outer](/faction/334) (-15)


 **You receive:**  [Old Tan Tunic*](/item/13540) (+20 exp)

elseif( **You turn in:**  { [RunnyEye Warbeads](/item/13931)}, 4) > 0


>**Sheriff Roglio says:** Good work, Deputy Soandso! We shall soon rid our countryside of the goblin threat. Here are your wages. Eat well tonight!


* __Faction:__ [Guardians of the Vale](/faction/263) (1)


* __Faction:__ [Mayor Gubbin](/faction/286) (1)


* __Faction:__ [Storm Reapers](/faction/355) (1)


* __Faction:__ [Merchants of Rivervale](/faction/292) (1)


* __Faction:__ [Dreadguard Outer](/faction/334) (-1)


 **You receive:**  [Tagglefoot Tingle Drink](/item/13024) (+5000 exp)


 **You receive:**  [Bixie Berry Buns](/item/13023) 

**This NPC *should* return incorrect items given.**



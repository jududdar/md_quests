# Marshal Anrey


## Dialog

**You say:** `hail`



>**Marshal Anrey says:** Stand at attention!! You don't look fit enough to toe-wrestle my grandma!! You cannot be in my squad!! Are you [petitioning] or are you a [visitor]?

**You say:** `visitor`



>**Marshal Anrey says:** Well, why didn't you say so?! Forgive me for hollering. Allow me to introduce myself. I am Marshal Anrey Leadladle, commander of the [Leatherfoot Raiders].

**You say:** `leatherfoot raider`



>**Marshal Anrey says:** You must be a visitor. The Leatherfoot Raiders are the elite force of the Guardians of the Vale. I command them. It is good to meet an outsider.



**You say:** `petitioning`



if **Faction** >= Amiable +100 then 
(200)




>**Marshal Anrey says:** So you want to be a [Leatherfoot Raider]? What kind of joke is this? Look at you! You're a mess! Where are you [from]?


elseif **Faction** >= Indifferent then



>**Marshal Anrey says:** You are in good standing with the Guardians of the Vale. Continue with your good work and then we may speak.


else



**Marshal Anrey says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `from rivervale`




if **Faction** >= Amiable +100 then 
(200)




>**Marshal Anrey says:** So you're from Rivervale?!! You must be some kind of freak. No halfling from Rivervale would look, smell and act anything like you. Well, freak, if you think you're stout enough to be a Leatherfoot Raider, you prove it!! You travel the lands and return to me a polar bear skin, a grizzly bear skin, a shark skin and an alligator skin. Then maybe, just maybe, I will let you wear the cap of a Leatherfoot Raider.




elseif **Faction** >= Indifferent then



>**Marshal Anrey says:** You are in good standing with the Guardians of the Vale. Continue with your good work and then we may speak.


else



**Marshal Anrey says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `from qeynos`




>**Marshal Anrey says:** What!  The only things from there are gnolls and trolls!  Which one are you?!  You kind of look like a troll, but you smell like a gnoll!  Get out of my sight or you will be cleaning the latrine with a toothbrush!
end

## Turn-Ins




if **Faction** >= Amiable +100 and  **You turn in:** [Polar Bear Skin](/item/13761), [Thick Grizzly Bear Skin](/item/13756), [Shark Skin](/item/13075), [Alligator Skin](/item/13749)) then 


>**Marshal Anrey says:** So I see the young troll has become a young warrior.  You have stepped up to the challenge of the Leatherfoot Raiders, you may wear the petitioner's skullcap, but to receive the true cap of the raiders, bring me the dirk of a fallen Neriak dragoon and the cap I have given you.  Only then can I be sure that you can truly be one of the few and bold, the Leatherfoot Raiders.





* __Faction:__ [Guardians of the Vale](/faction/263) (25)


* __Faction:__ [Mayor Gubbin](/faction/286) (3)


* __Faction:__ [Storm Reapers](/faction/355) (2)


* __Faction:__ [Merchants of Rivervale](/faction/292) (2)


* __Faction:__ [Dreadguard Outer](/faction/334) (-3)


 **You receive:**  [Leatherfoot Skullcap](/item/13941) (+1000 exp)

elseif **Faction** >= Amiable +100 and  **You turn in:** [Leatherfoot Skullcap](/item/13941), [Dragoon Dirk](/item/13942)) then 


>**Marshal Anrey says:** Congratulations, my young deputy! Welcome to the brotherhood of the Leatherfoot Raiders. You have earned your skullcap. Wear it with pride. You are now one of the elite. Remember our motto, 'Those who risk, prevail'.





* __Faction:__ [Guardians of the Vale](/faction/263) (50)


* __Faction:__ [Mayor Gubbin](/faction/286) (7)


* __Faction:__ [Storm Reapers](/faction/355) (5)


* __Faction:__ [Merchants of Rivervale](/faction/292) (5)


* __Faction:__ [Dreadguard Outer](/faction/334) (-7)


 **You receive:**  [Leatherfoot Raider Skullcap](/item/12259) (+5000 exp)

**This NPC *should* return incorrect items given.**



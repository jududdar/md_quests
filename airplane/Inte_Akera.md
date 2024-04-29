# Inte Akera


## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds
## Dialog

**You say:** `hail`



>**Inte Akera says:** Greetings, Soandso. I am Inte Akera. I have retired to the Plane of Sky after a long life toiling on Norrath's soil. Have you retreated here as well, or are you merely visiting?

**You say:** `toil`



>**Inte Akera says:** Long ago, before I came to this plane, I fought in the name of Prexus against all the evils that plagued Norrath. In that time, I have done everything one can do. I have fought for the causes of good. I gained the esteem of kings and lords. The sword I hold is but one example of the treasures I have sought and won. I have accomplished all that I can, have all that I desire. My toil is done and now I sit among the clouds in peace, occasionally blessing those who seek it and are found worthy.

**You say:** `blessing`



>**Inte Akera says:** Many come seeking my blessings. No matter how minor the blessing they ask, all must prove that they embody the qualities of a paladin before I bless them.

**You say:** `prove myself`



>**Inte Akera says:** I believe the two most important qualities of a paladin are nobility and sacrifice. Hand me an item of yours that proves you understand what nobility and sacrifice are. Be warned however, if I do not think as you do, I will simply accept the item as a gift, and give you no blessing.

**You say:** `nobility`



>**Inte Akera says:** Ah nobility. A true measure of a paladin. If you are wondering what to bring me, then perhaps you should look within yourself. Look into your soul for a great, burning fire of nobility and you will know.

**You say:** `sacrifice`



>**Inte Akera says:** Sacrifice is a virtue all paladins should strive for. The sacrifice of something dear to you will show your devotion. Perhaps something you use to smite the unholy undead.

**You say:** `accomplish`



>**Inte Akera says:** I accomplished many great deeds; far too many to name. I saved kings and kingdoms; I helped the weak and destitue; I accomplished all I sought to do, save one at which I failed.

**You say:** `failed`



>**Inte Akera says:** No.. I was unable to kill my most hated foe, Miragul. The head of this wretched, foul necromancer is forever out of the reach of justice. It would be worth restoring him to his former state for the chance to take his head as a trophy.

**You say:** `miragul`



>**Inte Akera says:** You think you can succeed where I cannot? Perhaps you can noble one.. Bring me the head of Miragul, his robe and hand me back the two blessings I gave you, and in return I shall bequeath to you this sword I carry. Good luck my friend.
end

## Turn-Ins




if( **Faction is** > Kindly and  **You turn in:** [SoulFire](/item/5504)) then 


>**Inte Akera says:** You have chosen wisely, my friend. Take this note as a token of my blessing upon you.


 **You receive:**  [Intes First Blessing](/item/18033) (+100000 exp)

elseif( **Faction is** > Kindly and  **You turn in:** [Ghoulbane](/item/5403)) then 


>**Inte Akera says:** You have chosen wisely, my friend. Take this note as a token of my blessing upon you.


 **You receive:**  [Intes Second Blessing](/item/18034) (+100000 exp)


elseif( **Faction is** > Kindly and  **You turn in:** [Intes First Blessing](/item/18033), [Intes Second Blessing](/item/18034), [Miragul's Head](/item/19073), [Miragul's Robe](/item/1254)) then 


>**Inte Akera says:** Long have I awaited this moment. You have done what even I thought impossible. Take this sword, the Fiery Avenger. You have earned both it and my deepest respect.


 **You receive:**  [Fiery Avenger](/item/11050) (+1000000 exp)



**Inte Akera despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Inte Akera despawns.**




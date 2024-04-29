# Dill Fireshine


## Dialog

**You say:** `hail`



>**Dill Fireshine says:** Welcome to the treetops and the home of Faydark's Champions. We are the skilled rangers of the Faydarks. You are safe in Kelethin. but watch yourself upon the forest floor. I hear the [blue meanies] have been on the rise.

**You say:** `blue meanies`



>**Dill Fireshine says:** That is a little name I have given the Crushbone orcs. It appears they have increased their numbers. The Emerald Warriors are charged with our defense against them. We rangers are to seek out the [orc saboteurs].

**You say:** `orc saboteurs`



if **Faction** >= Amiable then



>**Dill Fireshine says:** As others move to battle the orc armies. we have word that the orc pawns have been sent into the woods to damage the great trees which support Kelethin. We shall employ the talents of our young rangers to halt their efforts. I currently seek those who will [hunt the orc pawns].


elseif **Faction** >= Indifferent then



>**Dill Fireshine says:** Faydark's Champions cannot call you foe. but you have yet to earn our trust.


else



>**Dill Fireshine says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.


**You say:** `hunt.* orc pawn`



if **Faction** >= Amiable then



>**Dill Fireshine says:** Go to the forest floor and seek out the orc pawns. Within their ranks can sometimes be found orc hatchetmen. They carry orc hatchets which you must return and I shall reward you for every two orc hatchets and perhaps offer you a weapon in return. should we have any to spare at the time.


elseif **Faction** >= Indifferent then



>**Dill Fireshine says:** Faydark's Champions cannot call you foe. but you have yet to earn our trust.


else



>**Dill Fireshine says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.


**You say:** `crushbone allies`



if **Faction** >= Amiable then



>**Dill Fireshine says:** It seems the orcs have allied themselves with the wicked Teir'Dal. We know of this through reports of a Teir'Dal presence within Crushbone. We must [intercept the Crushbone runners] and find a reason for their union.


elseif **Faction** >= Indifferent then



>**Dill Fireshine says:** Faydark's Champions cannot call you foe. but you have yet to earn our trust.


else



>**Dill Fireshine says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.


**You say:** `intercept.* crushbone runner`



if **Faction** >= Amiable then



>**Dill Fireshine says:** Go to the Butcherblocks. You stand a greater chance of finding the runners there. I shall pay a bounty for all returned runner pouches.


elseif **Faction** >= Indifferent then



>**Dill Fireshine says:** Faydark's Champions cannot call you foe. but you have yet to earn our trust.


else



>**Dill Fireshine says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.

end

## Turn-Ins



local text = "I expect to receive TWO orc hatchets.";





if **Faction** >= Amiable and  **You turn in:** [Orc Hatchet](/item/12108), [Orc Hatchet](/item/12108)) then 


>**Dill Fireshine says:** Fantastic work!! Your actions shall earn you the respect of all Fier'Dal!  Take this as a small bounty for your deed.  We have heard of [Crushbone allies] who wish our demise.


* __Faction:__ [Faydarks Champions](/faction/246) (10)


* __Faction:__ [King Tearis Thex](/faction/279) (2)


* __Faction:__ [Clerics of Tunare](/faction/226) (2)


* __Faction:__ [Soldiers of Tunare](/faction/310) (2)


* __Faction:__ [Crushbone Orcs](/faction/234) (-2)


 **You receive:** eq.ChooseRandom( [Tarnished Scimitar](/item/5047), [Tarnished Bastard Sword](/item/5048), [Cast-Iron Rapier](/item/7032), [Tarnished Battle Axe](/item/5046)) (+2500 exp)


 **You receive:** eq.ChooseRandom( [Tarnished Scimitar](/item/5047), [Tarnished Bastard Sword](/item/5048), [Cast-Iron Rapier](/item/7032), [Tarnished Battle Axe](/item/5046)) 


if ( math.random() < 0.5 ) then



 **You receive:** eq.ChooseRandom( [Tarnished Scimitar](/item/5047), [Tarnished Bastard Sword](/item/5048), [Cast-Iron Rapier](/item/7032), [Tarnished Battle Axe](/item/5046)) 


elseif( **You turn in:** [A Sealed Letter](/item/18840)) then 


>**Dill Fireshine says:** Yes. A recent report has proven this to be true. An evil alliance has been made. We shall soon need many more experienced adventurers such as yourself. For now, take this reward and strengthen your skills.


* __Faction:__ [Faydarks Champions](/faction/246) (30)


* __Faction:__ [King Tearis Thex](/faction/279) (7)


* __Faction:__ [Clerics of Tunare](/faction/226) (7)


* __Faction:__ [Soldiers of Tunare](/faction/310) (7)


* __Faction:__ [Crushbone Orcs](/faction/234) (-7)


 **You receive:**  [Longbow](/item/8003) (+23400 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Runner Pouch](/item/13226)) then 


>**Dill Fireshine says:** Good work. We shall cut off correspondence between these two. It is for the best. Remember, if you find any notes to Neriak from the ambassador in Crushbone, give them to me.


* __Faction:__ [Faydarks Champions](/faction/246) (20)


* __Faction:__ [King Tearis Thex](/faction/279) (5)


* __Faction:__ [Clerics of Tunare](/faction/226) (5)


* __Faction:__ [Soldiers of Tunare](/faction/310) (5)


* __Faction:__ [Crushbone Orcs](/faction/234) (-5)


 **You receive:** eq.ChooseRandom( [Leather Skullcap](/item/2001), [Leather Mask](/item/2002), [Leather Sleeves](/item/2008), [Leather Gloves](/item/2010), [Raw-hide Tunic](/item/2140), [Raw-hide Cloak](/item/2142), [Raw-hide Leggings](/item/2147), [Raw-hide Boots](/item/2148)) (+21800 exp)

**This NPC *should* return incorrect items given.**



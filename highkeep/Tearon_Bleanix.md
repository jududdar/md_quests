# Tearon Bleanix
## Dialog

local fac = e.other:GetFaction(e.self);

local expansion_flag = eq.get_current_expansion();

**You say:** `hail`



>**Tearon Bleanix says:** Hello sir. Are you a citizen of Highpass?

**You say:** `I am not a citizen`



>**Tearon Bleanix says:** Nor am I. I find this city's love of greed appalling. Do not you?

**You say:** `appalling`



>**Tearon Bleanix says:** Yes. This city of vices is second only to Neriak. And it is trouble with Neriak that has sent me here, in search of my people's princess.

**You say:** `princess`



>**Tearon Bleanix says:** The Princess Lenya Thex is the daughter of His Royal Majesty, King Tearis Thex of Felwithe. She was on her way to Qeynos when we believe she was kidnapped by Carson McCabe, the governor of this vile city. I await the paladin from Felwithe.

**You say:** `all is not bright above the clouds`



if **Faction** >= Kindly then



>**Tearon Bleanix says:** Taken from this place she has been.  Seek the Highpass hussy.  Ask of her.  Only she knows where.  Find the Princess.  Give her this.  Show your allegiance.  This and her key. Then return the room key to me with the prize from the princess.  Become a hero!!



**You receive:**  [Tearons Bracer](/item/13108)


elseif **Faction** >= Indifferent then



>**Tearon Bleanix says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


else



>**Tearon Bleanix says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!




**You say:** `become a hero`



if(fac < 4) then



>**Tearon Bleanix says:** Well let's get started on making you a hero. You must take the Elite Guard Bracer. Look for Princess Lenya. When you find her give her the bracer to prove you are with the Koada'dal. She should trust you then. Then return to me with Princess Lenya and return my bracer. Be safe my friend.



**You receive:**  [Tearons Bracer](/item/13108)


else



>**Tearon Bleanix says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.

end

## Turn-Ins




if **You turn in:** [Highkeep Royal Suite](/item/12267), [Royal Amulet of Thex](/item/13109)


>**Tearon Bleanix says:** Peace..  I can rest now.  You now hold my Silent Watch Shield.  Protect Felwithe..


* __Faction:__ [Clerics of Tunare](/faction/226) (25)


* __Faction:__ [King Tearis Thex](/faction/279) (25)


* __Faction:__ [Anti-mage](/faction/5002) (18)


 **You receive:**  [Silent Watch Shield](/item/9312) (+0 exp)


**Tearon Bleanix despawns.**


if **You turn in:** [Tearon's Bracer](/item/13112)


>**Tearon Bleanix says:** King Tearis Thex thanks you my friend. Could you please hand the princess this amulet. It is hers. I pryed it from the hands of some beggar.


* __Faction:__ [Clerics of Tunare](/faction/226) (25)


* __Faction:__ [King Tearis Thex](/faction/279) (25)


* __Faction:__ [Anti-mage](/faction/5002) (25)


 **You receive:**  [Royal Amulet of Thex](/item/13109) (+0 exp)


**Spawn NPC:**  [\#Princess Lenya](/npc/6573) at (**y:** 13.0, **x:** 52.0)

**This NPC *should* return incorrect items given.**

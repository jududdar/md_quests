# Master Xydoz
## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Master Xydoz says:** What is it you seek within the tower? Could it be that you are a new apprentice? If so, you are required to don the [apprentice skullcap]


elseif **Faction** >= Indifferent then



>**Master Xydoz says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Master Xydoz says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `apprentice`



>**Master Xydoz says:** All new members of the Brood of Kotiz are required to don the [apprentice skullcap]. To earn one, a new apprentice is required to fetch four brains for further experiments. Not just any four brains, mind you, but the brains of [sarnak] hatchlings.

**You say:** `sarnak`



>**Master Xydoz says:** Sarnak ? Do not speak loudly, that name. If you seek information on the sarnak, read the tome of this tower. The tower librarian should be found within.

**You say:** `second rank skullcap`



>**Master Xydoz says:** Looking for the second rank skullcap ? Look no further, but be prepared to earn it. I seek a [faded tapestry]. Now, too, so do you.

**You say:** `faded tapestry`



>**Master Xydoz says:** I have heard reports of such a thing found upon Sarnak hatchlings. They must have scampered from the safety of their dwelling with their master's property. I would like to see this tapestry, but only when it has been mended. I need find a necromancer who is [adept at tailoring].

**You say:** `kor sha`



>**Master Xydoz says:** Do not become like the herbalist, Jondin.  He has many questions concerning Kor - Sha.  It is recorded in the tower tomes.  It was a laboratory of a once great Iksar.  It turned to rubble long ago.

**You say:** `adept at tailoring`



if **Faction** >= Amiable then



>**Master Xydoz says:** If you are a member of the Brood and wish to assist you may seek out this tapestry. Find the Torn and Ripped pieces and take them both to a sewing kit. Return with the mended tapestry and your first rank skullcap and I shall see that you are rewarded with coin and a second rank skullcap


elseif **Faction** >= Indifferent then



>**Master Xydoz says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Master Xydoz says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!

end



## Turn-Ins



local text1 = "I must have the mended tapestry and your first circle apprentice cap before I reward you."

local text2 = "Do not bother me unless you have all that I asked for, grunt. Two star rubies AND the book! Now get OUT of here!";

local text3 = "I will require four sarnak whelp brains for my experiment. When I have them, then you shall have the skullcap of the apprentice, first circle.";



if **Faction** >= Amiable and  **You turn in:** [Sarnak Hatchling Brain](/item/12408), [Sarnak Hatchling Brain](/item/12408), [Sarnak Hatchling Brain](/item/12408), [Sarnak Hatchling Brain](/item/12408)


>**Master Xydoz says:** Good work, my young apprentice. You will make a fine addition to our ranks. Here is your first apprentice skullcap. Wear it as a sign of our circle. Do not lose it. Someday you shall wear a necromancer skullcap, but next shall come the [second rank skullcap].


* __Faction:__ [Brood of Kotiz](/faction/443) (2)


* __Faction:__ [Legion of Cabilis](/faction/441) (1)


 **You receive:**  [Apprentice Skullcap - 1st Rank](/item/4260) (+100 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Apprentice Skullcap - 1st Rank](/item/4260), [Mended Tapestry](/item/18208)


>**Master Xydoz says:** A job well done, apprentice Soandso. Your fine service shall earn you the second circle apprentice skullcap. I would advise you to forget this tapestry, it is nothing more than an ancient rug of no importance.


* __Faction:__ [Brood of Kotiz](/faction/443) (10)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


 **You receive:**  [Apprentice Skullcap - 2nd Rank](/item/4261) (+120 exp)

elseif **You turn in:** [Illegible Note: Greaves](/item/14793)


>*Master Xydoz snatches the paper from your hand and hisses in anger. Without even looking at the paper he growls*


>**Master Xydoz says:** WHAT?! What is this tra... He stares down at the paper, mouth hanging open wide in disbelief. He finally continues, saying, Very well, then. If you wish to know confidence I have a task for you. Our hated enemies, the sarnak, have a tome we have sought to return to our libraries for centuries. At this point, we believe it to be found in a small fortress they maintain near the Great Lake. One of their scholars will most likely have it on their person. Bring it to me along with two star rubies.

elseif **You turn in:** [Iron Bound Tome](/item/14811), [Star Ruby](/item/10032), [Star Ruby](/item/10032)


>**Master Xydoz says:** Well done


 **You receive:**  [Glosk's Reference: Greaves](/item/14831) (+10000 exp)

**This NPC *should* return incorrect items given.**

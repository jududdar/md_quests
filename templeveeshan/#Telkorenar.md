# Telkorenar


## Dialog

if **Faction** >= Kindly then 


**You say:** `hail`




>**Telkorenar says:** The Strong seek me out, for one reason or another. It seems you have come here in peace. Perhaps you wish to prove yourself a mighty fighter? I respect only might, " .. e.other:Race() .. ".


**You say:** `prove`




>**Telkorenar says:** For the mighty I have four tests. The test of the tooth, the test of the flame, the test of the fire storm, and the test of protection. Which test do you wish to undertake?


**You say:** `tooth`




>**Telkorenar says:** With tooth and nail you must fight, deep into the halls of testing. Recover the white tear of power, the white symbol for purity, the silver symbol to calm ones self, and a glowing orb. If you can return these to me I will know you are a mighty fighter indeed.


**You say:** `flame`




>**Telkorenar says:** Return the black tear, the black symbol, the poison symbol, and the serrated symbol to me and you will have completed the test of flame. Your reward will be quite suitable to one who enters the fray of battle.


**You say:** `fire storm`




>**Telkorenar says:** Become like a fire storm and bring your wrath upon the inhabitants of the halls of testing. Return when you have the tear of poison and the serrated tear along with the a symbol kissed by flames and a ruby symbol.


**You say:** `protection`




>**Telkorenar says:** My fire will protect you if you are strong enough to endure this test. A ruby tear like my flames, an emerald tear like a forest ready to burn, an emerald symbol, and a platinum symbol are what I seek. With these I will forge pauldrons unlike any you have ever seen mortal. Go now and seek out what I desire.

 
elseif **Faction** >= Indifferent then


>**Telkorenar says:** You need to prove your dedication to our cause before I can discuss such matters with you.

else


**Telkorenar says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins





if **Faction** >= Kindly and  **You turn in:** [Emerald Symbol](/item/31257), [Emerald Tear](/item/31268), [Ruby Tear](/item/31270), [Platinum Symbol](/item/31258)


FactionHits(e);


 **You receive:**  [Pauldrons of the Deep Flame](/item/31472) (+20000 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Glowing Drake Orb](/item/31260), [Silver Symbol](/item/31253), [White Tear](/item/31261), [White Symbol](/item/31250)


FactionHits(e);


 **You receive:**  [Serrated Dragon Tooth](/item/31469) (+20000 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Black Tear](/item/31262), [Black Symbol](/item/31251), [Poison Symbol](/item/31255), [Serrated Symbol](/item/31254)


FactionHits(e);


 **You receive:**  [Earring of the Living Flame](/item/31470) (+20000 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Flame Kissed Symbol](/item/31256), [Poison Tear](/item/31266), [Serrated Tear](/item/31265), [Ruby Symbol](/item/31259)


FactionHits(e);


 **You receive:**  [Cloak of the Fire Storm](/item/31471) (+20000 exp)

**This NPC *should* return incorrect items given.**

function FactionHits(e)

>**Telkorenar says:** You have done well, ".. e.other:Race() .. ". You have proven that you are strong, but do you dare enter those halls again?

* __Faction:__ [Claws of Veeshan](/faction/430) (75)

* __Faction:__ [Yelinak](/faction/436) (18)

* __Faction:__ [Kromzek](/faction/448) (-37)
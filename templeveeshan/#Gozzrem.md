# Gozzrem


## Dialog

if **Faction** >= Kindly then 


**You say:** `hail`




>**Gozzrem says:** Greetings, Soandso. If you seek wisdom or the arcane I have tasks in the halls of testing you may complete to gain what you seek.


**You say:** `arcane`




>**Gozzrem says:** To garner a reward fit for one who walks the arcane path return to me the poison tear and the poison symbol. Along with these return the serrated symbol and the runed symbol. If this task is not hard enough for you, I have a second quest for you.


**You say:** `second`




>**Gozzrem says:** Tears may fall to the ground but not the ones you seek now. The black tear and the ruby tear you must seek. For more power I require the ruby symbol and a white symbol to bind the powers together. Upon the return of these four objects you will receive a wondrous reward.


**You say:** `wisdom`




>**Gozzrem says:** Wisdom can be gleaned from battle and that is what I wish you to do. Battle in the halls of testing may give you a different outlook on life. Which do you seek, the short battle or the long battle?


**You say:** `long`




>**Gozzrem says:** You will spend much time in the halls of testing. Seek out a runed tear and a flame kissed tear, bring them back to me with a symbol black as midnight and a glowing orb of the ancient drakes.


**You say:** `short`




>**Gozzrem says:** For the shortest time in the halls, seek out a Platinum tear held by the cursed one, a platinum symbol, a silver symbol and an emerald symbol as green as the forests. If you are able to return these to me I will reward you with a simple idol of the white dragons.

 
elseif **Faction** >= Indifferent then


>**Gozzrem says:** You need to prove your dedication to our cause before I can discuss such matters with you.

else


**Gozzrem says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins





if **Faction** >= Kindly and  **You turn in:** [Poison Tear](/item/31266), [Poison Symbol](/item/31255), [Runed Symbol](/item/31252), [Serrated Symbol](/item/31254)


FactionHits(e);


 **You receive:**  [White Dragon Statue](/item/31466) (+20000 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Black Tear](/item/31262), [Ruby Tear](/item/31270), [Ruby Symbol](/item/31259), [White Symbol](/item/31250)


FactionHits(e);


 **You receive:**  [Boots of Deep Thought](/item/31468) (+20000 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Flame Kissed Tear](/item/31267), [Runed Tear](/item/31263), [Black Symbol](/item/31251), [Glowing Drake Orb](/item/31260)


FactionHits(e);


 **You receive:**  [Boots of Silent Striding](/item/31467) (+20000 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Silver Symbol](/item/31253), [Platinum Symbol](/item/31258), [Emerald Symbol](/item/31257), [Platinum Tear](/item/31269)


FactionHits(e);


 **You receive:**  [White Dragon Idol](/item/31465) (+20000 exp)

**This NPC *should* return incorrect items given.**

function FactionHits(e)

>**Gozzrem says:** You have done well, ".. e.other:Race() .. ". You have proven that you are strong, but do you dare enter those halls again?

* __Faction:__ [Claws of Veeshan](/faction/430) (75)

* __Faction:__ [Yelinak](/faction/436) (18)

* __Faction:__ [Kromzek](/faction/448) (-37)
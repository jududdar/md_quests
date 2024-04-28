# Lendiniara the Keeper
## Dialog

if **Faction** >= Kindly then 


**You say:** `hail`




>**Lendiniara the Keeper says:** Greetings, Soandso. I am the keeper of relics. If you are brave I have tasks to test your might and perhaps rewards.


**You say:** `rewards`




>**Lendiniara the Keeper says:** One should ask of the tasks before worrying about rewards," .. e.other:Race() .. ".


**You say:** `tasks`




>**Lendiniara the Keeper says:** Enter into the halls of testing to complete these tasks. Seek out the ancient ones inside and see if your might is as great as theirs and fear not, those who you slay will be returned to the temple by the gift of Veeshan's great power. I have three tasks, which any may complete, as well as a request of both the arcane and the strong.


**You say:** `arcane`




>**Lendiniara the Keeper says:** Those who seek knowledge, will seek this task out for its reward is great. Three tears and a glowing orb will garner one an ancient mask. The White tear and the black tear for balance the runed tear to hold the balance and a glowing orb to return raw energy to the ancient mask.


**You say:** `strong`




>**Lendiniara the Keeper says:** Those who believe they are strong may be surprised after such a task. Seek out the cursed one and slay him, return to me when you have gathered a silver tear, a poison tear, a flame kissed tear and a serrated tear. End the cursed ones torment for a short time, before the high priest raises him to continue his suffering for eternity.


**You say:** `three`




>**Lendiniara the Keeper says:** Tears from the cursed you much seek for each task. The test of the Ruby Tear, the test of the Platinum Tear and the test of the Emerald Tear await all who wish to partake of them.


**You say:** `ruby tear`




>**Lendiniara the Keeper says:** The test of the ruby tear sounds simple enough, enter the halls of testing, secure a ruby tear, a white symbol, a silver symbol and a ruby symbol. I warn you mortal, those who walk the halls will rend your body and mind if you are not worthy.


**You say:** `platinum tear`




>**Lendiniara the Keeper says:** Seek the platinum tear and three symbols to bind its powers to a bracelet. The black symbol to add raw power, the serrated symbol to enchant its powers and the runed symbol to hold the powers to the bracelet.


**You say:** `emerald tear`




>**Lendiniara the Keeper says:** The emerald tear of Veeshan entrusted to the cursed one. Return this tear to me so I may return the powers of an ancient shield. Three symbols you must also seek. Emerald like the tear, one kissed by the flames of the elder wurms and one made of the ancient wyverns venomous poison.

 
elseif **Faction** >= Indifferent then


>**Lendiniara the Keeper says:** You need to prove your dedication to our cause before I can discuss such matters with you.

else


**Lendiniara the Keeper says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins





if **Faction** >= Kindly and  **You turn in:** [Black Tear](/item/31262), [White Tear](/item/31261), [Runed Tear](/item/31263), [Glowing Drake Orb](/item/31260)


FactionHits(e);


 **You receive:**  [Mask of the Silver Eyes](/item/31463) (+20000 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Flame Kissed Tear](/item/31267), [Poison Tear](/item/31266), [Serrated Tear](/item/31265), [Silver Tear](/item/31264)


FactionHits(e);


 **You receive:**  [Silver Mask of the Slayer](/item/31464) (+20000 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Ruby Symbol](/item/31259), [Ruby Tear](/item/31270), [Silver Symbol](/item/31253), [White Symbol](/item/31250)


FactionHits(e);


 **You receive:**  [Silver Charm of Tranquility](/item/31460) (+20000 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Black Symbol](/item/31251), [Platinum Tear](/item/31269), [Runed Symbol](/item/31252), [Serrated Symbol](/item/31254)


FactionHits(e);


 **You receive:**  [Silver Bracelet of Speed](/item/31461) (+20000 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Emerald Symbol](/item/31257), [Emerald Tear](/item/31268), [Flame Kissed Symbol](/item/31256), [Poison Symbol](/item/31255)


FactionHits(e);


 **You receive:**  [Buckler of Insight](/item/31462) (+20000 exp)

**This NPC *should* return incorrect items given.**

function FactionHits(e)

>**Lendiniara the Keeper says:** You have done well, ".. e.other:Race() .. ". You have proven that you are strong, but do you dare enter those halls again?

* __Faction:__ [Claws of Veeshan](/faction/430) (75)

* __Faction:__ [Yelinak](/faction/436) (18)

* __Faction:__ [Kromzek](/faction/448) (-37)
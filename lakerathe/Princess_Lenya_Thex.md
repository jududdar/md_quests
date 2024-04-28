# Princess Lenya Thex
## On NPC Spawn

**Set a timer** named *yay* for 600 seconds

**Zone Wide Emote:** <span class="text-warning">*a royal fish changes into a beautiful princess!!*</span>

**Princess Lenya Thex shouts:** <span class="text-danger">I am free..</span>

>*Princess Lenya Thex <glug>'  She motions to you to follow her to shore.'*
## Timer(s)

if(e.timer=="yay") then


**Princess Lenya Thex despawns.**
end

## Dialog

**You say:** `hail`



>**Princess Lenya Thex says:** I am rescued from the hands of the Teir'Dal! I am grateful.  Show me your [proof of allegiance] along with a key to remove these [dark shackles] and I shall reward thee.

**You say:** `proof of allegiance`



>**Princess Lenya Thex says:** When I speak of proof of allegiance, I speak of proof you were sent by one of the [Silent Watch].

**You say:** `dark shackles`



>**Princess Lenya Thex says:** My Teir'Dal captors have placed magical shackles upon me.  The shackles prevent me from using my magic to transport myself home nor do they allow me to venture far from Lake Rathetear.  I will require special shackle keys from Highkeep.

**You say:** `silent watch`



>**Princess Lenya Thex says:** The Silent Watch are the Royal Family's guardians. If you run into one, maybe he'll teach you a lesson or two!
end

## Turn-Ins



local text = "I will require both the shackle key for the dark shackles and some proof of allegiance.";



if **You turn in:** [Brass Key](/item/20008), [Tearons Bracer](/item/13108)


>**Princess Lenya Thex says:** You have saved me!!  Soandso, you are my hero!!  Take my amulet and the royal suite key to Tearon in Highkeep.  Help put his soul at ease and he shall reward you.  Now I must go.. I am sorry I cannot transport you as well, but my powers are weak from much swimming.  Farewell, brave soul!


* __Faction:__ [Clerics of Tunare](/faction/226) (75)


* __Faction:__ [King Tearis Thex](/faction/279) (75)


* __Faction:__ [Anti-mage](/faction/5002) (75)


 **You receive:**  [Royal Amulet of Thex](/item/13109) (+500 exp)


**Princess Lenya Thex despawns.**

**This NPC *should* return incorrect items given.**

# Bregun Dorey

## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds
## Timer(s)

if(e.timer == "depop") then


**Bregun Dorey despawns.**
end

## Dialog

**You say:** `hail`



>**Bregun Dorey says:** Trog trog trog trog?

**You say:** `trog`



>**Bregun Dorey says:** Ha! What are you talking about?! Strange thing you are. Wait a minute, come closer. Are you [from Norrath]?

**You say:** `from norrath`



>**Bregun Dorey says:** I thought so, your armor looks to be made from things found not here. Have you heard of [Rivervale]?

**You say:** `bixies around rivervale`



>**Bregun Dorey says:** There are Bixies! THERE ARE BIXIES! This is great. You should hunt some Bixies, and get some Bixie parts. Then you can make me some Bixie Crunchies! Ooooh, Crunchies. I want to try the Crunchies. I think you should bring me four Crunchies!

**You say:** `rivervale`



>**Bregun Dorey says:** [Good].

**You say:** `good`



>**Bregun Dorey says:** Yeah good! Trog trog trog trog! Hahaha! These Troglodytes don't know of Rivervale. They just run around the cave all day doing Troglodyte things. Hahaha! Trog trog trog. So what was I speaking of.. Oh Bixies! So, are there [bixies around Rivervale]?
end

## Turn-Ins





if **You turn in:** [Bixie Crunchies](/item/13464), [Bixie Crunchies](/item/13464), [Bixie Crunchies](/item/13464), [Bixie Crunchies](/item/13464)


>**Bregun Dorey says:** Ah hum!


e.self:RemoveItem(29852);


 **You receive:** None 


>**Bregun Dorey says:** Give this charm to Torsten as a present from his old friend.

elseif **You turn in:** [Sealed Note to Bregun](/item/29853)


>**Bregun Dorey says:** Hahaha! Silly Torsten. Always snooping over my shoulder. Well I have nothing to lose... Take this to him, it's directions on how to find the Journal I kept. I hid it where no one would look! Haha! Trog trog trog!


 **You receive:** None 

**This NPC *should* return incorrect items given.**

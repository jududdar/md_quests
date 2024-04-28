# Umvera Dekash
## Dialog

**You say:** `hail`



>**Umvera Dekash says:** What, Soandso? Do I look like a merchant to you? Just because all these merchants are in my library, it doesn't mean that I am one. If you are [interested] in something other than spell scrolls, then, we can talk.

**You say:** `interested`



>**Umvera Dekash says:** Ah, so you do have half a wit about you! Very well. As you can clearly see, I am the librarian here. I keep track of all of the mystic tomes that enter this divine building. I also take care of all of the purchasing. Have you something to [offer]?

**You say:** `offer`



>**Umvera Dekash says:** Excellent! You have no idea how difficult it is to get good help these days. Do you think you would have the time to gather some [information] for me?

**You say:** `information`



>**Umvera Dekash says:** Even better! Well, it has been some time since the Tesch Val gnolls moved in on the Split Paw. That being said, we still know little to nothing of their origins. If you can bring me back the four scrolls that our diviners speak of, I believe I can reward you well.
end

## Turn-Ins



local text = "Did I not ask for FOUR scrolls? What are you? Some kind of idiot?";



if **You turn in:** [Helle Splitpaw-Haut](/item/18504), [Tanned Split Paw Skin](/item/18505), [Tanned Split Paw Skin](/item/18506), [Tanned Split Paw Skin](/item/18507)





>**Umvera Dekash says:** It's about time. Let's see here. Right.. right.. right. Very good. Right. There you are! I translated the text. Now the scrolls need to be bound. Take these scrolls to Jheron Felkis in Freeport. I believe he is staying in one of the spare rooms in Velith and Bardo's establishment. He will ensure they are bound correctly. Return to me when the binding is complete.


 **You receive:** None 

elseif **You turn in:** [Pawbook](/item/18510)





>**Umvera Dekash says:** You have returned safely. That is wonderful! Where the heck is my book, child? In my hands, I see. Such a bright little twinkle you are! Well, let me scribble something down on this pad here. There you are. Take this note to Durkis Battlemore in the Butcherblock Mountains. He is a remarkable smith, but more importantly, he owes me for his smithing books.


 **You receive:** None 

**This NPC *should* return incorrect items given.**

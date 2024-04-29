# Darfumpel Zirubbel
## Dialog

**You say:** `hail`



>**Darfumpel Zirubbel says:** Hail, Soandso. I am Darfumpel, master jeweler and proprietor of this shop. How might I assist you today? Perhaps you need a stone [cut] or some jewelry [repaired]?

**You say:** `cut`



>**Darfumpel Zirubbel says:** Yes, I use a new gemcutting technique I designed myself. It will bring out the beauty of any gem. However, as arrogant as this may sound, I do not cut just any ordinary stone. They must be rare or of extraordinary quality. Have you an exceptional stone that requires faceting? If so, what type of gem is it?

**You say:** `repaired`



>**Darfumpel Zirubbel says:** Although more mundane a task. I do have a shop to keep up and so I repair jewelry for a nominal fee.

**You say:** `hyacinth`



>**Darfumpel Zirubbel says:** A hyacinth, eh? That is quite a rare stone. Quite fragile and easily shattered, too. With my new technique, I can assure you I will not destroy the gem, however, it will cost you. 1000 platinum coins is my fee. Provide me with the coin and the gem and I will cut it for you.
end

## Turn-Ins



local text = "Do you have the other requirement?";



if( **You turn in:** [Uncut Hyacinth](/item/10191), platinum = 1000) then


>**Darfumpel Zirubbel says:** I have not seen a gem such as this in quite some time! It was not since I dabbled in a bit of necro? Wait? What are you going to use this for? Never mind. I do not wish to know. Here, take your gem and leave!


 **You receive:**  [Faceted Hyacinth](/item/10192) (+1000 exp)

**This NPC *should* return incorrect items given.**






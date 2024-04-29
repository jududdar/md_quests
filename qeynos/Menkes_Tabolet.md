# Menkes Tabolet
## Dialog

**You say:** `hail`



if **Faction** >= Dubious +200 then 



>**Menkes Tabolet says:** Greetings, fine citizen of Qeynos, what can I make for you today?  How about a genuine, handmade [rat fur cap]?  Or maybe a lovely [rat pelt cape]?  Maybe you'd like a necklace?  For a small fee. I can make a nice [snake fang necklace] or a [lucky rat's foot necklace].


else



**Menkes Tabolet says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `rat fur cap`



if **Faction** >= Dubious +200 then



>**Menkes Tabolet says:** Rat fur cap?  You're in luck, that happens to be my specialty, Soandso.  Just bring me 2 pieces of rat fur and 3 gold, and I'll make one up for you while you wait.


else



**Menkes Tabolet says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `rat pelt cape`



if **Faction** >= Dubious +200 then



>**Menkes Tabolet says:** The rat pelt cape..  that happens to be my specialty!  I must say, it would be the perfect choice to go with that outfit you have on.  All I need are 3 rat pelts, those big ol' rats out in the hills work great for these capes, and 4 gold.  I must say, at these prices, everyone in Qeynos will be wearing one in a matter of weeks.


else



**Menkes Tabolet says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `snake fang necklace`



if **Faction** >= Dubious +200 then



>**Menkes Tabolet says:** Hey, great choice..  the snake fang necklace just happens to be my specialty, Soandso!  Just bring me 3 snake fangs, and 2 gold.  With one of these around your neck, you're sure to be the center of attention down at Crow's..  or anywhere else you fill your mug.


else



**Menkes Tabolet says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `lucky rat`



if **Faction** >= Dubious +200 then



>**Menkes Tabolet says:** Now that is exactly what you need my friend, a lucky rat's foot necklace..  and, it just happens to be my specialty!  Just bring me one rat's foot, some rat whiskers, and I won't even charge you any gold. Just buy me a honey mead, and you'll be the luckiest rat dodger this side of Highpass.


else



**Menkes Tabolet says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `kane`



if **Faction** >= Dubious +200 then



>**Menkes Tabolet says:** Commander Kane Bayle is the commander of all the Qeynos Guard.  He is second only to his brother, Antonius Bayle.  His post is in the guard house at the city gates.  Mind you, do not bother him, he has a bit of a temper.


else



**Menkes Tabolet says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `circle.* unseen hand`



if **Faction** >= Dubious +200 then



>**Menkes Tabolet says:** The Circle of the Unseen Hand?  I have heard nothing of them.  Are they some sort of performing magic troupe?


else



**Menkes Tabolet says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Arrive at Waypoint Script

if(e.wp == 6) then


>**Menkes Tabolet says:** Get your rat fur caps here! Get your snakes fang necklaces here! Special discount prices.. this week only.

elseif(e.wp == 9) then


>**Menkes Tabolet says:** Custom made rat pelt capes.. cheap, cheap, cheap!

elseif(e.wp == 12) then


>**Menkes Tabolet says:** Feeling a bit unlucky lately? Gnoll pups always picking on you? Fire beetles attacking you when you aren't looking? what you need is a lucky rat's foot necklace! Satisfaction guaranteed!

elseif(e.wp == 17) then


>**Menkes Tabolet says:** Get your rat fur caps here! Get your snake fang necklaces here! Special discount prices.. This week only.



elseif(e.wp == 23) then


>**Menkes Tabolet says:** Feeling a bit unlucky lately? Gnoll pups always picking on you? Fire beetles attacking you when you aren't looking? what you need is a lucky rat's foot necklace! Satisfaction guaranteed!



elseif(e.wp == 27) then


>**Menkes Tabolet says:** Menkes' discount fashions and jewelry, now open for business.. custom made hats, to fit any size head.


## Turn-Ins



local text1 = "Yea, this is good, but remember, I need 3 gold and 2 pieces of rat fur to make a cap for you.";

local text2 = "That's part of it, now get me the rest and you'll be walking off in a brand new cape, my friend.";

local text3 = "Hey, I'm giving you a great deal here.. Get the rest of items for this already. I'm sure we both have important things to do.";

local text4 = "Oh yea.. this will be the finest snake fang necklace I've ever made.";




if **Faction** >= Dubious and  **You turn in:** [a piece of Rat Fur](/item/13064), [a piece of Rat Fur](/item/13064), gold = 3) then 


>**Menkes Tabolet says:** Hey. look at this. some of my best work, if I do say so myself. Enjoy, and tell your friends


* __Faction:__ [Qeynos Citizens](/faction/121) (2)


 **You receive:**  [Rat Fur Cap](/item/1050) (+200 exp)

elseif **Faction** >= Dubious and  **You turn in:** [Giant Rat Pelt](/item/13054), [Giant Rat Pelt](/item/13054), [Giant Rat Pelt](/item/13054),gold = 4) then


>**Menkes Tabolet says:** This cape turned out great. It'll sure help keep you warm on those cold and stormy nights out in the Karanas.


* __Faction:__ [Qeynos Citizens](/faction/121) (5)


 **You receive:**  [Rat Pelt Cape](/item/1051) (+200 exp)

elseif **Faction** >= Dubious and  **You turn in:** [Snake Fang](/item/13067), [Snake Fang](/item/13067), [Snake Fang](/item/13067),gold = 2) then


>**Menkes Tabolet says:** Hey, hey.. with this little baby, you will be the talk of the town tonight!


* __Faction:__ [Qeynos Citizens](/faction/121) (5)


 **You receive:**  [Snake Fang Necklace](/item/1052) (+200 exp)

elseif **Faction** >= Dubious and  **You turn in:** [Rat Foot](/item/13065), [Rat Whiskers](/item/13071), [Honey Mead](/item/13033)) then


>**Menkes Tabolet says:** Now this here has got to be one of my best works.. I dare you to find someone who can make a higher quality necklace than this one! Enjoy, my good friend!


* __Faction:__ [Qeynos Citizens](/faction/121) (5)


 **You receive:**  [Rats Foot Necklace](/item/1053) (+200 exp)

**This NPC *should* return incorrect items given.**

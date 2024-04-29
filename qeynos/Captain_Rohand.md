# Captain Rohand
## Dialog

**You say:** `hail`



>**Captain Rohand says:** Greetings, friend, and welcome to the Mermaid's Lure. Here, we sell fishing supplies and some imported goods from far-off lands. And, if you've got a few minutes, I could even tell you a [story] or two.

**You say:** `story`



>**Captain Rohand says:** Stories? Stories? I saw more adventure before I was ten years tall than you'll see in your whole miserable existence. I've been everywhere, [Odus], [Faydwer], [Kunark]. . . You name it, and I can tell ya a little something 'bout it. . . If you buy me a sip of brandy, of course!

**You say:** `odus`



if **Faction** >= Indifferent then



>**Captain Rohand says:** You haven't lived until you've seen Odus. Erud was the first human to cross the sea, and he founded the great city of Erudin. The trade routes from here to Odus are busy and prosperous, but can also be very dangerous.


else



**Captain Rohand says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `faydwer`



if **Faction** >= Indifferent then



>**Captain Rohand says:** I call Faydwer the home of the little people. They say the continent was named by the high elves when they landed on its shores long ago. I've even heard tales of an ancient elven vampire who lives there. . . Just another Felwithe legend, I'll bet!


else



**Captain Rohand says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `kunark`



if **Faction** >= Indifferent then



>**Captain Rohand says:** Even I can't tell you much about that continent. Kunark is a tough place, populated by even tougher creatures. I hear the high elves of Faydwer have been trying for years to establish a small port on Kunark's hostile shores.


else



**Captain Rohand says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `antonica`



if **Faction** >= Indifferent then



>**Captain Rohand says:** Antonica?  You're standing on it!  This is the largest continent on all of Norrath, as well as the most populated.  We humans rule over most of Antonica, from this beautiful city to Everfrost, to Highpass and all the way to Freeport.






else



**Captain Rohand says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!





**You say:** `tax`



* __Faction:__ [Merchants of Qeynos](/faction/291) (-1)


>**Captain Rohand says:** Argh! You curvy sea goblin! Taxes, you say?! Peh! I got your taxes right here! I sure don't get the services those taxes are supposed to provide! You can tell them ol' Captain Rohand said so!


**You receive:**  [Rohands Tax Payment](/item/13177)
end

## Turn-Ins

local brandy = 0;





if( **You turn in:** [Brandy](/item/13034), [Brandy](/item/13034), [Brandy](/item/13034), [Brandy](/item/13034)) then


brandy = 4;

elseif( **You turn in:** [Brandy](/item/13034), [Brandy](/item/13034), [Brandy](/item/13034)) then



brandy = 3;

elseif( **You turn in:** [Brandy](/item/13034), [Brandy](/item/13034)) then


brandy = 2;

elseif( **You turn in:** [Brandy](/item/13034)) then


brandy = 1;
 

if(brandy > 0) then


repeat



>**Captain Rohand says:** Yeah, this is just what I've been craving!



* __Faction:__ [Merchants of Qeynos](/faction/291) (25)



* __Faction:__ [Circle of Unseen Hands](/faction/223) (-5)



* __Faction:__ [Antonius Bayle](/faction/219) (3)



* __Faction:__ [Coalition of Tradefolk](/faction/229) (2)



* __Faction:__ [Guards of Qeynos](/faction/262) (5)







 **You receive:** 0 (+10 exp)



brandy = brandy - 1;


until brandy == 0

 

item_lib.return_items(e.self, e.other, e.trade, e.text)
 
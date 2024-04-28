# Captain Ashlan
## Dialog


**You say:** `hail`



if **Faction** >= Dubious +150 then



>**Captain Ashlan says:** Greetings, traveler! I am Captain Ashlan of the Highpass Guards. I keep watch over my men and the [volunteers] here at the East Gate. It's been a busy [job] here lately, with the [orc raids] and all.


else



**Captain Ashlan says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `job`



if **Faction** >= Dubious +150 then



>**Captain Ashlan says:** We're short-handed around here, as usual. Would you like to help us out with the [Volunteer Watch]?


else



**Captain Ashlan says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `volunteer`



if **Faction** >= Dubious +150 then



>**Captain Ashlan says:** The Volunteer Watch guards the entry gates of Highpass. Since the [orc raids] are becoming more and more frequent, it's a busy job. But it can pay well, depending on how many [orcs] you slay.


else



**Captain Ashlan says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `orc`



if **Faction** >= Dubious +150 then



>**Captain Ashlan says:** One of the orc clans of Kithicor Woods has been trying to expand their territory. Small orc raiding parties are frequently rushing the East Gate. Without the [Volunteer Watch] helping us out, Highpass would probably be overrun by those vile beasts.


else



**Captain Ashlan says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `hold`



if **Faction** >= Dubious +150 then



>**Captain Ashlan says:** Highpass Hold is run by [Carson McCabe], who lives in the keep. It's a rough place here, but you can easily make a quick buck.


else



**Captain Ashlan says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `carson`



if **Faction** >= Dubious +150 then



>**Captain Ashlan says:** Carson runs this place. I wouldn't cross him; he seems like a pretty ruthless guy. I hear he's got connections all over Antonica!


else



**Captain Ashlan says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins

local scalp = 0;





if **You turn in:** [Orc Scalp](/item/13791), [Orc Scalp](/item/13791), [Orc Scalp](/item/13791), [Orc Scalp](/item/13791)



scalp = 4;

elseif **You turn in:** [Orc Scalp](/item/13791), [Orc Scalp](/item/13791), [Orc Scalp](/item/13791)



scalp = 3;

elseif **You turn in:** [Orc Scalp](/item/13791), [Orc Scalp](/item/13791)



scalp = 2;

elseif **You turn in:** [Orc Scalp](/item/13791)



scalp = 1;



if(scalp > 0) then


if **Faction** >= Dubious +150 then



repeat




>**Captain Ashlan says:** Great work! Maybe you can help us out again sometime?




* __Faction:__ [Highpass Guards](/faction/332) (1)




* __Faction:__ [Carson McCabe](/faction/329) (1)




* __Faction:__ [Merchants of Highpass](/faction/331) (1)




* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)




* __Faction:__ [The Freeport Militia](/faction/330) (1)




 **You receive:** 0 (+2500 exp)




scalp = scalp - 1;



until scalp == 0


else



>**Captain Ashlan says:** I will not aid beings such as you.



scalp = 0;


**This NPC *should* return incorrect items given.**
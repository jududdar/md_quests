# Captain Orben
## Dialog


**You say:** `hail`



if **Faction** >= Dubious +150 then



>**Captain Orben says:** Greetings, traveler! I am Captain Orben of the Highpass Guards. I keep watch over my men and the [volunteers] here at the West Gate. It's been a busy [job] here lately, with the [gnoll raids] and all.


else



**Captain Orben says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `job`



if **Faction** >= Dubious +150 then



>**Captain Orben says:** We're short-handed around here, as usual. Would you like to help us out with the [Volunteer Watch]?


else



**Captain Orben says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `volunteer`



if **Faction** >= Dubious +150 then



>**Captain Orben says:** The Volunteer Watch guards the entry gates of Highpass. Since the [gnoll raids] are becoming more and more frequent, it's a busy job. But it can pay well, depending on how many [gnolls] you slay.


else



**Captain Orben says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `gnoll`



if **Faction** >= Dubious +150 then



>**Captain Orben says:** The Mucktail Gnolls of the Karanas have been trying to expand their territory. Small gnoll raiding parties are frequently rushing the West Gate. Without the [Volunteer Watch] helping us out, Highpass would probably be overrun by those vile beasts.


else



**Captain Orben says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `hold`



if **Faction** >= Dubious +150 then



>**Captain Orben says:** Highpass Hold is run by [Carson McCabe], who lives in the keep. It's a rough place here, but you can easily make a quick buck.


else



**Captain Orben says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `carson`



if **Faction** >= Dubious +150 then



>**Captain Orben says:** Carson runs this place. I wouldn't cross him; he seems like a pretty ruthless guy. I hear he's got connections all over Antonica!


else



**Captain Orben says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `keep`



if **Faction** >= Dubious +150 then



>**Captain Orben says:** The keep is in the center of Highpass Hold. The keep was made in a natural cave and then expanded over the past few years. I hear they are currently adding some new floors beneath it.


else



**Captain Orben says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins

local scalp = 0;





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13792" data-url="13792" class="tooltip-link link">Gnoll Scalp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13792" data-url="13792" class="tooltip-link link">Gnoll Scalp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13792" data-url="13792" class="tooltip-link link">Gnoll Scalp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13792" data-url="13792" class="tooltip-link link">Gnoll Scalp</a>) then



scalp = 4;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13792" data-url="13792" class="tooltip-link link">Gnoll Scalp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13792" data-url="13792" class="tooltip-link link">Gnoll Scalp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13792" data-url="13792" class="tooltip-link link">Gnoll Scalp</a>) then



scalp = 3;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13792" data-url="13792" class="tooltip-link link">Gnoll Scalp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13792" data-url="13792" class="tooltip-link link">Gnoll Scalp</a>) then



scalp = 2;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13792" data-url="13792" class="tooltip-link link">Gnoll Scalp</a>) then



scalp = 1;



if(scalp > 0) then


if **Faction** >= Dubious +150 then



repeat




>**Captain Orben says:** Great work! Maybe you can help us out again sometime?




Your faction standing with [Highpass Guards](/faction/332) got better (<span class='text-success'>+5</span>)




Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+2</span>)




Your faction standing with [Merchants of Highpass](/faction/331) got better (<span class='text-success'>+2</span>)




Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+2</span>)




Your faction standing with [The Freeport Militia](/faction/330) got better (<span class='text-success'>+2</span>)




 &#127873; **You receive:** 0 (+2500 exp)

**You receive coin:** 0-1 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 




scalp = scalp - 1;



until scalp == 0


else



>**Captain Orben says:** I will not aid beings such as you.



scalp = 0;


**This NPC *should* return incorrect items given.**

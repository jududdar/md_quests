# Lady Shae


## Dialog

**You say:** `hail`



>**Lady Shae says:** Hello. It is always good to meet someone new. I am Lady Shae of the House of Dumas. And what [house] are you from?

**You say:** `no house`



>**Lady Shae says:** Good. I care not to hang around any snobs this evening. Would you be so kind as to buy me some wine?

**You say:** `wine`



>**Lady Shae says:** Why, yes, I would love a drink! Pandos, my bodyguard, keeps telling me to try the white wine.

**You say:** `steel warriors sent me`



>**Lady Shae says:** Thank you for checking into this matter. I told the Militia, but they just ignored me. It appears the dark elves keep coming in leaving mail for [Shintl] Lowbrew. Before I tell you more could you please buy me A white wine please.

**You say:** `shintl`



>**Lady Shae says:** Oh, please!!  Do not mention that horrid little person!  My stay here has turned into a nightmare because of her.  She gets mail delivered to her room every so often by dark elves, of all things.  I cannot stand the Teir'Dal!  I wonder what is in that mail.  If I just had her room key I could walk right up to the innkeeper and say, 'Mail for room two please.' That is all it would take.  But enough about her.  Let's talk about you buying me some drinks.

**You say:** `house of pancakes`



>**Lady Shae says:** I can tell. You look like you ATE a house of pancakes.

**You say:** `house of style`



>**Lady Shae says:** I would of never guessed by the way you look.

**You say:** `house of pain`



>**Lady Shae says:** How droll. I have no interest in warriors or bad jesters.

**You say:** `dyllin`



>**Lady Shae says:** Dyllin was the name of a Qeynos guard who was sent to pick up the list I was holding for dear, sweet Antonius. He left just yesterday. If you wish to meet up with him, I heard him say he was going to stop at Highpass Hold.
end



## Turn-Ins



local text = "Thank you... Oh my! A few more of these and I will be spilling my secrets.";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_788.png" alt="" /> <a
                                href="/item/13031" data-url="13031" class="tooltip-link link">White Wine</a>) then


>**Lady Shae says:** Thank you. Pandos has been telling me to try white wine forever. I mostly only drink red wine. Pardon me for getting off track. Anyway, it is a good thing you showed up. The lady in room 2 has been receiving mail from a Dark Elf. You [need the mail for room two]. The Innkeeper usually holds it for the guests.


Your faction standing with [FelGuard](/faction/156) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:** 0 (+5 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/13030" data-url="13030" class="tooltip-link link">Red Wine</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/13030" data-url="13030" class="tooltip-link link">Red Wine</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/13030" data-url="13030" class="tooltip-link link">Red Wine</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/13030" data-url="13030" class="tooltip-link link">Red Wine</a>) then


>**Lady Shae says:** Oh my.. You are so kind. I can not tell you the last time I had so much fine wine. Well, there was the time Antonius Bayle told me he no longer had the time for a committed relationship. Mister big ruler of the world. Make it to the top and find someone younger. I know his plan. I hate him. I will never trust another human again. After all that, he goes and asks me to hold on to this list for him. Well I am glad it was taken from me by that [Dyllin]. Antonius Bayle has no ties to me any more!! Good riddance! Oooooh! I love him.


Your faction standing with [FelGuard](/faction/156) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:** 0 (+240 exp)

 


**This NPC *should* return incorrect items given.**



## Arrive at Waypoint Script

if(e.wp == 12) then


>**Lady Shae says:** I will be back soon, Pandos. Please keep an eye on my room for me.


**Signaled to:**  [Pandos Flintside](/npc/9057)
end

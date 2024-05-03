# Captain Bosec


## Dialog

**You say:** `hail`



if **Faction** >= Dubious +150 then



>**Captain Bosec says:** I'm Captain Bosec. and I am the officer in charge down here. It's my job to patrol the prison and try to keep any [goblins] from getting into Highpass.


else



**Captain Bosec says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `goblin`



if **Faction** >= Dubious +150 then



>**Captain Bosec says:** Help us exterminate these vile creatures. They call themselves the [Pickclaw] Clan.. I call them annoying. I will gladly pay big money for the left ear of every goblin slain.


else



**Captain Bosec says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `pickclaw`



if **Faction** >= Dubious +150 then



>**Captain Bosec says:** A couple of months ago, Carson decided to add some more floors beneath the keep. During the construction, we came across these tunnels.. and these goblins. Work has been temporarily halted until we can completely clear out this Pickclaw infestation.


else



**Captain Bosec says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `who.* mistress anna`




>**Captain Bosec says:** Mistress!  Aptly named, that one.  You are speaking of the Highpass hussy.  That is what everyone calls her, at least behind her back, that is.  Just as Highpass, she is beautiful and frequently traveled.  I have heard rumors that Carson has been seeing her, but how can that be true?  He has Lady McCabe.  What else does he need?

**You say:** `who.* carson`




>**Captain Bosec says:** Carson McCabe is the ruler of Highpass Hold. It was his father, Sean McCabe, who established this great community.

**You say:** `who.* lady mccabe`




>**Captain Bosec says:** A stunning lady if I ever saw one. There is truly a rose missing from the gardens of Erudin. Just look, but do not touch. She is the spouse of Carson McCabe himself. How even he won the heart of a lady as beautiful as that is an amazement to us all.

**You say:** `karana`




>**Captain Bosec says:** If you are trying to get to Karana, you will need to leave Highpass from the western entrance.

**You say:** `prison`




>**Captain Bosec says:** The dungeon is located on the lower levels of High Keep. Do not venture there. It is off limits to visitors. If you wish to get someone released, you will have to speak with the jail clerk just before you get to the dungeon.

**You say:** `sleep`




>**Captain Bosec says:** If you are looking for a comfortable bed to sleep on, speak to the innkeeper on the first level of the keep. The rooms are expensive, but other than that, your only choice would be to try and find an empty room at the Golden Rooster.

**You say:** `tavern`




>**Captain Bosec says:** There are a few places outside the keep which can supply an endless flow of grog. As for inside the keep, you may be able to buy a drink or two from the kitchen on the second floor.

**You say:** `freeport`




>**Captain Bosec says:** If you plan on going to Freeport you will have to go through the Commonlands first.

**You say:** `bank`




>**Captain Bosec says:** Inside the keep, you can turn items in for safekeeping with the vault clerk who is on the lower level beyond the guestrooms. Do not wander too far down there.The dungeon is also in the same area.

**You say:** `tehafer`




>**Captain Bosec says:** Commander Tehafer is a very noble man. It is rumored that he was once a paladin and has since fallen from grace. He now oversees all Highpass Watch operations. If you wish to speak with him, he can usually be found alongside the guards in High Keep entrance. Imagine that, a commander on watch alongside his men.

**You say:** `common`




>**Captain Bosec says:** Exit Highpass from the eastern entrance. You will run right into the Commonlands. Just be careful in the Commonlands - I hear there has been an increase in orc activity.

**You say:** `guild`




>**Captain Bosec says:** Guilds in Highpass!? I am afraid not. If you wish to join the ranks of the Highpass Watch, speak with one of our officers.

**You say:** `officer`




>**Captain Bosec says:** The officers of the Highpass Watch are Captain Bosec of the High Keep Guard, Captain Ashlan of the East Gate Guard and finally Captain Orben of the West Gate Guard. Above them all is Commander Tehafer.

**You say:** `where.* carson`




>**Captain Bosec says:** Carson McCabe resides in the royal chambers of High Keep. If you wish to meet with him, do so when he is on the lower levels of the keep. He does not like visitors in the upper levels.

**You say:** `where.* lady mccabe`




>**Captain Bosec says:** I would assume that she would be in the royal chambers in the highest levels of High Keep.

**You say:** `where.* mistress anna`




>**Captain Bosec says:** My best guess would be that she's somewhere in the suite of the richest noble passing through Highpass.
end



## Turn-Ins

local ear = 0;





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13790" data-url="13790" class="tooltip-link link">Left Goblin Ear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13790" data-url="13790" class="tooltip-link link">Left Goblin Ear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13790" data-url="13790" class="tooltip-link link">Left Goblin Ear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13790" data-url="13790" class="tooltip-link link">Left Goblin Ear</a>) then



ear = 4;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13790" data-url="13790" class="tooltip-link link">Left Goblin Ear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13790" data-url="13790" class="tooltip-link link">Left Goblin Ear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13790" data-url="13790" class="tooltip-link link">Left Goblin Ear</a>) then



ear = 3;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13790" data-url="13790" class="tooltip-link link">Left Goblin Ear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13790" data-url="13790" class="tooltip-link link">Left Goblin Ear</a>) then



ear = 2;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13790" data-url="13790" class="tooltip-link link">Left Goblin Ear</a>) then



ear = 1;



if(ear > 0) then


if **Faction** >= Dubious +150 then



repeat




>**Captain Bosec says:** Well done! We could really use the extra help around here.




Your faction standing with [Highpass Guards](/faction/332) got better (<span class='text-success'>+2</span>)




Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+1</span>)




Your faction standing with [Merchants of Highpass](/faction/331) got better (<span class='text-success'>+1</span>)




Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)




Your faction standing with [The Freeport Militia](/faction/330) got better (<span class='text-success'>+1</span>)




















 &#127873; **You receive:** 0 (+2500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 















-



ear = ear - 1;



until ear == 0


else



>**Captain Bosec says:** I will not aid beings such as you.


**This NPC *should* return incorrect items given.**

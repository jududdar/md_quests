# Moodoro Finharn


## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then 




>**Moodoro Finharn says:** Greetings, fellow traveler! I gotta tell ya. I love this town. Especially Crow's. Although the crowd seems a bit shadier than other places of the sort.


else



**Moodoro Finharn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




**You say:** `testament of vanear`



>**Moodoro Finharn says:** So you have heard that good old Moodoro has knowledge of the Testament of Vanear. I care little for that book. Of course I have it!! If you want it, I will sell it to you for two gold pieces.

**You say:** `ran`



>**Moodoro Finharn says:** Ran Flamespinner is a librarian in Highpass Hold.

**You say:** `page 34`



>**Moodoro Finharn says:** So, you know I have page 34. Pretty smart of me to tear the most important page out before someone else tried, eh? If you really want it, then sit down and deal in. Ante is 4 gold. I will give you one card. If it is a jester, then I will give you the page. Let's do it.

**You say:** `tonic`



>**Moodoro Finharn says:** I need some of Erud's tonic water. There is a merchant in Erudin who sells it.
end



## Arrive at Waypoint Script

if(e.wp == 6) then


>**Moodoro Finharn says:** <urp>.. I don't feel so well.


**Signaled to:**  [Flynn Merrington](/npc/2091)

elseif(e.wp == 14) then


eq.set_anim(2040,1);


>**Moodoro Finharn says:** Ooooh.. Bllaughhh.. Ooh.. I need some tonic.
end



## Signals


if(e.signal == 1) then


>**Moodoro Finharn says:** HA! HA! HA! Oh...  <burp> HA!  HA!  HA! How pitiful! HA! HA!






## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_856.png" alt="" /> <a
                                href="/item/13118" data-url="13118" class="tooltip-link link">Eruds Tonic</a>) then


>**Moodoro Finharn says:** Oh thank the maker you have returned. Here is a little something in return





Your faction standing with [Crimson Hands](/faction/233) got better (<span class='text-success'>+20</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+2</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [High Guard of Erudin](/faction/267) got better (<span class='text-success'>+2</span>)


e.other:QuestReward(0,0,0,0,0,0);

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_650.png" alt="" /> <a
                                href="/item/13994" data-url="13994" class="tooltip-link link">Jester</a>) then


>**Moodoro Finharn says:** Lucky you. We were hoping to really clean you out. Here you go. Take the page. Even together, the book is nothing more than fiction.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/13836" data-url="13836" class="tooltip-link link">Page 34 of a Book</a> 

 

elseif( **You turn in:** gold = 4) then


>**Moodoro Finharn says:** Well, what do you have?!!


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_650.png" alt="" /> <a
                                href="/item/13994" data-url="13994" class="tooltip-link link">Jester</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_652.png" alt="" /> <a
                                href="/item/13993" data-url="13993" class="tooltip-link link">Queen</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_653.png" alt="" /> <a
                                href="/item/13992" data-url="13992" class="tooltip-link link">King</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_654.png" alt="" /> <a
                                href="/item/13995" data-url="13995" class="tooltip-link link">Knight</a>) 

 

elseif( **You turn in:** gold = 2) then


>**Moodoro Finharn says:** HA!! I hope you enjoy the book. It is missing pages 30 and 34. It is nothing more than garbage without them. A rogue ripped them from their bindings and sold them to [Ran].


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/17918" data-url="17918" class="tooltip-link link">Testament of Vanear</a> 

 

**This NPC *should* return incorrect items given.**



## On NPC Death

e.self:Emote(string.format("'s corpse says 'I'll get you back %s!'",e.other:GetCleanName()));
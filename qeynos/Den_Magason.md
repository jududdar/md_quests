# Den Magason


## Arrive at Waypoint Script

if(e.wp == 16 or e.wp == 43 or e.wp == 70) then


>**Den Magason says:** Psst.. Hey, you there.. Yeah, you.. You need some [blank scroll sheets].. I just got a special shipment of things in.. Come on, it's just what you're looking for.. I know you.
end



## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then




>**Den Magason says:** Oh, hey there.. How ya doing? My name's Den. I work for ol' [Rohand] here, unloading the [shipments] that come in from overseas.


else



>**Den Magason says:** Wha'?  Another talking rat? Your reputation with the merchants in this town has put a price on your head...  begone, before I decide to collect!


**You say:** `rohand`



if **Faction** >= Apprehensive then



>**Den Magason says:** Ol' Captain Rohand is the owner of the Mermaid's Lure. He trades goods with sailors and sea [merchants]. I think that old man was even born at sea.. And he's got more stories than fish have scales.



else



>**Den Magason says:** Wha'?  Another talking rat? Your reputation with the merchants in this town has put a price on your head...  begone, before I decide to collect!


**You say:** `shipments`



if **Faction** >= Apprehensive then



>**Den Magason says:** Yeah.. We get merchants and traders with goods from here to [Odus].



else



>**Den Magason says:** Wha'?  Another talking rat? Your reputation with the merchants in this town has put a price on your head...  begone, before I decide to collect!


**You say:** `blank scroll sheets`



if **Faction** >= Apprehensive then



>**Den Magason says:** Blank scroll sheets, huh? You know, there seems to be a shortage of these around here lately. But, hey friend, ol' Denny-boy here would never steer you wrong. I'll sell you some for 2 gold. I know, I'm too kind.


else



>**Den Magason says:** Wha'?  Another talking rat? Your reputation with the merchants in this town has put a price on your head...  begone, before I decide to collect!


**You say:** `Odus`



if **Faction** >= Apprehensive then



>**Den Magason says:** Odus? I've never been there, but I hear it's a long journey.


else



>**Den Magason says:** Wha'?  Another talking rat? Your reputation with the merchants in this town has put a price on your head...  begone, before I decide to collect!

end



## Turn-Ins



local text = "Ok, good job, but I still need the other ones, too. Get the rest of them, so I can ship them all to Odus.";



if( **You turn in:** gold = 2) then


>**Den Magason says:** Yeah, well, these are pretty hard to come by. In fact, these came all the way from Odus. Enjoy, and tell your buddies.





Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+1</span>)




Your faction standing with [Merchants of Qeynos](/faction/291) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)




Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Kane Bayle](/faction/273) got better (<span class='text-success'>+1</span>)







 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18006" data-url="18006" class="tooltip-link link">Blank Scroll Sheets</a> (+100 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/13784" data-url="13784" class="tooltip-link link">Package for Den</a>) then


>**Den Magason says:** All right, I'll make sure this gets put on the next boat to Erudin. But now, I need a favor of you. Since I'm stuck here working the docks all day, I need someone to run out to Qeynos Hills and bring me back various pelts and skins. I got a customer in Odus who is trying to get a new shop started, and he needs some samples. Bring me back some snake scales, a high quality bear skin, a high quality wolf skin, and some bat fur. Make sure the quality is good, I can't send him rags.





Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+10</span>)




Your faction standing with [Merchants of Qeynos](/faction/291) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)




Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Kane Bayle](/faction/273) got better (<span class='text-success'>+1</span>)




 &#127873; **You receive:** 0 (+1000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_813.png" alt="" /> <a
                                href="/item/13070" data-url="13070" class="tooltip-link link">Snake Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13752" data-url="13752" class="tooltip-link link">High Quality Bear Skin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_553.png" alt="" /> <a
                                href="/item/13755" data-url="13755" class="tooltip-link link">High Quality Wolf Skin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_792.png" alt="" /> <a
                                href="/item/13069" data-url="13069" class="tooltip-link link">Bat Fur</a>) then 


>**Den Magason says:** Great... Hopefully he will like these samples, and order a lot more from me. Here's some gold for your efforts. Also, could you pass this note on to Ghil next time you talk to him? Thanks again.





Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+20</span>)




Your faction standing with [Merchants of Qeynos](/faction/291) got worse (<span class='text-danger'>-3</span>)



Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+3</span>)




Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-3</span>)



Your faction standing with [Kane Bayle](/faction/273) got better (<span class='text-success'>+3</span>)




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18796" data-url="18796" class="tooltip-link link">Note for Ghil</a> (+50000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 


**This NPC *should* return incorrect items given.**

# Ged Twigborn



[Ged Twigborn](/npc/20081) is a level 25 Human Warrior that spawns in [Kithicor Forest](/zone/20).



## Dialog

**You say:** `hail`



if **Faction** >= Dubious then



>**Ged Twigborn says:** Hello, Soandso. What brings you to this neck of the woods? You must have heard of my expert tanning skills. I craft some of the finest skin garments this side of Highpass Hold.


else



>**Ged Twigborn says:** I am sorry but I just would not feel comfortable helping you with that right now.  Maybe if you did more good deeds for the people of Kithicor Woods, I might reconsider.


**You say:** `garment`



if **Faction** >= Dubious then



>**Ged Twigborn says:** Gloves are my specialty. I make four varieties; ratskin, wolfskin, bearskin, and my most sought after type, lionskin.


else



>**Ged Twigborn says:** I am sorry but I just would not feel comfortable helping you with that right now.  Maybe if you did more good deeds for the people of Kithicor Woods, I might reconsider.


**You say:** `wolfskin glove`



if **Faction** >= Apprehensive then



>**Ged Twigborn says:** Wolfskin gloves?  Those will cost you 13 gold pieces and you need to bring me a high quality wolf skin as well.


else



>**Ged Twigborn says:** I am sorry but I just would not feel comfortable helping you with that right now.  Maybe if you did more good deeds for the people of Kithicor Woods, I might reconsider.


**You say:** `bearskin glove`



if **Faction** >= Indifferent then



>**Ged Twigborn says:** Ah...  My bearskin gloves are the finest you will find anywhere.  They will cost you 25 gold pieces and you also need to give me a high quality bear skin before I can get to work.


else



>**Ged Twigborn says:** I am sorry but I just would not feel comfortable helping you with that right now.  Maybe if you did more good deeds for the people of Kithicor Woods, I might reconsider.


**You say:** `lionskin glove`



if **Faction** >= Amiable then



>**Ged Twigborn says:** Interested in the best, are you?  Well, it will cost you.  In addition to a high quality lionskin, I require payment of 96 gold pieces for me to craft you my exquisite lionskin gloves.  Search the northern plains of Karana for highland lions as their skins are the most supple.


elseif **Faction** >= Indifferent then



>**Ged Twigborn says:** I know you are doing good for us here in Kithicor but I can only provide that kind of aid to heroes.  Keep up the good work and I may help you in the future.


else



>**Ged Twigborn says:** I am sorry but I just would not feel comfortable helping you with that right now.  Maybe if you did more good deeds for the people of Kithicor Woods, I might reconsider.


**You say:** `ratskin glove`



if **Faction** >= Dubious then



>**Ged Twigborn says:** Interested in some ratskin gloves, are you?  Well, before I can start, I need you to provide me a giant rat pelt and 6 gold pieces.  I need to make a living at this, after all...


else



>**Ged Twigborn says:** I am sorry but I just would not feel comfortable helping you with that right now.  Maybe if you did more good deeds for the people of Kithicor Woods, I might reconsider.

end



## Turn-Ins



local text1 = "Wolfskin gloves, huh?  Very well, but I am still missing one of the things I require to make them.";

local text2 = "Oh, I love working with fine bearskin!  But, if you want your gloves, you must give me the rest of the items I require.";

local text3 = "Excellent choice!  My lionskin gloves are known throughout Norrath.  But before I can make them, I need both a high quality lion skin AND ninety-six gold pieces.";



if **Faction** >= Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13054" data-url="13054" class="tooltip-link link">Giant Rat Pelt</a>) then 


>**Ged Twigborn says:** Ok! Let me see here.. Hmmm.. Oh, excellent.. Here you go. Some of my finest work, if I must say so myself.


Your faction standing with [Kithicor Residents](/faction/269) got better (<span class='text-success'>+2</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+1</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2312" data-url="2312" class="tooltip-link link">Ratskin Gloves</a> (+500 exp)

 

elseif **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_553.png" alt="" /> <a
                                href="/item/13755" data-url="13755" class="tooltip-link link">High Quality Wolf Skin</a>,gold = 13) then


>**Ged Twigborn says:** Ok! Let me see here.. Hmmm.. Oh, excellent.. Here you go. Some of my finest work, if I must say so myself.


Your faction standing with [Kithicor Residents](/faction/269) got better (<span class='text-success'>+2</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+1</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2313" data-url="2313" class="tooltip-link link">Wolfskin Gloves</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13752" data-url="13752" class="tooltip-link link">High Quality Bear Skin</a>,gold = 25) then


>**Ged Twigborn says:** Ok! Let me see here.. Hmmm.. Oh, excellent.. Here you go. Some of my finest work, if I must say so myself.


Your faction standing with [Kithicor Residents](/faction/269) got better (<span class='text-success'>+2</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+1</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2314" data-url="2314" class="tooltip-link link">Bearskin Gloves</a> (+1500 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_834.png" alt="" /> <a
                                href="/item/13766" data-url="13766" class="tooltip-link link">High Quality Lion Skin</a>,gold = 96) then


>**Ged Twigborn says:** Ok! Let me see here.. Hmmm.. Oh, excellent.. Here you go. Some of my finest work, if I must say so myself.


Your faction standing with [Kithicor Residents](/faction/269) got better (<span class='text-success'>+5</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+1</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2315" data-url="2315" class="tooltip-link link">Lionskin Gloves</a> (+2000 exp)

 

**This NPC *should* return incorrect items given.**

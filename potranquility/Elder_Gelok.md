# Elder Gelok


local RanGem;

function DoRandomGem(e)

RanGem = 0;



if (math.random(100) <= 15) then


RanGem = eq.ChooseRandom(10028, 10037, 22503, 15981); 
end



## Dialog

**You say:** `hail`



>**Elder Gelok says:** Hello there! Welcome in. . . Welcome in. . . Just watch yourself when making your way past my most trusted assistant, Drogguk. While he may have superior strength, his coordination is most inferior. He's dropped many a gear on my toes, but I know he means well. In fact, I was intending to send him on a [serious mission], though I would rather he not go.

**You say:** `serious mission`



>**Elder Gelok says:** You see, this windmill is more than it seems. It's quite a splendid device! It produces energy by converting the wind that rotates the blades into a power that supercharges the windmill's transcentrifugal axles. In simple terms, what it does is creates a portal into the [Plane of Innovation]. What a wonderful place that is! A virtual dream-land for any gnome!

**You say:** `plane of innovation`



>**Elder Gelok says:** Oh, it is such an amazing place! I ultimately desire to travel there to learn of advanced mechanics. Alas, this windmill requires constant upkeep due the constant surge of power that it propels. The gears are constantly getting sandy and the axles lose their grease almost daily. I'm often in need of [new parts] and that's where Drogguk's assistance would currently be handy, but I simply cannot sacrifice his current duties at this time. Pity, pity.

**You say:** `new parts`



>**Elder Gelok says:** Well, Drogguk used to travel through the portal to acquire items for me from the salvage yard. The last time he went through in search of parts he came back [badly wounded] and that's saying quite a lot! I was quite alarmed, but the elders nursed him to health with amazing haste. I simply cannot imagine placing him in such jeopardy again. He was lucky to return at all by the look of him then!

**You say:** `badly wounded`



>**Elder Gelok says:** Aye, you can still see some of the scars about his body. He stumbled out of the portal that day, bloody and spouting on about shiny men trying to tear him apart. He said they were speaking of research the whole time. Frightful stuff, really. Well, you look adventurous enough. Why don't you go collect some supplies for me? I fear that Drogguk would not be able to manage another trip to collect the [supplies] I require to maintain this place.

**You say:** `supplies`



>**Elder Gelok says:** Size 12 sprockets are always greatly needed. Any Silicorrosive Grease you find would be a huge help as well. You can never have too much Silicorrosive grease laying around. Also, tri-platinum foil and mini-gyro shields would be good for something or another. Micro-ceramic sleeves are a nice find as well. Got all that? Now, reach around up there in the area of the transcentrifugal axle that isn't working. You'll either be badly wounded or transported to the Plane of Innovation. Take care!
end
  


## Turn-Ins





local firstitem =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1026.png" alt="" /> <a
                                href="/item/28164" data-url="28164" class="tooltip-link link">Mini-gyro Shields</a>}

local seconditem =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/28165" data-url="28165" class="tooltip-link link">Silicorrosive Grease</a>}

local thirditem =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_731.png" alt="" /> <a
                                href="/item/28162" data-url="28162" class="tooltip-link link">Size 12 Sprockets</a>}

local forthitem =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/28163" data-url="28163" class="tooltip-link link">Tri-platinum Foil</a>}



if(firstitem > 0) then


repeat



>*Elder Gelok tosses the shields into a bag that was hidden deep within his robe, 'A few more of these and I'll be able to start working on something new.'*



DoRandomGem(e);



 &#127873; **You receive:** None 

 



firstitem = firstitem -1;


until firstitem == 0;



if(seconditem > 0) then


repeat



>*Elder Gelok inhales deeply and says, 'Aaaah! I love the smell of fresh Silicorrosive grease. It keeps teh sand from bogging down parts and attracts teh ladies all at the same time.'*



DoRandomGem(e);



 &#127873; **You receive:** None 

 



seconditem = seconditem -1;


until seconditem == 0;



if(thirditem > 0) then


repeat



>*Elder Gelok examines the object for a moment and then says, 'This is great! The windmill should function for weeks to come due to your hard work. Feel free to bring me any others that you find. A stockpile of parts never hurt anyone!'*



DoRandomGem(e);



 &#127873; **You receive:** None 

 



thirditem = thirditem -1;


until thirditem == 0;



if(forthitem > 0) then


repeat



>*Elder Gelok wipes the dust from the surface of the foil before placing it on a crate. 'Excellent find! This will be a great help!' The gnome reaches out and shakes your hand in gratitude.*



DoRandomGem(e);



 &#127873; **You receive:** None 

 



forthitem = forthitem -1;


until forthitem == 0;

**This NPC *should* return incorrect items given.**

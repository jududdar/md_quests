# Hansl Bigroon


## Dialog

**You say:** `hail`



>**Hansl Bigroon says:** Greetings, Soandso! Are you a [citizen of Qeynos] or are you a [traveler of sorts]?

**You say:** `traveler of sorts`



>**Hansl Bigroon says:** Ah, yes! Traveling can be truly dangerous. Have you ever [been to Erudin] or do you [not care for that place]?

**You say:** `not care for that place`



>**Hansl Bigroon says:** Then you would not care to hear about my grand plan.

**You say:** `erudin`



>**Hansl Bigroon says:** The trip to Erudin takes far too long. I have been designing a [titanic bridge] which will shorten the trip. Well, I cannot take full credit, most of the plans are being designed by [three great engineers].



**You say:** `three great engineers`




>**Hansl Bigroon says:** They are some of the finest engineers in all of Norrath. Young, they may be, but as smart as the wisest architects I have ever met. That reminds me.. I must have a [list of the engineers] somewhere.. where is it?

**You say:** `list of the engineers`




>**Hansl Bigroon says:** Do not concern yourself with the list. It is of no concern to you. I do not even have it. It is tucked away safely at home.

**You say:** `citizen of qeynos`



>**Hansl Bigroon says:** Then you are aware of how few ships come and go to the continent of Erudin. The port authority is even planning to tax all passage aboard the ships. You will be happy to know that a few other engineers and I are designing a [titanic bridge].

**You say:** `titanic bridge`



>**Hansl Bigroon says:** My grand plan has always been to erect a bridge which would span the distance between Qeynos and Odus. It would bypass the city of Erudin. Antonius Bayle would take full control of the bridge and its adjacent territories. This has had some opposition in Erudin, but for the most part, they just believe it is impossible to build such a bridge.

**You say:** `donation.* temple.* thunder`





>**Hansl Bigroon says:** I would be pleased to help out such a noble organization. Here you are, my good friend. See you at weekly services!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/13290" data-url="13290" class="tooltip-link link">A Donation</a>
end



## Depart from Waypoint Script

local xloc = e.self:GetX();

local yloc = e.self:GetY();

if(e.wp == 0) then


>*Hansl Bigroon drops something as he walks away. He doesn't seems to notice.*


eq.set_proximity(xloc - 10,xloc + 10,yloc - 10,yloc +10);

elseif(e.wp == 13) then


eq.clear_proximity();


**Stop timer** named *repeat*

elseif(e.wp == 36) then


>*Hansl Bigroon picks up a discarded item from the ground and says 'Don't people have enough respect for our grand city to not throw things onto the streets?!'*


**Set a timer** named *repeat* for 320 seconds
end

function event_enter(e)

**Message:** <span class="text-warning">*A note on the ground catches your eye.*</span>

 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18835" data-url="18835" class="tooltip-link link">A Sealed List</a>

eq.clear_proximity();


## Timer(s)

>*Hansl Bigroon picks up a discarded item from the ground and says 'Don't people have enough respect for our grand city to not throw things onto the streets?!'*
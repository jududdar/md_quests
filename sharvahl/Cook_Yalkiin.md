# Cook Yalkiin







## Dialog

**You say:** `Hail`



>**Cook Yalkiin says:** Welcome to our kitchen! As you can tell we stay pretty busy in here.  There are a lot of people to feed and a vast number of delicious meals to feed them.  I'm in charge of preparing [stews], [broth], and [vegetables].  If you ever have any questions about those areas. please let me know.

**You say:** `vegetables`



>**Cook Yalkiin says:** I could go on forever about vegetables. There is such a huge variety to choose from and so much that you can do with... well... come back a bit later and we can talk about them in greater detail.

**You say:** `stews`



>**Cook Yalkiin says:** Stews are a staple in this kitchen. When a cook can't think of a real meal or needs to feed a large number of people in a hurry, they can always whip up a stew. You have to be able to adapt and provide, friend. That's our role here. We're here to make sure people eat. When food is abundant, we can be as lavish as we please. When I'm in a hurry or out of supplies, I like to throw some [beetle claws] in some boiling broth and... bam! It's soup!

**You say:** `beetle claws`



>**Cook Yalkiin says:** Beetle claw stew is quick, easy, and fills stomachs. The main ingredient comes from the Rhino Beetles that can be found in abundance around the city. We use the claws in a variety of dishes, so we can always use a few more. Here, I can give you a bag if you want to go gather some for me. Just fill it up and come back.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/17074" data-url="17074" class="tooltip-link link">Stained Mesh Bag</a>

**You say:** `broth`



>**Cook Yalkiin says:** I can make broth from just about anything. Meat, water, and spices can be turned into a base broth for just about and stew or sauce. The current favorite around here comes from the meat of the large worms that come up from the earth around the base of our city. I know that they look horrid, but they really do taste great! If you want to help, I will pay for every four servings that you bring me.
end



## Turn-Ins



local chanceitem = 0;



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/10390" data-url="10390" class="tooltip-link link">Worm Meat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/10390" data-url="10390" class="tooltip-link link">Worm Meat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/10390" data-url="10390" class="tooltip-link link">Worm Meat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/10390" data-url="10390" class="tooltip-link link">Worm Meat</a>) then


>*Cook Yalkiin looks at each piece of meat before wrapping them in a spiced cloth. 'These look like good cuts of meat. I hope that this will suffice as payment,' he says as he stacks the wrapped meat on the counter.*


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/30580" data-url="30580" class="tooltip-link link">Wooden Practice Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/30577" data-url="30577" class="tooltip-link link">Wooden Practice Two Handed Hammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/30579" data-url="30579" class="tooltip-link link">Wooden Practice Flail</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/30572" data-url="30572" class="tooltip-link link">Wooden Practice Short Sword</a>) (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 4 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/10391" data-url="10391" class="tooltip-link link">Full Mesh Bag</a>) then


>*Cook Yalkiin tosses the bag in a pile with several others and hands you your payment. 'Thank you very much,' he says. 'The more of these that I can gather, the better. I always seem to be low.'*


if(math.random(100) < 35) then



chanceitem = eq.ChooseRandom(30581,30578,2752,2754,2758);



 &#127873; **You receive:** None 

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 6 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_867.png" alt="" /> <a
                                href="/item/5559" data-url="5559" class="tooltip-link link">Meal Voucher</a>) then


>**Cook Yalkiin says:** I'd love to fill this order, but we're out of the meat that he likes. We've been very busy today, so I doubt that any of us will be able to get out to gather more of it. If you could go out and grab us a few slabs, we could not only fill the order, I could put some away for anyone else that may come through today. This sounds like a perfect task for a young Taruun recruit. Fill this bag with the fatty meat from a young Owlbear and bring it back to me right away. I'll get Joharr's sandwiches as soon as you return with the meat.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_691.png" alt="" /> <a
                                href="/item/17608" data-url="17608" class="tooltip-link link">Bloody Cloth Sack</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/5562" data-url="5562" class="tooltip-link link">Sack of Owlbear Meat</a>) then


>*Cook Yalkiin opens the bag and immediately begins to slice the meat into thin sheets. He throws the meat on a few slices of bread and wraps the whole thing up with a hand full of vegetables. 'Here you go, friend!' He says as he hands you what appears to be a lunch bag. 'Joharr should love these sandwiches! The meat that you brought us was great. If you ever need a job as a butcher, just let us know. Take care and tell Joharr I said hello.'*


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1145.png" alt="" /> <a
                                href="/item/5563" data-url="5563" class="tooltip-link link">Bag of Food</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**

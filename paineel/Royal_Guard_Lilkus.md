# Royal Guard Lilkus
## Dialog

**You say:** `hail`



>**Royal Guard Lilkus says:** You tread upon sacred ground, " .. e.other:Race() .. ". None may go further unless they [have business with the Overlord], or, if you're looking to gain favor with the heretics and need a little coin, I have a [job] for you.

**You say:** `business`



>**Royal Guard Lilkus says:** The Overlord only sees those he calls forward. If you have a summons from him, I will escort you and announce your arrival. If not, then forget whatever business you may have had here. If you wish an audience, then go speak to Sheltian below. He may be able to help you.....if you help him.

**You say:** `job`



>**Royal Guard Lilkus says:** There are many campaigns we administer from within our city, Paineel. Some of these campaigns are threatened or hindered by annoyances. One of these annoyances are the kobolds that live in the filth of a cave not far from here. Find that lair and kill as many of these beasts as you can. For every kobold molar you return, you shall be rewarded.
end

## Turn-Ins



local randrew = 0;



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_802.png" alt="" /> <a
                                href="/item/1761" data-url="1761" class="tooltip-link link">Kobold Molar</a>) then


>**Royal Guard Lilkus says:** Not bad, Soandso. Here is your reward. If you slay enough of these dogs, Sheltuin may have a more important task for you to perform.


local random_result = math.random(10);


if(random_result == 1) then



randrew = eq.ChooseRandom(3120,3123,3115,3117,3122,3113,3116,3118,3121,3124,3119,3108,3107,3111,3103,3105,3110,3101,3104,3106,3109,3112,3132,3135,3127,3129,3134,3125,3128,3130,3133,3136,3131); 



Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+7</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-7</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-7</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-7</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-7</span>)


 &#127873; **You receive:** None 

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 6 <img src='/static/icons/item_645.png' width='14' height='14'/> 5 <img src='/static/icons/item_646.png' width='14' height='14'/> 6 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

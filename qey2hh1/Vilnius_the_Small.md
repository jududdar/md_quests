# Vilnius the Small



[Vilnius the Small](/npc/12019) is a level 46 Barbarian Rogue that spawns in [Western Plains of Karana](/zone/12).





## Dialog

**You say:** `hail`



>**Vilnius the Small says:** Soandso, just because I am short don't mean I can't bounce your " .. e.other:Race() .. " rump all over these hills. Now, do you have something for me, or are you just in search of a rump bouncing?

**You say:** `rump`



>**Vilnius the Small says:** My pleasure to oblige you then. Shall I start on the left side or the right side?


**Vilnius the Small attacks you.**

**You say:** `stanos`



>**Vilnius the Small says:** If you need to ask that question, you do not need to know the answer. At least not from me.

**You say:** `who.* you`



>**Vilnius the Small says:** Vilnius, as I have told you. And yes, I am not as large as most of my kin. But that is a blessing, because my brain is bigger than that of an $race. <grin> I am a Facilitator. I.. facilitate.. jobs. You want something somebody else has, I can arrange for you to have it.. even if that something is their life. That is why I am here now, waiting on something to turn up in my hands before I pass it on to my client. Though I am a bit tired of waiting. My hired help seem to be delayed.

**You say:** `malka`



>**Vilnius the Small says:** Malka Rale works for me from time to time. One of the best thieves I have ever met, and damn handy with a blade. She is long overdue to meet me here. I'm afraid she may have run into trouble in Qeynos.

**You say:** `delayed`



>**Vilnius the Small says:** Yes, delayed. She has always been prompt in the past, but she is several days overdue, and I know for a fact she completed the job. I am beginning to wonder if something happened to her. I would go check, but I run the risk of missing her if she shows up here.

**You say:** `job`



>**Vilnius the Small says:** I need a few more items for a collector. They are rare and valuable, but I will pay you well for your trouble. I need the sword owned by the king of the Frogloks, the sword my distant cousin Karg is so proud of, and the matched set of Painbringer and Fleshripper, held by the kobolds. Return those to me quickly, and we will take it from there, eh?

**You say:** `help`



>**Vilnius the Small says:** Oh, really?  So you are willing to wade into Qeynos to track Malka down, or to find out what happened to her?  Willing to take up the job if she failed?  Willing to risk the wrath of the entire Circle of Unseen Hands?  Wonderful, I do so appreciate enthusiasm!  Send Malka back to me, or deliver the pouch she was hired to steal, either one.  If that works out, maybe we can do more business, I am always looking for new people to help me... Facilitate.
end



## Turn-Ins



local text = "looks at you impatiently, expecting more.";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_722.png" alt="" /> <a
                                href="/item/28014" data-url="28014" class="tooltip-link link">Stanos' Pouch</a>) then 


>**Vilnius the Small says:** Ah, very nice. Very nice indeed. Good work, and I hope Malka is able to make it out, good help is hard to find. But in the meantime, I am without an acquisition expert. Do you want the job?


 &#127873; **You receive:** 0 (+1500 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/5411" data-url="5411" class="tooltip-link link">Fleshripper</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1165.png" alt="" /> <a
                                href="/item/5410" data-url="5410" class="tooltip-link link">Painbringer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5401" data-url="5401" class="tooltip-link link">A Mithril Two-Handed Sword</a> (+3000 exp)

 

**This NPC *should* return incorrect items given.**


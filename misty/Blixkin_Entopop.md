# Blixkin Entopop



[Blixkin Entopop](/npc/33066) is a level 27 Halfling Rogue that spawns in [Misty Thicket](/zone/33).











## Arrive at Waypoint Script

if((e.wp == 2) or (e.wp == 9) or (e.wp == 14) or (e.wp == 21) or (e.wp == 24)) then


>**Blixkin Entopop says:** Ember?!  Ember?!  Where are you, girl?!


**Signaled to:**  [Ember](/npc/33065)
end



## Signals

>**Blixkin Entopop says:** There you are!  Stay close to me, girl.


## Combat

>**Blixkin Entopop says:** What do you think you are doing?!?


## Dialog

**You say:** `hail`



>**Blixkin Entopop says:** Hail, Soandso! My name is Blixkin Entopop. Have you seen the wonderful assortment of [spiders] and [beetles] that inhabit the thicket? I have quite an extensive [bug collection]. Be careful, though. I have seen many brave halflings fall beneath a [swarm] of clicking and hissing bugs.

**You say:** `spiders`



>**Blixkin Entopop says:** There are many species of bugs out here. The most common are the fire beetles. If you are hunting them, make sure their queen is not around or you will be in deep trouble. Their eyes are a popular item for adventurers because they give off light as if they were on fire. I even had one warrior try to kill [Ember] for her eyes!!

**You say:** `ember`



>**Blixkin Entopop says:** I raised Ember from an egg. She is my faithful pet and quite smart for a beetle. There are plenty of other bugs to squish, out in the thicket, so you had best leave her alone or I will have to SQUISH you!

**You say:** `swarms`



>**Blixkin Entopop says:** Bugs tend to swarm and defend others of their species when they are attacked. So keep your eyes peeled if you intend to squish any of them.. And you'd better not even THINK of squishing [Ember] or you will be sorry!

**You say:** `beetles`



>**Blixkin Entopop says:** There are many species of bugs out here. The most common are the fire beetles. If you are hunting them, make sure their queen is not around or you will be in deep trouble. Their eyes are a popular item for adventurers because they give off light as if they were on fire. I even had one warrior try to kill [Ember] for her eyes!!

**You say:** `collection`



if **Faction** >= Apprehensive then



>**Blixkin Entopop says:** Here you go. Just follow the instructions on the [list] so you know what to collect and how to prepare the collection for me.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_609.png" alt="" /> <a
                                href="/item/17922" data-url="17922" class="tooltip-link link">Bug Collection Box</a>


else



**Blixkin Entopop says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `list`



if **Faction** >= Apprehensive then



>**Blixkin Entopop says:** What did you do, lose the list? Here is another one. Hold onto it because I will want it back when you are done.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18011" data-url="18011" class="tooltip-link link">Want List</a>


else



**Blixkin Entopop says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins



local text = "Oh you have a complete collection for me?! Good! Good! Well done. But remember that I need the complete bug collection and you must return my want list before I can pay you.";



if **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_609.png" alt="" /> <a
                                href="/item/13268" data-url="13268" class="tooltip-link link">Complete Bug Collection</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18011" data-url="18011" class="tooltip-link link">Want List</a>) then


>**Blixkin Entopop says:** Excellent! Good work! I knew you were the one for this job! Thank you so much! My collection just gets better and better each day. Here is your reward as I promised.


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+5</span>)


Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guardians of the Vale](/faction/263) got better (<span class='text-success'>+1</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+1</span>)


Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_599.png" alt="" /> <a
                                href="/item/14010" data-url="14010" class="tooltip-link link">Potion of Poison Warding</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_521.png" alt="" /> <a
                                href="/item/13281" data-url="13281" class="tooltip-link link">Silver Bracelet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_521.png" alt="" /> <a
                                href="/item/13280" data-url="13280" class="tooltip-link link">Bracelet of Beetlekind</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_806.png" alt="" /> <a
                                href="/item/14015" data-url="14015" class="tooltip-link link">Spider Venom</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1026.png" alt="" /> <a
                                href="/item/16875" data-url="16875" class="tooltip-link link">Stalking Probe</a>) (+65 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

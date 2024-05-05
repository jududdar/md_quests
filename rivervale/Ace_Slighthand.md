# Ace Slighthand



[Ace Slighthand](/npc/19090) is a level 15 Halfling Rogue that spawns in [Rivervale](/zone/19).






## Dialog

local level = **Your level**;


**You say:** `Hail`




>**Ace Slighthand says:** Hey, hey, hey! Welcome to the Fool's Gold. Don't bet more than you can afford to lose, pal! You don't want toup like ol' [Kevlin]. If you're looking for something to do after you have a drink, you may be interested in a [task].

**You say:** `kevlin`



if **Faction** >= Amiable then 



>**Ace Slighthand says:** Kevlin Diggs. His family sells armor here in Rivervale. He has a nice shop right across from us here. But he owes us Deeppockets some [gold] that we need to collect. We can't rough him up because he is a friend of Mayor Gubbin. We need someone to steal it.


elseif **Faction** >= Indifferent then



>**Ace Slighthand says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Ace Slighthand says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



**You say:** `gold`



if **Faction** >= Amiable then 



>**Ace Slighthand says:** He keeps his money in a sack on his bed. But he has a mean pet wolf, named Mangler, who mangled the last cutpurse we sent after it. If you were to wait until he leaves his shop, then sneak past Mangler and bring me the money he owes us, I will make it worth your time.


elseif **Faction** >= Indifferent then



>**Ace Slighthand says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Ace Slighthand says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


end



## Turn-Ins



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/13182" data-url="13182" class="tooltip-link link">Kevlins Debt</a>) then 


>**Ace Slighthand says:** Heh heh! You got a career ahead of ya kid! Good work. Here is your cut.


 &#127873; **You receive:** 0 (+30 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

else


**This NPC *should* return incorrect items given.**
;
end


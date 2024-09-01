# Tiam Khonsir

[Tiam Khonsir](/npc/24053) is a level 61 Erudite GM Paladin that spawns in [Erudin](/zone/24).

Their primary faction is [Deepwater Knights](/faction/242).

## Dialog
**You say:** `hail`

>**Tiam Khonsir says:** Greetings, Soandso. Are you a follower of our order, the Deepwater Knights, servants of the Ocean Lord, Prexus?
**You say:** `yes`

>**Tiam Khonsir says:** That is good, Soandso. Our followers are few but our faith is strong. With the efforts of those few, our destiny may be reached in time. We must walk with perseverence and devotion, much like the tides that, over time, can destroy a mighty stone cliff. Have you [come to serve our Lord], Soandso?
**You say:** `come.* serve our lord`

if **Faction** >= Dubious +300 then
>**Tiam Khonsir says:** Then I shall send you on a quest to prove your devotion. No doubt you have seen the vermin kobolds scuttling about the land as fleas upon a mangy dog. The kobolds have a lair on our continent from which they launch their wantonly destructive raids. You are to enter that lair and destroy as many of these dogs as you can. For each molar you bring me, you will receive praise, admiration, and perhaps some coin.
else
**Tiam Khonsir says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!

**You say:** `quest of greater importance`

if **Faction** >= Amiable then
>**Tiam Khonsir says:** Very well then, Soandso, you may be able to help us. Go to Breya and tell her I sent you. She will brief you.
elseif **Faction** >= Indifferent then
>**Tiam Khonsir says:** You need to prove your dedication to our cause before I can discuss such matters with you.
else
**Tiam Khonsir says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!

**You say:** `harpoon no more`

>**Tiam Khonsir says:** Well, Soandso, that is unfortunate. Quite a pity, indeed.





## Turn-Ins

local mlr =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_802.png" alt="" /> <a
                                href="/item/1761" data-url="1761" class="tooltip-link link">Kobold Molar</a> x 1

if **Faction** >= Dubious +300 and (mlr > 0))  then 
repeat
>**Tiam Khonsir says:** Wonderful work, friend Soandso. One less land dwelling, flea ridden, primitive for our wondrous lord to sweep aside when the apocalypse is upon us. Here is your reward. Perhaps if you gather enough molars, we can offer you a [quest of greater importance].
local ranitem = 0;
if(math.random(1,6) == 1) then
ranitem = eq.ChooseRandom(3120,3123,3115,3117,3122,3113,3116,3118,3121,3124,3119,3108,3107,3111,3103,3105,3110,3101,3104,3106,3109,3112,3132,3135,3127,3129,3134,3125,3128,3130,3133,3136,3131); 

Your faction standing with [Deepwater Knights](/faction/242) got better (<span class='text-success'>+7</span>)
Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+1</span>)
Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-1</span>)
 &#127873; **You receive:** No item given (+3800 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-6 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 
mlr = mlr - 1;
until mlr == 0

**This NPC *should* return incorrect items given.**
;



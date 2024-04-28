# Tiam Khonsir
## Dialog

**You say:** `hail`



>**Tiam Khonsir says:** Greetings, Soandso. Are you a follower of our order, the Deepwater Knights, servants of the Ocean Lord, Prexus?

**You say:** `yes`



>**Tiam Khonsir says:** That is good, Soandso. Our followers are few but our faith is strong. With the efforts of those few, our destiny may be reached in time. We must walk with perseverence and devotion, much like the tides that, over time, can destroy a mighty stone cliff. Have you [come to serve our Lord], Soandso?

**You say:** `come to serve our lord`



>**Tiam Khonsir says:** Then I shall send you on a quest to prove your devotion. No doubt you have seen the vermin kobolds scuttling about the land as fleas upon a mangy dog. The kobolds have a lair on our continent from which they launch their wantonly destructive raids. You are to enter that lair and destroy as many of these dogs as you can. For each molar you bring me, you will receive praise, admiration, and perhaps some coin.

**You say:** `quest of greater importance`



>**Tiam Khonsir says:** Very well then, Soandso, you may be able to help us. Go to Breya and tell her I sent you. She will brief you.

**You say:** `harpoon no more`



>**Tiam Khonsir says:** Well, Soandso, that is unfortunate. Quite a pity, indeed.
end

## Turn-Ins



local ranitem = 0;


if **You turn in:** [Kobold Molar](/item/1761)


>**Tiam Khonsir says:** Wonderful work, friend Soandso. One less land dwelling, flea ridden, primitive for our wondrous lord to sweep aside when the apocalypse is upon us. Here is your reward. Perhaps if you gather enough molars, we can offer you a [quest of greater importance].


if(math.random(4) == 1) then



ranitem = eq.ChooseRandom(3120,3123,3115,3117,3122,3113,3116,3118,3121,3124,3119,3108,3107,3111,3103,3105,3110,3101,3104,3106,3109,3112,3132,3135,3127,3129,3134,3125,3128,3130,3133,3136,3131); 



* __Faction:__ [Deepwater Knights](/faction/242) (7)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:** None 


e.other:GiveCash(12,14,5,0); 

**This NPC *should* return incorrect items given.**
;


# Miadera Shadowfyre
## Dialog

**You say:** `hail`



>**Miadera Shadowfyre says:** Ahhhahahaha! The terror that lays over this city like a blanket tingles my bones with vigor. I seek a fellow apostle of Cazic-Thule to assist me in the [summoning of Terror].

**You say:** `summoning of terror`



if **Faction** >= Amiable then



>**Miadera Shadowfyre says:** It will be a frightfully fulfilling summons. To do this, I need an eye of urd, some basalt drake scales, the lens of Lord Soptyvr, and a lock of widowmistress hair.


elseif **Faction** >= Indifferent then



>**Miadera Shadowfyre says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.




else



>**Miadera Shadowfyre says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!




end

## Turn-Ins



local text = "I require all four reagents, anything less is useless. Incompetence will get you nowhere amongst the faithful of Cazic-Thule!";



if( **Faction is** > Indifferent and  **You turn in:** [Eye of Urd](/item/10523), [Basalt Drake Scales](/item/19032), [Lens of Lord Soptyvr](/item/14110), [Widowmistress Hair](/item/14109)


>**Miadera Shadowfyre says:** Yes! Can you feel the terror in the air, prickling your flesh, and standing your hair on The chanters have summoned the avatar of Terror! Quickly take this mundane mask to him and he shall forge it into a valuable symbol to be worn by loyal apostles of Terror!


* __Faction:__ [Heretics](/faction/265) (200)


* __Faction:__ [Deepwater Knights](/faction/242) (-200)


* __Faction:__ [Gate Callers](/faction/254) (-200)


* __Faction:__ [Craftkeepers](/faction/231) (-200)


* __Faction:__ [Crimson Hands](/faction/233) (-200)


 **You receive:** None 


**Spawn NPC:**  [avatar of terror](/npc/75195) at (**y:** 1182, **x:** 421)

**This NPC *should* return incorrect items given.**
;






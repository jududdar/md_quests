# Barnal Flamehand
## Dialog

**You say:** `Hail`



>**Barnal Flamehand says:** And a fine day to you, too, Soandso! What is it that brings you here? Fortune? Adventure? In either case. it will be more fun than the duty I have. I am to acquire what scrolls I can for the High Council of Erudin. And you're also in luck, as I seek the services of a mighty adventurer like yourself. Do you wish to [aid me in my duty]?

**You say:** `aid you in your duty`



>**Barnal Flamehand says:** Then you will do this for me. Venture beyond this outpost to the most distant lands and the darkest dungeons. Within them. the creatures with the greatest power will have scrolls. The residents here will be able to give you general locations of the most dangerous places. I wish to obtain the scrolls of Atol's Spectral Shackles, Tears of Druzzil, Inferno of Al'Kabor, and lastly, Pillar of Frost. Make haste, as the High Council cannot be kept waiting! Fear not. I shall [reward] you well.

**You say:** `reward`



>**Barnal Flamehand says:** I am not empty-handed. I have already located some of the most rare scrolls. I'll part with one of my four for what you return to me. Fare thee well!
end

## Turn-Ins



local count =  **You turn in:**  { [Spell: Atol\`s Spectral Shackles](/item/19315),  [Spell: Inferno of Al\`Kabor](/item/19322),  [Spell: Pillar of Frost](/item/19318),  [Spell: Tears of Druzzil](/item/19319)}

if(count > 0) then


repeat



>**Barnal Flamehand says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 **You receive:** eq.ChooseRandom( [Spell: Tears of Solusek](/item/19329), [Spell: Abscond](/item/19320), [Spell: Thunderbold](/item/19324), [Spell: Tishan\`s Discord](/item/19317)) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**






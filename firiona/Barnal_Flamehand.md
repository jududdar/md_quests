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



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19315" data-url="19315" class="tooltip-link link">Spell: Atol\`s Spectral Shackles</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19322" data-url="19322" class="tooltip-link link">Spell: Inferno of Al\`Kabor</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19318" data-url="19318" class="tooltip-link link">Spell: Pillar of Frost</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19319" data-url="19319" class="tooltip-link link">Spell: Tears of Druzzil</a>}

if(count > 0) then


repeat



>**Barnal Flamehand says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19329" data-url="19329" class="tooltip-link link">Spell: Tears of Solusek</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19320" data-url="19320" class="tooltip-link link">Spell: Abscond</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19324" data-url="19324" class="tooltip-link link">Spell: Thunderbold</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19317" data-url="19317" class="tooltip-link link">Spell: Tishan\`s Discord</a>) (+1000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**






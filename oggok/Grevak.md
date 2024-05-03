# Grevak


## Dialog

**You say:** `Hail`



>**Grevak says:** Need new members we do not. Powerful enough are we with Grevak. Still. peons needed. Are you a [new peon] or are you an [outsider]? Speak up!! Fool!! No time Grevak has!!

**You say:** `new peon`



if **Faction** >= Indifferent then




>**Grevak says:** So you think you can be greater than Grevak!! Touch you not and still I can smash you. I am a Greenblood shadowknight!! Peon are you. Peons go to swamps and slay lizardmen. You return with four lizardmen tails and a reward is yours. You return with two lizardman shaman dolls and a great reward is yours.


else



>**Grevak says:** Foe of Greenbloods you are. In two I will rip you. Best if run.


**You say:** `i am an outsider`



>**Grevak says:** Go away or soon your pain will find you.
end



## Turn-Ins



local text = "This enough is not! Two is what Grevak spoke!";




if  ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1132.png" alt="" /> <a
                                href="/item/13354" data-url="13354" class="tooltip-link link">Lizard Tail</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1132.png" alt="" /> <a
                                href="/item/13354" data-url="13354" class="tooltip-link link">Lizard Tail</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1132.png" alt="" /> <a
                                href="/item/13354" data-url="13354" class="tooltip-link link">Lizard Tail</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1132.png" alt="" /> <a
                                href="/item/13354" data-url="13354" class="tooltip-link link">Lizard Tail</a>) then


>**Grevak says:** Now I shall take the lizard tails to shamans I will.  Healing spells will help create. You continue to slay. Continue to be the peon. Continue to live


Your faction standing with [Green Blood Knights](/faction/261) got better (<span class='text-success'>+10</span>)



Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+5</span>)




Your faction standing with [Storm Guard](/faction/312) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Shadowknights of Night Keep](/faction/308) got worse (<span class='text-danger'>-1</span>)



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/2125" data-url="2125" class="tooltip-link link">Large Tattered Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2126" data-url="2126" class="tooltip-link link">Large Tattered Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_643.png" alt="" /> <a
                                href="/item/2127" data-url="2127" class="tooltip-link link">Large Tattered Gorget</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/2129" data-url="2129" class="tooltip-link link">Large Tattered Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/2133" data-url="2133" class="tooltip-link link">Large Tattered Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2134" data-url="2134" class="tooltip-link link">Large Tattered Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_759.png" alt="" /> <a
                                href="/item/9016" data-url="9016" class="tooltip-link link">Large Buckler</a>) (+500 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_720.png" alt="" /> <a
                                href="/item/13367" data-url="13367" class="tooltip-link link">Mystic Doll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_720.png" alt="" /> <a
                                href="/item/13367" data-url="13367" class="tooltip-link link">Mystic Doll</a>) then


>**Grevak says:** A shaman doll! A great knight you some day become. A gift I give to help you on your way. The fight will continue. All hail the Greenbloods!


Your faction standing with [Green Blood Knights](/faction/261) got better (<span class='text-success'>+10</span>)



Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+5</span>)




Your faction standing with [Storm Guard](/faction/312) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Shadowknights of Night Keep](/faction/308) got worse (<span class='text-danger'>-1</span>)



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1018.png" alt="" /> <a
                                href="/item/13453" data-url="13453" class="tooltip-link link">Pickled Lizard</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/5013" data-url="5013" class="tooltip-link link">Rusty Short Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5014" data-url="5014" class="tooltip-link link">Rusty Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/5025" data-url="5025" class="tooltip-link link">Rusty Two Handed Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_605.png" alt="" /> <a
                                href="/item/5016" data-url="5016" class="tooltip-link link">Rusty Broad Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5019" data-url="5019" class="tooltip-link link">Rusty Long Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5020" data-url="5020" class="tooltip-link link">Rusty Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5023" data-url="5023" class="tooltip-link link">Rusty Two Handed Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15343" data-url="15343" class="tooltip-link link">Spell: Siphon Strength</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15235" data-url="15235" class="tooltip-link link">Spell: Invisibility vs Undead</a>) (+500 exp)

 

**This NPC *should* return incorrect items given.**







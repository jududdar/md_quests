# Jemoz Lerkarson
## Dialog

local fac = e.other:GetFaction(e.self);


**You say:** `hail`



>**Jemoz Lerkarson says:** Bless you. my friend!  We always welcome new converts into our Hall of Truth.  The righteous army of the twin deities must assemble.  The battle draws near.  The blessings of the Truthbringer are passed to all who are [devoted to truth].

**You say:** `fallen knight`




>**Jemoz Lerkarson says:** The fallen knight is Sir Lucan D'Lere. The organizer and leader of the Freeport Militia. He once stood beside us. Now he shall burn!! We willhim. We shall [crush the Freeport Militia]. Truth shall reign once again.

**You say:** `true organizer`




>**Jemoz Lerkarson says:** Captain Hazran is the commander of the Freeport Militia. Lucan has no time to waste on relegating duties. Hazran is the one who keeps these brutes together as a militia. Stop him and maybe the militia will collapse. Find a way to return his head to me. That would surely bring great thanks from this temple.

**You say:** `devoted to truth`



if **Faction** >= Amiable then



>**Jemoz Lerkarson says:** May the hand of Marr shield you from harm. Welcome to our world. The war begins here in Freeport. The [fallen knight] has masked the truth from the world, but he cannot mask his evil from the Truthbringer. He once followed our ways. Now he is our enemy and yours. We musthis rule. We must [crush the Freeport Militia]!!



**Jemoz Lerkarson casts:** [Holy Armor](/spell/11) on target.


elseif **Faction** >= Indifferent then



>**Jemoz Lerkarson says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Jemoz Lerkarson says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.


**You say:** `crush the freeport militia`



if **Faction** >= Amiable then



>**Jemoz Lerkarson says:** 'Our goal is totheir rule. To retake our city in the name of Marr. Let it begin with their blood!! Slay the militia!! They have no souls and hail from the back alleys and prison cells of darkness and depravity. Thieves and murderers, nothing more. Slay any you can and, as proof, return their militia helms to me. We shall see what bounty you deserve.


elseif **Faction** >= Indifferent then



>**Jemoz Lerkarson says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Jemoz Lerkarson says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.

end

## Turn-Ins




if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_550.png" alt="" /> <a
                                href="/item/13921" data-url="13921" class="tooltip-link link">Damaged Militia Helm</a>) then


>**Jemoz Lerkarson says:** Bless you, my child. Marr is grateful, as are we. Here is our thanks. Let it bring you greater strength to defeat the Militia. Go and continue the crusade. Soon you will be strong enough to slay the [true organizer].


**Jemoz Lerkarson casts:** [Light Healing](/spell/17) on target.


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+10</span>)


Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+2</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+5000 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/12142" data-url="12142" class="tooltip-link link">Human Head</a>) then


>**Jemoz Lerkarson says:** We heard of your assault. We even attempted to slay Lucan. Alas, we failed. You have done your part and as such have earned our thanks. Beware of the Freeport Militia. They will no doubt be on the lookout for you. May Marr protect you. Perhaps you should speak with Valeron Dushire, paladin of the Knights of Truth. He seeks other to slay the fallen knight.


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+20</span>)


Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+4</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15560" data-url="15560" class="tooltip-link link">Spell: Furor</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15230" data-url="15230" class="tooltip-link link">Spell: Root</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15219" data-url="15219" class="tooltip-link link">Spell: Center</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15229" data-url="15229" class="tooltip-link link">Spell: Fear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15222" data-url="15222" class="tooltip-link link">Spell: Invigor</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15012" data-url="15012" class="tooltip-link link">Spell: Healing</a>) (+5000 exp)

 

**This NPC *should* return incorrect items given.**

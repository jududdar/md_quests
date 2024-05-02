# Lozani
## Dialog

**You say:** `hail`



>**Lozani says:** Greetings. friend!!  I am Lozani. Scribe Supreme of the Eldritch Collective.  I have been sent forth from the great Library of Mechanimagica in the city of Ak'Anon. to study the arcane knowledge of man and beast alike.  I have studied many languages and spells. from Crushbone to Kerra Ridge.  I have found most languages hard to decipher.  As of this date. I have learned to read only the script of the [orc oracles].  Oh well. I am on a five decade mission.  Better luck next language.

**You say:** `orc oracles`



>**Lozani says:** Oh!! Heard of the orc oracles have you? A ghastly bunch they are!! Argh! The numerous days I spent interrogating those beasts with their foul breath. It was as if rats had gone and died in their mouths. I wished I could read minds after those days. TWENTY WEEKS of that rat-carcass breath and all I have learned is the ability to decipher [oracle scrolls] and [apprentice cantrips]. What a mess that was! I'm beginning to think I should have become a Gemchopper.

**You say:** `oracle scroll`



>**Lozani says:** Orc oracle scrolls? Mere shaman spells are they. I know how to decipher those illegible scrolls. I can do so, but it will cost you. Nothing is for free in this world, y'know? You give me one of those illegible scrolls and four gold coins.

**You say:** `apprentice cantrips`



>**Lozani says:** Orc apprentice cantrips. Child's play they are. Very difficult to decipher, mostly due to the orc sweat smearing the writing. I fill in the blanks with a second orc cantrip and my universe of knowledge, so you never know what spell is going to be scribed! Could be magic, could be wizardry, could be necromancy, golly!! Sometimes I evenup with a recipe!! If you want me to try to decipher one just hand me two illegible cantrips. No coinage necessary!! They are mostly apprentice spells. Nothing much.
end

## Turn-Ins



local text1 = "I need TWO illegible cantrips. Not much to ask for.";

local text2 = "Hey! I said FOUR gold and the illegible scroll! Sheesh.";

local scroll = 0;


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13225" data-url="13225" class="tooltip-link link">Illegible Scroll</a>,gold = 4) then 


>**Lozani says:** Hmmm... Aha! Well, I think this is it. A fine spell. I hope you need it because you are not getting your gold back.


scroll = 1;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13845" data-url="13845" class="tooltip-link link">Illegible Cantrip</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13845" data-url="13845" class="tooltip-link link">Illegible Cantrip</a>) then 


>**Lozani says:** And the winning spell is... Here, you do the honors.


scroll = 1;

if(scroll == 1) then


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15200" data-url="15200" class="tooltip-link link">Spell: Minor Healing</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15042" data-url="15042" class="tooltip-link link">Spell: Invisibility</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15226" data-url="15226" class="tooltip-link link">Spell: Endure Disease</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15246" data-url="15246" class="tooltip-link link">Spell: Lesser Shielding</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15276" data-url="15276" class="tooltip-link link">Spell: Serpent Sight</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15211" data-url="15211" class="tooltip-link link">Spell: Summon Drink</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15203" data-url="15203" class="tooltip-link link">Spell: Cure Poison</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15054" data-url="15054" class="tooltip-link link">Spell: Frost Bolt</a>) (+100 exp)

 


scroll = 0;

**This NPC *should* return incorrect items given.**

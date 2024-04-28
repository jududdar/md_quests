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


if **You turn in:** [Illegible Scroll](/item/13225),gold = 4


>**Lozani says:** Hmmm... Aha! Well, I think this is it. A fine spell. I hope you need it because you are not getting your gold back.


scroll = 1;

elseif **You turn in:** [Illegible Cantrip](/item/13845), [Illegible Cantrip](/item/13845)


>**Lozani says:** And the winning spell is... Here, you do the honors.


scroll = 1;

if(scroll == 1) then


 **You receive:** eq.ChooseRandom( [Spell: Minor Healing](/item/15200), 15042, 15226, 13360, 15246, 15276, 15211, 15203, 15054) (+100 exp)


scroll = 0;

**This NPC *should* return incorrect items given.**

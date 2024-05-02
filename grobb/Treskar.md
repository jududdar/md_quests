# Treskar



## Dialog

**You say:** `hail`



>**Treskar says:** You dare speak to Master Treskar!  You be [sent by Hukulk] or you be hurtin'! Me have no time to waste with ugly one like you!

**You say:** `sent by hukulk`



>**Treskar says:** Ha!  Hukulk accept puny troll now?!  Ha!  You join us and you join fight.  Nightkeep enemy is Soandso enemy!  You help smash [other weak shadowknights].  Them weak.  We true power!  You bash good and maybe you do [secret mission] for Treskar.

**You say:** `other weak shadowknights`



if **Faction** >= Amiable then




>**Treskar says:** Other shadowknights is ogre shadowknights! They name is Greenbloods. They no match for Nightkeep! We tear arms from ogre bodies. You not as powerful as Treskar so you smash young Greenbloods. You hunt YOUNG members of Greenblood shadowknights. You bring me black shadow tunic and me share treasures from Nightkeep vault with puny Soandso. Go


elseif **Faction** >= Indifferent then



>**Treskar says:** Me talk to you 'bout dat when you do more to help Nightkeep!  Kill all Greenbloods!  Kill all froggies!


else



>**Treskar says:** <..Sniff, sniff, sniff..>  Me smell the blood of enemy in you.  You fool to talk to Nightkeep shadowknight!  Me bleed you if you no run!


**You say:** `secret mission`



if **Faction** >= Amiable then




>**Treskar says:** Nightkeep hear bashers see fungus man spore guardian at Innothule. Him protect young fungus man spores so they grow big, BIG an' attack trolls!! You go find spore guardian. Smash hi big red head!! Bring Treskar that huge mushroom head of his to prove he walk no more. You do this and me give you froglok skin mask.


elseif **Faction** >= Indifferent then



>**Treskar says:** Me talk to you 'bout dat when you do more to help Nightkeep!  Kill all Greenbloods!  Kill all froggies!


else



>**Treskar says:** <..Sniff, sniff, sniff..>  Me smell the blood of enemy in you.  You fool to talk to Nightkeep shadowknight!  Me bleed you if you no run!


end

## Turn-Ins



local text = "Me change mind! Me want total of THREE ogre black shadow tunics. Ha Ha! And you also pay two gold for Nightkeep tax! Ha! Ha!";




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_854.png" alt="" /> <a
                                href="/item/12190" data-url="12190" class="tooltip-link link">Huge Mushroom Head</a>) then


>**Treskar says:** You do it! You am great knight. Me give you special froglok skin mask. Shaman make for Nightkeep. It am make you smarter like Treskar... Me tink so!


Your faction standing with [Shadowknights of Night Keep](/faction/308) got better (<span class='text-success'>+20</span>)



Your faction standing with [Broken Skull Clan](/faction/222) got worse (<span class='text-danger'>-3</span>)



Your faction standing with [Broken Skull Clan](/faction/222) got worse (<span class='text-danger'>-5</span>)



Your faction standing with [Da Bashers](/faction/235) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2308" data-url="2308" class="tooltip-link link">Froglok Skin Mask</a> (+10000 exp)

 

elseif  **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_538.png" alt="" /> <a
                                href="/item/12199" data-url="12199" class="tooltip-link link">Black Shadow Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_538.png" alt="" /> <a
                                href="/item/12199" data-url="12199" class="tooltip-link link">Black Shadow Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_538.png" alt="" /> <a
                                href="/item/12199" data-url="12199" class="tooltip-link link">Black Shadow Tunic</a>, gold = 2) then 


>**Treskar says:** Hmm... You do good job. You surprise Treskar. Maybe you good after all. Maybe Treskar give you [secret mission]. Maybe not


Your faction standing with [Shadowknights of Night Keep](/faction/308) got better (<span class='text-success'>+20</span>)



Your faction standing with [Broken Skull Clan](/faction/222) got worse (<span class='text-danger'>-3</span>)



Your faction standing with [Broken Skull Clan](/faction/222) got worse (<span class='text-danger'>-5</span>)



Your faction standing with [Da Bashers](/faction/235) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6014" data-url="6014" class="tooltip-link link">Rusty Warhammer</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5023" data-url="5023" class="tooltip-link link">Rusty Two Handed Sword</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6013" data-url="6013" class="tooltip-link link">Rusty Two Handed Hammer</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_776.png" alt="" /> <a
                                href="/item/7009" data-url="7009" class="tooltip-link link">Rusty Spear</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/5013" data-url="5013" class="tooltip-link link">Rusty Short Sword</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5021" data-url="5021" class="tooltip-link link">Rusty Scimitar</a>) (+1000 exp)

 

**This NPC *should* return incorrect items given.**

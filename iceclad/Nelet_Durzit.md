# Nelet Durzit

[Nelet Durzit](/npc/110059) is a level 30 Gnome Rogue that spawns in [Iceclad Ocean](/zone/110).

Their primary faction is [Pirates of Iceclad](/faction/447).

## Dialog
**You say:** `hail`

>*Nelet Durzit sneezes and wipes his hand across his nose.  'H-h-h-i.'*
e.self:DoAnim(52);
if(**spawned NPC:**  [Rendap](/npc/110060)) then
eq.get_entity_list():GetMobByNpcTypeID(110060):Say("Nelet don't talk much anymore.  All this cold really gets to 'im.");

**You say:** `cold`

>*Nelet Durzit talks through clenched, chattering teeth.  'Y-y-yeah.  C-cursed cold.  Sh-sh-shot of gnomish pirate triple strength rum's all I need ta fix me up, Rendap tells me.  N-n-nilham lost it all, though.'*





## Turn-Ins


if( **You turn in:**   <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_703.png" alt="" /> <a
                                href="/item/30034" data-url="30034" class="tooltip-link link">Capt. Nalot's Triple Strength Rum</a> ) then
>*Nelet Durzit greedily swigs rum from the jug.  After a few drinks, he starts to gag and make faces.  'Oh, geez!  Rendap told me this stuff was strong but this tastes like clockwork grease!  It burns but now I feel - ugh.'  Nelet doubles over and passes out on the ground.  As he falls over, a small silver trinket slips out of his pocket.*
if(**spawned NPC:**  [Rendap](/npc/110060)) then
eq.get_entity_list():GetMobByNpcTypeID(110060):Emote("points and laughs as Nelet falls over.  'That'll put hair on yer ears, boy.  Suck it up.  Least ya ain't shiverin' o' cold anymore, eh?'");

 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1043.png" alt="" /> <a
                                href="/item/30033" data-url="30033" class="tooltip-link link">Rough Silver Chain</a> 

 

**This NPC *should* return incorrect items given.**


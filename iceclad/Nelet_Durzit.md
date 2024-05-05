# Nelet Durzit



[Nelet Durzit](/npc/110059) is a level 30 Gnome Rogue that spawns in [Iceclad Ocean](/zone/110).



## Dialog

**You say:** `hail`



>*Nelet Durzit sneezes and wipes his hand across his nose.  'H-h-h-i.'*


e.self:DoAnim(52);


if(**spawned NPC:**  [Rendap](/npc/110060)) then



eq.get_entity_list():GetMobByNpcTypeID( [Rendap](/npc/110060)):Say("Nelet don't talk much anymore.  All this cold really gets to 'im.");


**You say:** `cold`



>*Nelet Durzit talks through clenched, chattering teeth.  'Y-y-yeah.  C-cursed cold.  Sh-sh-shot of gnomish pirate triple strength rum's all I need ta fix me up, Rendap tells me.  N-n-nilham lost it all, though.'*
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1043.png" alt="" /> <a
                                href="/item/30033" data-url="30033" class="tooltip-link link">Rough Silver Chain</a> 

 

**This NPC *should* return incorrect items given.**

end
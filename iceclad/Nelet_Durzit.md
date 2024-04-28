# Nelet Durzit
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





if **You turn in:** [Capt. Nalot's Triple Strength Rum](/item/30034)


>*Nelet Durzit greedily swigs rum from the jug.  After a few drinks, he starts to gag and make faces.  'Oh, geez!  Rendap told me this stuff was strong but this tastes like clockwork grease!  It burns but now I feel - ugh.'  Nelet doubles over and passes out on the ground.  As he falls over, a small silver trinket slips out of his pocket.*


if(**spawned NPC:**  [Rendap](/npc/110060)) then



eq.get_entity_list():GetMobByNpcTypeID( [Rendap](/npc/110060)):Emote("points and laughs as Nelet falls over.  'That'll put hair on yer ears, boy.  Suck it up.  Least ya ain't shiverin' o' cold anymore, eh?'");



 **You receive:**  [Rough Silver Chain](/item/30033) 

**This NPC *should* return incorrect items given.**

end
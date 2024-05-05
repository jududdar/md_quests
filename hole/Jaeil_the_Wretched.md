# Jaeil the Wretched



[Jaeil the Wretched](/npc/39041) is a level 55 Erudite Warrior that spawns in [The Hole](/zone/39).





## On NPC Spawn

eq.set_proximity(e.self:GetX() - 20, e.self:GetX() + 20, e.self:GetY() - 20, e.self:GetY() + 20);
function event_enter(e)

**Set a timer** named *chatter* for 10 seconds
function event_exit(e)

**Stop timer** named *chatter*


## Timer(s)

if(e.timer == "chatter") then


>*Jaeil the Wretched whimpers pathetically as his reflection catches his eye. He turns and stares pitifully at the ceiling.*


>*Jaeil the Wretched shields his eyes from his reflection in the water, occasionally gibbering as he scratches at a flapping, rotted patch of skin on his sunken face. In his arms he cradles something. He seems to emanate an aura of power.*
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_858.png" alt="" /> <a
                                href="/item/17860" data-url="17860" class="tooltip-link link">Shiny Tin Bowl</a>) then


>*Jaeil the Wretched howls in anger, his body seeming to suck energy from the walls around him as he sees his reflection. He pulls a hammer from the bundle in his arms and swings fiercely at your head.*


**Spawn NPC:**  [Jaeil the Insane](/npc/39154) at this location.


**Jaeil the Wretched despawns.**


**Stop timer** named *chatter*


eq.clear_proximity();

**This NPC *should* return incorrect items given.**



## On NPC Death

**Stop timer** named *chatter*

eq.clear_proximity();





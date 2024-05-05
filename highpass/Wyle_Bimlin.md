# Wyle Bimlin



[Wyle Bimlin](/npc/4073) is a level 20 Human Shopkeeper that spawns in [Highpass Hold](/zone/5).



## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Wyle Bimlin picks an item up from the ground and says, 'Hey! Look what I found! Another piece of rubbish for my trailer... Must be my lucky day.*




## Dialog

**You say:** `hail`



>**Wyle Bimlin says:** Greetings, fine friend! I bet you are in need of some fine tonics. Feeling a little low? Take a drink of my fine Zap Doodle Tonic. It will give you the energy of five hill giants! You are in luck, my friend! I have it on sale today, and today only. Matter of fact, the sale ends in five minutes or five footsteps, whichever comes first. So don't be down... get an upside-down frown with my Zap Doodle Tonic! All sales are final.
end
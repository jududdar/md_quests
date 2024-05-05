# Ghost of Burdael



[Ghost of Burdael](/npc/121015) is a level 49 Ghost Shadow Knight that spawns in [Crystal Caverns](/zone/121).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Dialog

**You say:** `hail`



>*Ghost of Burdael says, in an unknown tongue, 'Hgidf! Hsdh je shafoin jsjsi!... Frundlpap gnut hfna iiongio... Woha?! Yiond?'*

**You say:** `Yiond`



>*Ghost of Burdael says, in an unknown tongue, 'Yiond?!?!? Yohodfnon jf awhicin fhnn fhgou vu ganferdefli sahbfnfn. Yexsf asfsdfupoi xubeni gindas hguj quetsrrop. Pliuhghtn gurintop noe?'*
end



## Combat

if Ghost of Burdael enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

**Ghost of Burdael despawns.**
end
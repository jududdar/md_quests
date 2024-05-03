# Diana


## Dialog

Brittina = eq.get_entity_list():GetMobByNpcTypeID(126213);

Ashley = eq.get_entity_list():GetMobByNpcTypeID(126207);

Roxxanne = eq.get_entity_list():GetMobByNpcTypeID(126184);


**You say:** `hail`



>**Diana says:** Well hello! We are great dancers. Would you like to see us dance? Or maybe you would like us to teach you to dance?

**You say:** `see you dance`



Brittina:Say("Hey! Yeah! Do the Marinara!");


Ashley:Say("Hey! Yeah! Do the Marinara!");


Roxxanne:Say("Hey! Yeah! Do the Marinara!");


Brittina:DoAnim(33);


Ashley:DoAnim(33);


e.self:DoAnim(33);


Roxxanne:DoAnim(33);

**You say:** `teach me`



**Diana casts:** [Magi Curse](/spell/806) on target.


>**Diana says:** Look at you! You can dance! Go, go, go! That's the spirit, you got it! Keep up the good work! Don't get too tired now, you are looking a little pale!
end

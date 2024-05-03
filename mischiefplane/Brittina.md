# Brittina


## Dialog

Ashley = eq.get_entity_list():GetMobByNpcTypeID(126207);

Diana = eq.get_entity_list():GetMobByNpcTypeID(126187);

Roxxanne = eq.get_entity_list():GetMobByNpcTypeID(126184);


**You say:** `hail`



>**Brittina says:** Well hello! We are great dancers. Would you like to see us dance? Or maybe you would like us to teach you to dance?

**You say:** `see you dance`



Ashley:Say("Hey! Yeah! Do the Marinara!");


Diana:Say("Hey! Yeah! Do the Marinara!");


Roxxanne:Say("Hey! Yeah! Do the Marinara!");


e.self:DoAnim(33);


Ashley:DoAnim(33);


Diana:DoAnim(33);


Roxxanne:DoAnim(33);

**You say:** `teach me`



**Brittina casts:** [Magi Curse](/spell/806) on target.


>**Brittina says:** Look at you! You can dance! Go, go, go! That's the spirit, you got it! Keep up the good work! Don't get too tired now, you are looking a little pale!
end

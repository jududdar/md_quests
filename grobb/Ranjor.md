# Ranjor


## Dialog

**You say:** `hail`



>**Ranjor says:** Ya wanna be a member a Da Bashers, duz ya?  What making ya tink yooz is good nuff ta be one o' us?  Can ya proves ta me why I shouldn't oughtta just eat yer smelly hide?  I gonna tests ya, ya big, ugly peece o' meet.  Ya [willin ta test] or duz I just eats ya now?

**You say:** `willin ta test`



if **Faction** >= Amiable then






>**Ranjor says:** Stoopid meat.  I gonna eats ya anyways sumday.  Brings me a froglok meat and two dem li'l froglok tadpole fleshes.  Dey berry good.


elseif **Faction** >= Indifferent then



>**Ranjor says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Ranjor says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



if ( **You turn in:** [A tattered note](/item/18790)) then 


>**Ranjor says:** Arhh.. Ranjor mighty warrior.. Ranjor teach you warrior.. you fight for Ranjor now.


* __Faction:__ [Da Bashers](/faction/235) (100)



* __Faction:__ [Broken Skull Clan](/faction/222) (-15)


 **You receive:**  [Mud Covered Tunic*](/item/13528) (+20 exp)

elseif  **Faction** >= Amiable and  **You turn in:** [Froglok Meat](/item/13409), [Froglok Tadpole Flesh](/item/13187), [Froglok Tadpole Flesh](/item/13187)) then


>**Ranjor says:** You is berry slow. Me too hungry. Me shood eats you for being slow. Gib me dat stuff. Here, take dis and git more stuff fer us. You much kllin, come backs sees me. I teeches ya hows ta kill bedder. Now git and kill stuff. We be Da Bashers fer a reesun.


* __Faction:__ [Da Bashers](/faction/235) (5)



* __Faction:__ [Broken Skull Clan](/faction/222) (-1)




 **You receive:**  [Rusty Two Handed Battle Axe](/item/5025) (+1000 exp)

**This NPC *should* return incorrect items given.**

# Tuuak


## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Tuuak says:** Another fine day for ice fishing here in Kael.


elseif **Faction** >= Indifferent then



>**Tuuak says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Tuuak says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `fishing`



if **Faction** >= Amiable then



>**Tuuak says:** You should get a rod and fish, too.  It can be very relaxing.


elseif **Faction** >= Indifferent then



>**Tuuak says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Tuuak says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

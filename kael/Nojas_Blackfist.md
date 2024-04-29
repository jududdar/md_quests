# Nojas Blackfist
## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Nojas Blackfist says:** What brings you to the hall of the frost giants, little one? Have you come to serve our lord and master? Or are you simply a scout for a raiding party? I warn you, do not make war on my kin. I will twist the elements to my will and destroy you if that is your intent.


else



**Nojas Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `serve`



if **Faction** >= Amiable then



>**Nojas Blackfist says:** You could best serve the masters by serving me. The more time I have to tend to my research the better. I have several minor tasks which you could easily handle...


elseif **Faction** >= Indifferent then



>**Nojas Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Nojas Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `minor task`



if **Faction** >= Amiable then



>**Nojas Blackfist says:** In the wreched jungle to the west there lives a race of faries protected by Tunare and her other minions. These abominations are called the Sifaye. I belive that the strength of the Wakening lands is linked not only to Tunare herself, but her connection with these foul beasts. Bring me the wings of one of their so called knights and the heads of three commoners and I will reward you for such busy work.


elseif **Faction** >= Indifferent then



>**Nojas Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Nojas Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `elements`



if **Faction** >= Amiable then



>**Nojas Blackfist says:** The elements of  nature, of course!  Over the years, I have learned that I can bend the powers of nature and the spirits of those long passed to my will and achieve many things.


elseif **Faction** >= Indifferent then



>**Nojas Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Nojas Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** [Wings of a Sifaye Knight](/item/25112), [Sifaye Head](/item/25113), [Sifaye Head](/item/25113), [Sifaye Head](/item/25113)) then


>**Nojas Blackfist says:** Congratulations, slayer of tiny beasts. Take this living tattoe for your troubles.  If you wish to continue to serve me, find a way to capture more noble sifaye... alive.





* __Faction:__ [Kromrif](/faction/419) (10)


* __Faction:__ [Kromzek](/faction/448) (2)


* __Faction:__ [Coldain](/faction/406) (-5)


* __Faction:__ [Claws of Veeshan](/faction/430) (-1)


 **You receive:**  [Silver Dragon Tattoo](/item/25056) (+5000 exp)

**This NPC *should* return incorrect items given.**

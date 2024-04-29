# Clrakk Blackfist
## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>*Clrakk Blackfist looks down at you. 'What is it you want, Soandso? Why do you speak to the great Knight Clrakk Blackfist?*


else



**Clrakk Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `bring strife`



if **Faction** >= Amiable then



>**Clrakk Blackfist says:** The Coldain have grown complacent. The defenses of their city are built to keep my kind and dragonkind at bay. However, their defenses against the smaller races such as yourself are not nearly as sophisticated. I wish to kill many Coldain, but now is not the time for that. There is a particular Coldain whose death will strike fear into the hearts of many. His name is Deaen Greyforge, a Coldain knight. He is both feared and respected by his kind. If you can destroy him, it will send a message to the Coldain that they are not safe from the wrath of the giants. Kill him and chop his body into bits. Bring me a few pieces as proof that the fool is dead.


elseif **Faction** >= Indifferent then



>**Clrakk Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Clrakk Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `knight`



if **Faction** >= Amiable then



>**Clrakk Blackfist says:** Yes, I am a knight.  One who walks a dark path of blood and hatred.  In your realms, one such as myself is called a shadowknight.


elseif **Faction** >= Indifferent then



>**Clrakk Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Clrakk Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins





if( **You turn in:** [Hand of Deaen Greyforge](/item/25115)) then 


>**Clrakk Blackfist says:** You truly are a bringer of strife, Soandso. Take this. I hope it will assist you. Use it in our war against the Coldain scum.





* __Faction:__ [Kromrif](/faction/419) (10)


* __Faction:__ [Kromzek](/faction/448) (2)


* __Faction:__ [Coldain](/faction/406) (-5)


* __Faction:__ [Claws of Veeshan](/faction/430) (-1)


 **You receive:**  [Mask of Malediction](/item/25054) (+1000 exp)

elseif( **You turn in:** [Legs of Deaen Greyforge](/item/25114)) then 


>**Clrakk Blackfist says:** You truly are a bringer of strife, Soandso. Take this. I hope it will assist you. Use it in our war against the Coldain scum.





* __Faction:__ [Kromrif](/faction/419) (10)


* __Faction:__ [Kromzek](/faction/448) (2)


* __Faction:__ [Coldain](/faction/406) (-5)


* __Faction:__ [Claws of Veeshan](/faction/430) (-1)


 **You receive:**  [Dark Spear of Venom](/item/25051) (+1000 exp)

**This NPC *should* return incorrect items given.**

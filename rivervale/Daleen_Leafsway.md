# Daleen Leafsway


## On NPC Spawn

**Set a timer** named *blurt* for 600 seconds


## Dialog 




**You say:** `hail`



>**Daleen Leafsway says:** Greetings, Soandso.  Welcome to Tagglefoot's Farm.  We grow nothing but the finest vegetables in our field.  We even manage to harvest the mystical jumjum stalk in our fields.  Karana has blessed us indeed.

**You say:** `starving`



if **Faction** >= Amiable then 



>**Daleen Leafsway says:** Deputy Eigon! I forgot! I was supposed to bring him some turnips to eat while he is on patrol! Oh... He asked so nicely, too. I feel bad that I forgot. If only someone would take these [turnips] to the Deputy..


elseif **Faction** >= Indifferent then



>**Daleen Leafsway says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Daleen Leafsway says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



**You say:** `turnips`



if **Faction** >= Amiable then 



>**Daleen Leafsway says:** Oh, thank you so much! You can keep any payment he gives you. Be sure to tell him I'm sorry.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/16165" data-url="16165" class="tooltip-link link">Sack of Turnips</a>


elseif **Faction** >= Indifferent then



>**Daleen Leafsway says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Daleen Leafsway says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


end



## Timer(s)

if (timer == "blurt") then


>**Daleen Leafsway says:** Oh Dear.. I can't believe I forgot.. He must be [starving]!
end




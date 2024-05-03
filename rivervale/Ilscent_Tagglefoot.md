# Ilscent Tagglefoot


## Dialog

**You say:** `hail`



>**Ilscent Tagglefoot says:** Oh hello, Soandso.  My name is Ilscent.   I am glad to see you, but I am in a bit of a [bind] right now.

**You say:** `bind`



if **Faction** >= Amiable then



>**Ilscent Tagglefoot says:** Well, I promised an ally of ours that I would send him a case of Jumjum juice for all the help he has given us.  I had planned on taking it to him myself but I have too many chores to do here on the farm. Will you take the [jumjum juice] to him?


elseif **Faction** >= Indifferent then



>**Ilscent Tagglefoot says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Ilscent Tagglefoot says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



**You say:** `jumjum juice`



if **Faction** >= Amiable then



>**Ilscent Tagglefoot says:** Oh, thank you so much!  His name is Xanuusus and he lives in the Plains of Karana, in the foothills along their northern edge, actually.  We are most grateful for your help.  Xanuusus normally rewards messengers well.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/13411" data-url="13411" class="tooltip-link link">Case of Jumjum Juice</a>


elseif **Faction** >= Indifferent then



>**Ilscent Tagglefoot says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Ilscent Tagglefoot says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


end




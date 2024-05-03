# Sarhya the Dawnbreeze


## Dialog

local qglobals = eq.get_qglobals(e.other);



**You say:** `hail`



if ( qglobals.zebuxoruk and qglobals.zebuxoruk == "2" ) then



>**Sarhya the Dawnbreeze says:** It appears that you are ready to travel into the Elemental Planes.  Beware many of the gods there have set up wards to protect them against assaults.  Most I cannot speak about; however I do have information on the Circle of Protection that guards Xegony, in her [Plane of Air].


else



>**Sarhya the Dawnbreeze says:** Well met.  I am keeper of the Portal to the [Plane of Air].





**You say:** `plane of air`



if ( qglobals.zebuxoruk and qglobals.zebuxoruk == "2" ) then



>**Sarhya the Dawnbreeze says:** Xegony has created four avatars, each one embodies a different aspect of her power, and each of these avatars was created with a portion of her very essence. The story goes, the one who possesses each of these essences may create a key to break Xegony's ward and enter into her inner sanctum. I don't know the truth behind this, as I have neither the power, nor the desire to challenge the Avatars myself. I have fashioned this, which I believe will form the four essences into a key.



if ( not **You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_739.png" alt="" /> <a
                                href="/item/17888" data-url="17888" class="tooltip-link link">Pouch of Swirling Winds</a> x 1




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_739.png" alt="" /> <a
                                href="/item/17888" data-url="17888" class="tooltip-link link">Pouch of Swirling Winds</a>




else



>**Sarhya the Dawnbreeze says:** The Elemental Planes are not for idle exploration. Return to me when you have a reason to enter and I will consider opening the portal for you.

end

# Fodin Frugrin










## Dialog

**You say:** `hail`



>**Fodin Frugrin says:** Hello Soandso. Have you ever peered beyond our little world? Somewhere out there in the vast darkness is a world filled with great technology and adventure. Our people should concentrate on reaching these distant worlds beyond the sparkling skies.

**You say:** `who`



>**Fodin Frugrin says:** I am Fodin Frugin, observer for the Library of Mechanimagica.

**You say:** `larkon sent me`



if( **Faction is** >= Amiable) then



>**Fodin Frugrin says:** So they found another young member to attend to their putrid hunt, eh? Take this box. You will notice that your box has ten slots and does not smell very good. That is because each slot must be filled with the diseased livers of infected rats. Hop to it, then! Go get some diseased livers. And if you should get bitten and find yourself diseased or poisoned, be sure to visit the Abbey of Deep Musing. They have healers who can cure disease. Do not forget to return the box to Larkon



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/17923" data-url="17923" class="tooltip-link link">Air Tight Box</a>


elseif( **Faction is** == Indifferent) then



>**Fodin Frugrin says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Fodin Frugrin says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.



**You say:** `lens`



if( **Faction is** >= Amiable) then



>**Fodin Frugrin says:** Spare Telescopic Lens?? I am sorry but I don't have any spares right now.. Oh wait!! I do. Here you are my friend. Careful with that. They are very rare.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1129.png" alt="" /> <a
                                href="/item/13277" data-url="13277" class="tooltip-link link">A Telescope Lens</a>


elseif( **Faction is** == Indifferent) then



>**Fodin Frugrin says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Fodin Frugrin says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.

end

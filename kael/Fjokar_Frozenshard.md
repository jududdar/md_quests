# Fjokar Frozenshard



[Fjokar Frozenshard](/npc/113153) is a level 60 Giant Rogue that spawns in [Kael Drakkel](/zone/113).





## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Fjokar Frozenshard says:** Today is a good day in Kael Drakkel. Don't you think?


else



**Fjokar Frozenshard says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `today is a good day`



if **Faction** >= Indifferent then



>*Fjokar Frozenshard snickers.  Do you always repeat what others say, Human?  Pestering me is a good way toup dead.*



else



**Fjokar Frozenshard says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `wenglawk`



if **Faction** >= Amiable then



>**Fjokar Frozenshard says:** Wenglawks masquerades as a noble. As family lines go, his is even more diluted than those two Iceshard brothers. He is a petty merchant and traitor. One day I will find my proof of this.


elseif **Faction** >= Indifferent then



>**Fjokar Frozenshard says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Fjokar Frozenshard says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `iceshard brother`



if **Faction** >= Amiable then



>**Fjokar Frozenshard says:** Klaggan and Vorken, those two ruffians who somehow have managed to become the lords of the Kromrif manor. They were nothing but a pair of thugs no less than twenty years ago. I remember watching them kill and maim the innocent among the Kromrif tribes. If it were not for King Tormax's protection, I would slay them.


elseif **Faction** >= Indifferent then



>**Fjokar Frozenshard says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Fjokar Frozenshard says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `kromrif`



if **Faction** >= Amiable then



>**Fjokar Frozenshard says:** The Frost giants are a proud race, but they are not nearly as powerful and blessed as we Kromzek. Our cousins may be strong, but the might of an enraged storm giant is something to behold.


elseif **Faction** >= Indifferent then



>**Fjokar Frozenshard says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Fjokar Frozenshard says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `courier`



if **Faction** >= Amiable then



>**Fjokar Frozenshard says:** Those Kromzek deserve to die. They know very well what he is up to. I will hunt them for sport, moving silently through the streets of Kael Drakkel, and invisibly through the outside world. Wenglawks has some sort of underhanded deals going on with the dragons. I have yet to find anything which will persuade King Tormax to allow me to slay him, unfortunately.


elseif **Faction** >= Indifferent then



>**Fjokar Frozenshard says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Fjokar Frozenshard says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `dead`



if **Faction** >= Amiable then



>*Fjokar Frozenshard pats an ice covered spear at his side.  'This spear has been the demise of many.  A swift stab to the back of an unsuspecting foe is all that it takes.  I am still waiting for that thick headed Wenglawks to discover who has been killing his poor couriers.*


elseif **Faction** >= Indifferent then



>**Fjokar Frozenshard says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Fjokar Frozenshard says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/1717" data-url="1717" class="tooltip-link link">Sealed Letter</a>) then 


>**Fjokar Frozenshard says:** You have found what I was unable to. King Tormax's protection of Wenglawks willsoon. His death will be so very delightful to invoke. 'rushes out of the room, dropping his spear as he does.'


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+20</span>)


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+20</span>)


Your faction standing with [Yelinak](/faction/436) got worse (<span class='text-danger'>-10</span>)


Your faction standing with [Dain Frostreaver IV](/faction/405) got worse (<span class='text-danger'>-10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/25030" data-url="25030" class="tooltip-link link">Frozen Shard</a> (+75000 exp)

 

**This NPC *should* return incorrect items given.**

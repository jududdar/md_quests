# Frundle Frenkler



[Frundle Frenkler](/npc/115006) is a level 30 Coldain Shopkeeper that spawns in [The City of Thurgadin](/zone/115).





## Dialog

if ( **Faction is** > Apprehensive) then


**You say:** `velium vapor`




>**Frundle Frenkler says:** Ahh, you come seeking my family recipe? After all you've done for our people it's the least I can do. First you must fashion a velium vial, then combine the vial with two small pieces of velium in this jar. That's all there is to it. Please keep the recipe a secret.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1239.png" alt="" /> <a
                                href="/item/17513" data-url="17513" class="tooltip-link link">Velium Purifier</a>


**You say:** `velium vial`




>**Frundle Frenkler says:** I'm no potter mind you, but if I remember correctly it's a small brick of velium, three crystalline silks, and two glass shards. Then you'll have to finish up by firing it in a kiln with a high quality firing sheet.


elseif( **Faction is** < Indifferent) then


**You say:** `velium vapor`




**Frundle Frenkler says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

# Tilkzog Mournunder


## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `silk thread`




>**Tilkzog Mournunder says:** To create silk thread, combine 2 spiderling silk inside a tailoring kit.


**You say:** `hail`




>**Tilkzog Mournunder says:** Hail Soandso. I am Tilkzog Mournunder, Necromancer of the Dark Reflection. It is my duty here to assist not only the young necromancers of the Dark Reflection but also those wizards, magicians, and enchanters that have been called into the service of the Plague Bringer. I will aid you in obtaining an outfit of [durable clothing] suitable for a young sorcerer of the Dark Reflection. Once you have been adequately outfitted for venturing beyond our homeland in service of the Plague Bringer return to me and I will assist you in obtaining a [staff of dark reflections].


**You say:** `staff of dark reflections`




>**Tilkzog Mournunder says:** The Dark Reflection has many enemies even within our home of Ak'Anon and the surrounding Steamfont Mountains. Many fear and oppose the beliefs that grant us our vision and powers. A wizard of the Eldrich Collective by the name of Winex Kloktik has been aiding members of the Deep Muses hunt and slay those loyal to Bertoxxulous and the Dark Reflection. Seek Winex Kloktik and eliminate her. When you have completed this task bring me Winex's Staff.


**You say:** `durable clothing`




>**Tilkzog Mournunder says:** The sorcerous servants of Bertoxxulous, the Plague Bringer, are privileged with the sight of the Dark Reflection. This gift enlightens us to the powers of disease, decay, death, and destruction. Forces that are misunderstood and feared by the majority of Norrath, including our fellow gnomes of Ak'Anon. These forces are the catalyst of change, cleansing Norrath of the old and weak, and we are the agents of this catalyst. However, before you will be of much use to the Dark Reflection you must gather the [components] necessary for the outfit that will protect and aid you in your duties.


**You say:** `components`




>**Tilkzog Mournunder says:** You will need this Curing Kit and varying components depending on the piece of clothing you wish to fabricate. Do you desire to craft a [plague sorcerer cap], [plague sorcerer wristband], [plague sorcerer gloves], [plague sorcerer boots], [plague sorcerer sleeves], [plague sorcerer pantaloons], or [plague sorcerer robe]?



**You receive:**  [Curing Kit](/item/17125)


**You say:** `plague sorcerer boots`




>**Tilkzog Mournunder says:** To craft Plague Sorcerer Boots you require two [silk thread], two ebon drakeling bile, and two large rat pelts. Once you have the necessary components combine them in your Curing Kit with this Tattered Boot Pattern.



**You receive:**  [Tattered Boot Pattern](/item/19561)


**You say:** `plague sorcerer cap`




>**Tilkzog Mournunder says:** To craft a Plague Sorcerer Cap you will require two [silk thread], ebon drakeling bile, and a grikbar kobold scalp. Once you have the necessary components combine them in your Curing Kit with this Tattered Cap Pattern.



**You receive:**  [Tattered Cap Pattern](/item/19555)


**You say:** `plague sorcerer gloves`




>**Tilkzog Mournunder says:** To craft Plague Sorcerer Gloves you require two [silk thread], ebon drakeling bile, and two yellow recluse silks. Once you have the necessary components combine them in your Curing Kit with this Tattered Glove Pattern.



**You receive:**  [Tattered Glove Pattern](/item/19559)


**You say:** `plague sorcerer pantaloons`




>**Tilkzog Mournunder says:** To craft Plague Sorcerer Pantaloons you require two [silk thread], young ebon drake bile, and four yellow recluse silks. Once you have the necessary components combine them in your Curing Kit with this Tattered Pant Pattern.



**You receive:**  [Tattered Pant Pattern](/item/19560)


**You say:** `plague sorcerer robe`




>**Tilkzog Mournunder says:** To craft a Plague Sorcerer Robe you will require three [silk thread], ebon drake bile, a giant rat pelt, and two yellow recluse silks. Once you have the necessary components combine them in your Curing Kit with this Tattered Tunic Pattern.



**You receive:**  [Tattered Tunic Pattern](/item/19556)


**You say:** `plague sorcerer sleeves`




>**Tilkzog Mournunder says:** To craft Plague Sorcerer Sleeves you require two [silk thread], young ebon drake bile, and three yellow recluse silks. Once you have the necessary components combine them in your Curing Kit with this Tattered Sleeves Pattern.



**You receive:**  [Tattered Sleeve Pattern](/item/19557)


**You say:** `plague sorcerer wristband`




>**Tilkzog Mournunder says:** To craft a Plague Sorcerer Wristband you require a [silk thread], ebon drakeling bile, and a large rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Wristband Pattern.



**You receive:**  [Tattered Wristband Pattern](/item/19558)

end

## Turn-Ins

local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** [Winexs Staff](/item/10994)) then


>**Tilkzog Mournunder says:** It is good to know that one so zealously opposed to the Dark Reflection has been eliminated. Take this Rough Hewn Staff and when you have acquired a Harpies Eye and Pristine Ebon Drakeling Scales take the Staff, Eye, and Scales to Clockwork SmithXIII. The clockwork will put the finishing touches on your new staff.


* __Faction:__ [Dark Reflection](/faction/238) (10)


* __Faction:__ [Eldritch Collective](/faction/245) (-1)


* __Faction:__ [Gem Choppers](/faction/255) (-1)


* __Faction:__ [Deepmuses](/faction/240) (-1)


 **You receive:**  [Rough Dark Reflection Staff](/item/10999) (+100 exp)

**This NPC *should* return incorrect items given.**

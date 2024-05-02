# Reivaj the Battlerager
## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Reivaj the Battlerager says:** Greetings, Soandso. You tread in the halls of Iceshard manor. Are you here with a purpose or are you lost?


elseif **Faction** >= Indifferent then



>**Reivaj the Battlerager says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Reivaj the Battlerager says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `lost`



if **Faction** >= Amiable then



>**Reivaj the Battlerager says:** Turn around and go to your left through the hallways, then turn right and go straight.  That should lead you out of this fine manor


elseif **Faction** >= Indifferent then



>**Reivaj the Battlerager says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Reivaj the Battlerager says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `purpose`



if **Faction** >= Amiable then



>**Reivaj the Battlerager says:** I do not know what purpose you would serve to the Kromrif. If you seek to amass a fortune you have come to the wrong man. I am but a simple battlerager, wielding my blade for the Iceshard brothers when needed.


elseif **Faction** >= Indifferent then



>**Reivaj the Battlerager says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Reivaj the Battlerager says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `rallos zek`



if **Faction** >= Amiable then



>**Reivaj the Battlerager says:** The great war god guides my blade and has helped shape my day to day life... I feel as if there is something greater mapped out for my life than what I have here.


elseif **Faction** >= Indifferent then



>**Reivaj the Battlerager says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Reivaj the Battlerager says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `plan`



if **Faction** >= Amiable then



>**Reivaj the Battlerager says:** I have been planning to travel forth from Kael Drakkel and destroy any Coldain who have spread from their safe home in Thurgadin. It is always a nice trip, I will take several of the elder Kromrif with me as well. Perhaps we will track down the elusive wurm, Blizzent.


elseif **Faction** >= Indifferent then



>**Reivaj the Battlerager says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Reivaj the Battlerager says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `blizzent`



if **Faction** >= Amiable then



>**Reivaj the Battlerager says:** Blizzent is an ancient ice wurm Vorken speaks of occasionally. If I remember the story correctly, Blizzent once bit Vorken and Klaggen and has had a desire to have another taste. I have never seen the wurm myself. He may not even be alive still. If I were able to slay Blizzent and retrieve proof of it, I could probably get in good with master Vorken.


elseif **Faction** >= Indifferent then



>**Reivaj the Battlerager says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Reivaj the Battlerager says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `battle`



if **Faction** >= Amiable then



>**Reivaj the Battlerager says:** Yes, I am a warrior who thrives on battle.  I have great faith in Rallos Zek and I call upon his power to make me more efficient in battle.  I am not like the foolish berserkers.  They howl like animals and create strange totems.  They simply unleash their anger upon the world whereas I focus and destroy my foes with the aid of Rallos Zek.


elseif **Faction** >= Indifferent then



>**Reivaj the Battlerager says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Reivaj the Battlerager says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/25117" data-url="25117" class="tooltip-link link">Bllizents Fang</a>) then


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+25</span>)


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+6</span>)


Your faction standing with [Coldain](/faction/406) got worse (<span class='text-danger'>-12</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1171.png" alt="" /> <a
                                href="/item/25083" data-url="25083" class="tooltip-link link">Vehement Sword of Reivaj</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**

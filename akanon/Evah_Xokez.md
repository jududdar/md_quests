# Evah Xokez


## Dialog

**You say:** `hail`



if **Faction** >= Amiable then 



>**Evah Xokez says:** Be wary, Soandso, there are unseen powers within these mines that can destroy the strongest warriors or the wisest seers. Do you find the rust that corrodes the mechanisms around you and the decaying forms that wander [these tunnels pleasing]?


elseif( **Faction is** == Indifferent) then



>**Evah Xokez says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Evah Xokez says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `pleasing`



if **Faction** >= Indifferent then 



>**Evah Xokez says:** Then perhaps you share the vision of we who have made these mines our home. We are the Dark Reflection and our perceptions have been refined to allow us to see the poisons and disease coursing through every creature's veins and the decay afflicting all forms of matter in Norrath. I can teach you to harness the powers of our divine benefactor if you are [willing to learn] through service to the Dark Reflection.


else



**Evah Xokez says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `willing.* learn`



if **Faction** >= Indifferent then 



>**Evah Xokez says:** Then your first lesson shall be the fulfillment of spreading infection and disease. Some of the best carriers of infectious diseases are rodents. Take this vial containing a slow and painful infection and give it to one of the pregnant giant rodents that can be found outside in the Steamfont Mountains. This way you can spread the disease to not only those creatures which cross the mother's path but also to those who cross the paths of her future offspring. Bring me the empty vial when the task has been completed.



**You receive:**  [Vial of Infectious Disease](/item/10262)



else



**Evah Xokez says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `components`



if **Faction** >= Indifferent then 



>**Evah Xokez says:** The recipe we use to make the plague rat disease is fairly simple. We could easily extract the fluids from the infected rat livers but that would be counterproductive to our cause since it would require the deaths of our rodent carriers. Instead, I need you to collect two parts diseased bone marrow, one sprig of wormwood and one part gnomish spirits to be used as a medium. When you have combined all the components in the container I have provided, return it to me so that we may continue to spread the disease!


else



**Evah Xokez says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



if **You turn in:** [Stained Note](/item/18769)


>**Evah Xokez says:** Join us in fulfilling teh will of Bertoxxulous. You can train with us here, in the shadows of the Abbey. Wear this tunic to help conceal your true identity.


* __Faction:__ [Dark Reflection](/faction/238) (100)



* __Faction:__ [Eldritch Collective](/faction/245) (-10)



* __Faction:__ [Gem Choppers](/faction/255) (-10)


* __Faction:__ [Deepmuses](/faction/240) (-10)



 **You receive:**  [Tin Patched Tunic*](/item/13518) (+20 exp)


elseif **Faction** >= Indifferent and  **You turn in:** [Empty Infectious Vial](/item/10263)


>**Evah Xokez says:** I hope you enjoyed the thrill of your first lesson and the awakening of your vision. Now you must prove your utility to our society. Take this airtight container and gather the [components] for another dose of the plague rat disease.


* __Faction:__ [Dark Reflection](/faction/238) (50)



* __Faction:__ [Eldritch Collective](/faction/245) (-5)



* __Faction:__ [Gem Choppers](/faction/255) (-5)



* __Faction:__ [Deepmuses](/faction/240) (-5)



 **You receive:**  [Airtight Metal Box](/item/17357) (+150 exp)


elseif **Faction** >= Indifferent and  **You turn in:** [Container of Infectious Reagents](/item/10266)


>**Evah Xokez says:** It appears that you truly seek to expand your vision into the Dark Reflection, Soandso. I grant you the Initiate Symbol of Bertoxxulous!


* __Faction:__ [Dark Reflection](/faction/238) (25)



* __Faction:__ [Eldritch Collective](/faction/245) (-2)



* __Faction:__ [Gem Choppers](/faction/255) (-2)



* __Faction:__ [Deepmuses](/faction/240) (-2)



 **You receive:**  [Initiate Symbol of Bertoxxulous](/item/1390) (+200 exp)


**This NPC *should* return incorrect items given.**

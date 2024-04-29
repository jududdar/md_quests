# Ostorm



## Dialog

if **Faction** >= Indifferent then


**You say:** `hail`




>**Ostorm says:** I am Ostorm of the Temple of Solusek Ro, guardian of the sacred crystal of Kintaz.  Be wary and keep your distance, lest the proximity of the crystal [steal] your [memories].


**You say:** `steal`




>**Ostorm says:** It is the nature of the crystal of Kintaz to steal the memories of those around it. Only I am safe, and then only because of the strong wardings placed on me by Solusek Ro himself. Are you interested in [losing] any [memories]?


**You say:** `losing`




>**Ostorm says:** Recently, I have been experimenting with the crystal, and have found that those exposed to ruby light filtered through it tend to lose the memories of their most specialized arcane skills. Are you sure you want to [lose advanced memory] of specialization?


**You say:** `advanced`




>**Ostorm says:** Be warned that once exposed to the crystal, I can not reverse the effects. If you desire exposure, fetch me a ruby.


**You say:** `gold`




>**Ostorm says:** You do not remember?  You promised me fifty gold coins for allowing you to be exposed to the sacred crystal of Kintaz.


else


**Ostorm says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";



if **Faction** >= Indifferent and (e.other:GetClass() == 2 or e.other:GetClass() == 6 or e.other:GetClass() == 10 or e.other:GetClass() == 11 or e.other:GetClass() == 12 or e.other:GetClass() == 13 or e.other:GetClass() == 14) and  **You turn in:** [Ruby](/item/10035)) then


>**Ostorm says:** ..hear me? Ah, you seem to be coming out of your stupor. I think you have been exposed to the crystal long enough. By the time you leave the temple, your memories should have faded. Do you have the [fifty gold] coins that you owe me?


* __Faction:__ [Temple of Solusek Ro](/faction/415) (1)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


for skill=43,47,1 do



e.other:SetSkill(skill,49);



**Message:** <span class="text-warning">*Your specialize skills have all been set to 49.*</span>


 **You receive:** 0 (+1000 exp)

elseif( **You turn in:** gold = 50) then


>**Ostorm says:** Thank you.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (2)


* __Faction:__ [Shadowed Men](/faction/416) (-2)


e.other:Ding();


elseif **Faction** >= Indifferent and  **You turn in:** [Fire Opal](/item/10031), [Fire Opal](/item/10031), [Lambent Stone](/item/10000)) then


>**Ostorm says:** Here is your prize - a lambent fire opal.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (1)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Lambent Fire Opal](/item/10128) (+1000 exp)


elseif **Faction** >= Indifferent and  **You turn in:** [Enchanted Platinum Bar](/item/16507)) then


>**Ostorm says:** I see that Gavel has sent you to me.  Very well, I have magnetized your platinum bar - take it.


 **You receive:**  [Magnetized Platinum Bar](/item/19049) 

**This NPC *should* return incorrect items given.**







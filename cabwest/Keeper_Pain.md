# Keeper Pain
## Dialog

**You say:** `hail`



>*Keeper Pain raises his gaze from his tomes to greet you. 'Ahh!! Welcome, seeker of knowledge! Come to fill your brains, have you? Look closer, adventurer. I have scribed some very powerful spells.*

**You say:** `wand of pain`



if **Faction** >= Amiable then



>*Keeper Pain drops his tome and monocle and looks at you sharply. 'What?!! Have you seen Revenant Vytrix? I let him borrow my wand for a quest. That was half a season ago!! I fear he is dust and my precious wand is lost.*


elseif **Faction** >= Indifferent then



>**Keeper Pain says:** No Iksar resident will have anything to do with you!


else



>**Keeper Pain says:** No Iksar resident will have anything to do with you!   Away from here before you find yourself dead.

end

## Turn-Ins



if **Faction** >= Amiable and  **You turn in:** [Wand of Pain](/item/12869)) then


>*Keeper Pain begins jumping for joy. 'Yoohoo!! My wand!! Thank you. You must be some powerful adventurer. You can help me collect a few components. Fill this chest with a frost crystal, a cockatrice egg, a giant hornet egg and a plains pebble. Return the full chest to me and I shall offer you a spell I recently researched.*


* __Faction:__ [Brood of Kotiz](/faction/443) (5)




* __Faction:__ [Legion of Cabilis](/faction/441) (1)



 **You receive:**  [Component Chest](/item/17041) (+100 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Full Component Chest](/item/12885)) then


>**Keeper Pain says:** Yes this is exactly what I wanted. Here is your spell.


* __Faction:__ [Brood of Kotiz](/faction/443) (5)




* __Faction:__ [Legion of Cabilis](/faction/441) (1)



 **You receive:**  [Spell: Renew Bones](/item/15444) 


**This NPC *should* return incorrect items given.**

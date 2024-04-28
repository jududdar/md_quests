# Bukuku Wolffeetz
## Dialog

**You say:** `Hail`



>**Bukuku Wolffeetz says:** Har har har! Yu funy lukking. Oooo.. do u hav doze [smarty writin's]?

**You say:** `smarty writin`



>**Bukuku Wolffeetz says:** Me not know what dem ar for shure. Dem only hav dees names. Umm.. let me see if I can member dem. Taaalisman de umm.. Jasinth. Dat's one of dem. Spirited of Scaley?? OH!! Dis my favorite. Kripple. Den the last is the painful one. Canaabaalize canaabaalize canaabaalize. Yep, dat super duper one. Bring me bak one of dem, me trade.
end

## Turn-Ins



local count =  **You turn in:**  { [Spell: Cripple](/item/19269),  [Spell: Spirit of Scale](/item/19238),  [Spell: Talisman of Jasinth](/item/19264),  [Spell: Cannibalize III](/item/19272)}

if(count > 0) then


repeat



>**Bukuku Wolffeetz says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 **You receive:** eq.ChooseRandom( [Spell: Talisman of Shadoo](/item/19267), [Spell: Shroud of the Spirits](/item/19271), [Spell: Torrent of Poison](/item/19274), [Spell: Insidious Decay](/item/19266)) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**






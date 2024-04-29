# Xantis Ixtax
## Dialog

**You say:** `hail`



>**Xantis Ixtax says:** Greetings, disciple Soandso. Feel free to inspect my wares. I am here to serve all necromancers of the Dead. I can also enchant a [ring of the Dead] if you have one.

**You say:** `ring of the dead`



if **Faction** >= Kindly then



>**Xantis Ixtax says:** The ring of the Dead is the mark of loyal members of the his house. One can use it to bind his soul to any point, but only once and then the enchantment is gone. It is my duty to enchant the ring of the Dead once it is drained of all power, but only for a loyal member. I believe you to be loyal. I require the drained ring and ten gold coins.


elseif **Faction** >= Indifferent then



>**Xantis Ixtax says:** When you learn to serve the Dead, then I will find the time to speak of such things.


else



>**Xantis Ixtax says:** You dare to speak to me?

end

## Turn-Ins



local text = "Come now.. I said I require the ring of the Dead and 10 gold pieces.";



if **Faction** >= Kindly and  **You turn in:** [Ring of the Dead](/item/13394), gold = 10) then 


>**Xantis Ixtax says:** Here you are, disciple. I have enchanted your ring once more.


 **You receive:**  [Ring of the Dead](/item/13394) (+0 exp)

**This NPC *should* return incorrect items given.**







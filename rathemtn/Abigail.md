# Abigail
## Dialog

**You say:** `Hail`



>**Abigail says:** Greetings!  I am the holder of the secret of the [Breastplate of Ro].  You may rest here.  You are quite safe within this camp of paladins.


**You say:** `breastplate of ro`



if **Faction** >= Indifferent +50 then 



>**Abigail says:** The Breastplate of Ro mold will be awarded to you.  First, you will perform a test of strength.  Go to Faydwer.  There you shall seek out and destroy the Teir'Dal who carry the dark cauldrons!!  They have been venturing into our lands and capturing many Koada'Dal and Fier'Dal for cooking purposes!  Bring to me two of their dark cauldrons.


elseif **Faction** >= Indifferent then



>**Abigail says:** You need to prove your loyalty to my temple.  Go to Felwithe and seek out the Clerics of Tunare.  Prove to them your faith.  Then ask the leader of this church if you are a [honored member].


else



>**Abigail says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!

end

## Turn-Ins



local text = "I instructed you to return with no less than two dark pots.";


if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1017.png" alt="" /> <a
                                href="/item/12309" data-url="12309" class="tooltip-link link">A Dark Cauldron</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1017.png" alt="" /> <a
                                href="/item/12309" data-url="12309" class="tooltip-link link">A Dark Cauldron</a>) then 


>**Abigail says:** You have earned the mold.  You will now need go and speak with Thomas about [Lord Searfire].


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+20</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+20</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/12299" data-url="12299" class="tooltip-link link">Mold of Ro Breastplate</a> 

 

**This NPC *should* return incorrect items given.**







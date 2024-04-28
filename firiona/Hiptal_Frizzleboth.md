# Hiptal Frizzleboth
## Dialog

**You say:** `Hail`



>**Hiptal Frizzleboth says:** Bah!! It's not been a good day! Reports from the Outlands are even worse than I was led to believe. Many would-be adventurers have turned up missing of late. One of them was one of my messenger. He was out collecting some of the various new and [interesting scrolls] that have been surfacing in the farthest reaches of this land. I fear for his safety and that of the others searching for the lost travelers. I wish there was more I could do.

**You say:** `interesting scrolls`



>*Hiptal Frizzleboth reaches into his pouch. 'Well, let's see what I have in here. Ah, yes. The scrolls are definitely worth finding. Possibly even dangerous if they should fall into the wrong hands. But that is why the Collective sent me here. To procure all of the scrolls so that they may be studied at the Library of Mechanimagica. Bah!! But my messenger is missing! I can't fail them. Would you be willing to [help locate] some of the scrolls I am missing?*

**You say:** `help locate`



>**Hiptal Frizzleboth says:** You would do that for me? Of course you would, you realize how important my work is here. Your task is quite simple, really. I'll part with one of my rare scrolls if you bring me one of the common ones from the surrounding areas. To be more precise, I am looking for the scrolls Gift of Xev and Bristlebane's Bundle. Oh, my nephew is going to love these! I can't wait to get my hands on them! I'm also looking for the scrolls Quiver of Marr and Scars of Sigil. Bring them back to me as soon as you find one.
end

## Turn-Ins



local count =  **You turn in:**  { [Spell: Bristlebane\`s Bundle](/item/19351),  [Spell: Gift of Xev](/item/19347),  [Spell: Quiver of Marr](/item/19354),  [Spell: Scars of Sigil](/item/19358)}

if(count > 0) then


repeat



>**Hiptal Frizzleboth says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 **You receive:** eq.ChooseRandom( [Spell: Boon of Immolation](/item/19368), [Spell: Scintillation](/item/19346), [Spell: Vocarate: Fire](/item/19355), [Spell: Vocarate: Air](/item/19357)) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**






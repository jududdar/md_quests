# Semkak Prophet of Vallon
## Dialog

if( **Faction is** > Indifferent) then


**You say:** `hail`




>**Semkak Prophet of Vallon says:** You have entered the sacred temple of Vallon Zek. This is the Temple of Strategy. We teach what must be done to be a great leader. Forethought is a powerful tool.


**You say:** `teach`




>**Semkak Prophet of Vallon says:** I cannot teach one of your kind the arts of war at this time. I must teach the other Kromzek and Kromrif that proper strategy will allow us to win the war against the dragons. If you were to serve the temple of Vallon, I might consider giving you a few words of advice about strategy.


**You say:** `serve the temple`




>**Semkak Prophet of Vallon says:** The dragons of Velious are ancient and wise beyond belief. They have ageless strategies to destroy their foes. The Temple of Strategy must gain the knowledge they hold. I have heard rumors of a great dragon burial ground. If this tomb indeed exists, find it and seek out the knowledge of the dragons who are now dead. Bring whatever you believe will teach us their strategies and tactics of the past.


elseif( **Faction is** > Apprehensive) then


>**Semkak Prophet of Vallon says:** You need to prove your dedication to our cause before I can discuss such matters with you.

else


**Semkak Prophet of Vallon says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.
end

## Turn-Ins





if( **Faction is** > Indifferent and ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_683.png" alt="" /> <a
                                href="/item/24986" data-url="24986" class="tooltip-link link">Golden Tablet of Draconic Strategy</a> or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/24985" data-url="24985" class="tooltip-link link">Scroll of Scaled Tactics</a>)) then


>**Semkak Prophet of Vallon says:** This tablet holds great knowledge. The Temple of Strategy thanks you, Soandso. Take this and know that your own strategies are wise indeed if you have acquired this tablet from the depths of the dragons' graveyard.


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+20</span>)


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+5</span>)


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+5</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-10</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_521.png" alt="" /> <a
                                href="/item/25036" data-url="25036" class="tooltip-link link">Steel Wristband  of Strategy</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_676.png" alt="" /> <a
                                href="/item/25040" data-url="25040" class="tooltip-link link">Shield of Battle</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/25034" data-url="25034" class="tooltip-link link">Circlet of Vallon</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/25035" data-url="25035" class="tooltip-link link">Book of Strategy</a>) (+50000 exp)

 

**This NPC *should* return incorrect items given.**

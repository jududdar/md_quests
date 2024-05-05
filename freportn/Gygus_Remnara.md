# Gygus Remnara



[Gygus Remnara](/npc/8037) is a level 61 Human GM Paladin that spawns in [North Freeport](/zone/8).



## Dialog

**You say:** `hail`



>**Gygus Remnara says:** The Temple of Marr welcomes you. I am Gygus Remnara. High Sentinel for the Sentries of Passion. We are the order of paladins within the Priests of Marr and whose charge it is to protect the holy Temple of Marr.

**You say:** `heal`



>**Gygus Remnara says:** It is not my duty to see to the wounded. You must seek out Plur Etinu. He is in here somewhere.

**You say:** `honored member`



if **Faction** >= Indifferent +50 then



>**Gygus Remnara says:** Yes.  The light of righteousness shines from within you.


elseif **Faction** >= Indifferent then



>**Gygus Remnara says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Gygus Remnara says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.

end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18738" data-url="18738" class="tooltip-link link">A tattered note</a>) then 


>**Gygus Remnara says:** Welcome to the Sentries of Passion. We are the protectors of the Temple of Marr. Wear our tunic with pride, young knight! Find your wisdom within these walls and in the words of our priests. And remember to aid all who follow the twin deities, Mithaniel and Erollisi Marr.


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+100</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-10</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13556" data-url="13556" class="tooltip-link link">White and Blue Tunic*</a> (+20 exp)

 

**This NPC *should* return incorrect items given.**
;


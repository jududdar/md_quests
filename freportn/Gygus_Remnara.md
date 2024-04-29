# Gygus Remnara
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




if( **You turn in:** [A tattered note](/item/18738)) then 


>**Gygus Remnara says:** Welcome to the Sentries of Passion. We are the protectors of the Temple of Marr. Wear our tunic with pride, young knight! Find your wisdom within these walls and in the words of our priests. And remember to aid all who follow the twin deities, Mithaniel and Erollisi Marr.


* __Faction:__ [Priests of Marr](/faction/362) (100)


* __Faction:__ [The Freeport Militia](/faction/330) (-10)


* __Faction:__ [Knights of Truth](/faction/281) (15)


 **You receive:**  [White and Blue Tunic*](/item/13556) (+20 exp)

**This NPC *should* return incorrect items given.**
;


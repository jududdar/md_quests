# a skeleton
## Dialog

**You say:** `hail`



>**a skeleton says:** Here I stand high and above, a minstrel supreme, my words offer love. Love between all, troll and ogre alike. I sing to all, except Tabaz, so take a hike!

**You say:** `back to the closet`



if **Faction** >= Amiable +100 then 




>**a skeleton says:** Back to the closet?! Not until I can get an instrument. You get me... hmm, I know. Get me a lizardman scout fife. Not just one, but four. Then my friends can also play along with me. Do this and I promise you I shall return.


elseif **Faction** >= Indifferent then



>**a skeleton says:** You're going to have to prove yourself a stronger aid to my masters, the Darkones.


else



>**a skeleton says:** I would like to assist you, but my masters say you are no friend of the Darkones and would rather see you dead.


end

## Turn-Ins



local text = "I want FOUR lizardman scout fifes.";



if **Faction** >= Amiable +100 and  **You turn in:** [Lizardman Scout Fife](/item/12198), [Lizardman Scout Fife](/item/12198), [Lizardman Scout Fife](/item/12198), [Lizardman Scout Fife](/item/12198)


>**a skeleton says:** All right! I was kinda hoping the lizards would finish you off and I could stay free, but a deal is a deal. Let's go.


 **You receive:**  [The Minstrel](/item/12216) (+25 exp)


**a skeleton despawns.**

**This NPC *should* return incorrect items given.**

end
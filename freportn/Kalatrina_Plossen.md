# Kalatrina Plossen



[Kalatrina Plossen](/npc/8076) is a level 61 Human GM Paladin that spawns in [North Freeport](/zone/8).



## Dialog

local fac = e.other:GetFaction(e.self);



**You say:** `hail`



>**Kalatrina Plossen says:** Hail!  Welcome to the Hall of Truth.  We, the Knights of Truth, are all the hope this city has of loosening the grip of Lucan D'lere and his militia.  I seek a young knight to [serve the will of the Truthbringer].

**You say:** `what.* truthbringer`



>**Kalatrina Plossen says:** Shame on you.  To set foot into the Hall of Truth and not know for whom it was built.  Still, it is never too late to see the light.  Mithaniel Marr is our deity.  He is the Truthbringer.  By living our lives in valor and crushing all those who suppress His beliefs. We serve Him.

**You say:** `who.* lucan`



>**Kalatrina Plossen says:** He is the self-proclaimed ruler of Freeport.  He began this false rule by banding together every vagabond and brawler he could find into a militia of sorts.  By protecting the city from orc raids and the frequent scuffles between travelers, he gained the city's trust and wrested control of it from the former ruler.  All this took place during the Hall's Crusade of Tears.  We returned to find our remaining forces murdered.  The militia claimed the orcs infiltrated the city and killed our knights.  How convenient that they killed no militia!  Join us in crushing the defiler!

**You say:** `serve.* truthbringer`



if **Faction** >= Amiable then



>**Kalatrina Plossen says:** Stand tall then, knight! We have need of your services. We have sent a man to infiltrate the militia. We fear he may soon be found out. Take him this note of warning. Say the words, 'Truth is good,' and you shall find him. Be careful, young knight. The militia does not take prisoners.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18817" data-url="18817" class="tooltip-link link">A Sealed Letter</a>


elseif **Faction** >= Indifferent then



>**Kalatrina Plossen says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Kalatrina Plossen says:** Leave my presence at once.  Your ways of life are not acceptable to one who follows the Truthbringer.


**You say:** `zimel.* blades`



if **Faction** >= Amiable then



>**Kalatrina Plossen says:** Why would Lucan visit a condemned building? He must be searching for something. When I last visited the local forge, I heard rumors of Lucan searching for a sword named Soulfire. If this is true, you must find it first! No more power should go his way. Seek this sword out!


elseif **Faction** >= Indifferent then



>**Kalatrina Plossen says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Kalatrina Plossen says:** Leave my presence at once.  Your ways of life are not acceptable to one who follows the Truthbringer.

end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18818" data-url="18818" class="tooltip-link link">A tattered flier</a>) then 


>**Kalatrina Plossen says:** Zimel's Blades?! Hmmmmm. It doesn't ring a bell and the remainder of the writing is too hard to make out. It kind of looks like a list of prices. You know, down at the Office of the People they might be able to tell us if this place exists. Go speak with Rashinda. She knows all about Freeport. If [Zimel's Blades] existed, you must report back to me what happened to it.


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+1</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+5000 exp)

 

**This NPC *should* return incorrect items given.**

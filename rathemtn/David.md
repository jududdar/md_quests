# David
## Dialog

**You say:** `hail`



>**David says:** I, the keeper of the [Bracers of Ro],  welcome you.  Come and rest within our camp.  You have nothing to fear while such righteous might is gathered.

**You say:** `bracers of ro`



if **Faction** >= Indifferent +50 then



>**David says:** When you can swim the waters of Rathe and return two goblin nets from the elusive goblin net masters. then you will be rewarded the bracer mold.


elseif **Faction** >= Indifferent then



>**David says:** You and I are not one yet.   Go to Erudin and serve the Deepwater Knights.  When you can ask Lord Weligon if you are an [honored member] and he answers yes, then this is when we are one with Prexus.




else



>**David says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.

end


## Turn-Ins



local text = "Two Deepwater goblin nets are required.";



if **Faction** >= Indifferent +50 and  **You turn in:** [Deepwater Goblin Net](/item/12311), [Deepwater Goblin Net](/item/12311)


>**David says:** You have done well. Take the mold for the bracer.  Go forth to speak with Thomas of [Lord Searfire].  Then all components shall be known.


* __Faction:__ [Deepwater Knights](/faction/242) (20)


* __Faction:__ [High Council of Erudin](/faction/266) (3)



* __Faction:__ [Heretics](/faction/265) (-3)


 **You receive:** None 

**This NPC *should* return incorrect items given.**

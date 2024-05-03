# Drill Master Vygan


## Dialog

**You say:** `hail`



>**Drill Master Vygan says:** I am a Drill Master of the Legion of Cabilis.  I have no time for idle chitchat.  Be off if you were not summoned to this fortress!  Find that guild which was chosen for you as an egg.

**You say:** `militia pike`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** The pike is the prime weapon of Cabilis warriors. It can be upgraded, too, such as from the partisan pike to the militia pike and beyond. All these pikes may be slung on one's back when your hands are needed for other pursuits. To upgrade a pike is something that is learned, but it can never be performed without a [geozite tool]. Do you [desire to upgrade the partisan pike]?


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `upgrade the partisan pike`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** It seems as though a traitor is among our people. Someone has smuggled shackle keys to the slaves. The froglok slaves have been escaping into the swamplands and there we can hear the whistle of their contact who escorts them to freedom. We must put a stop to this! I desire three things. Your partisan pike, the head of the Iksar traitor and the whistle of the escort. Bring these to me and I shall give you the militia pike.


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `what geozite tool`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** The Geozite Tool is used to sharpen the pikes of the Legion of Cabilis. Only it can produce the serrated edges necessary for these deadly weapons. They are not handed out to just any broodling. The tool is only given to warriors who serve the legion. Do you [want a geozite tool]?


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `want a geozite tool`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** Then take this satchel and go to the outer walls of Cabilis and seek out large scorpions. When you can fill and combine the satchel with scorpion pincers, then you shall prove to me that you are truly a warrior and I shall send you off on your true test.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/17993" data-url="17993" class="tooltip-link link">Pincer Satchel</a>


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `true warrior of the legion`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** If you are you will have proof; else you will have the wrath of the Legion upon you for such a claim.


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `partisan of cabilis`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** Bah! You are but a broodling!  Report to the other Drill Masters and pray that they can help you overcome your incompetence.


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.

end



## Turn-Ins



local text1 = "You shall wield no militia pike until I have the head of the traitor, the fife of the escort and the partisan pike.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18203" data-url="18203" class="tooltip-link link">Guild Summons</a>) then 


>**Drill Master Vygan says:** I see they have begun to draft younger broodlings? Hmmph!! No matter. We Drill Masters shall make a warrior of you. Here is your partisan's pike and some coin as your wages. Be sure that you begin your training in blacksmithing and report to the other Drill Masters for any tasks they may have for you. Let them know you are [a partisan of Cabilis]. Perhaps soon you shall be rewarded the [militia pike].


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+100</span>)



Your faction standing with [Cabilis Residents](/faction/440) got better (<span class='text-success'>+25</span>)



Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+25</span>)



Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+25</span>)




Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+25</span>)







 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/5130" data-url="5130" class="tooltip-link link">Partisan's Pike</a> (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-2 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 


elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_751.png" alt="" /> <a
                                href="/item/12675" data-url="12675" class="tooltip-link link">Froglok Escort Fife</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1208.png" alt="" /> <a
                                href="/item/12677" data-url="12677" class="tooltip-link link">An Iksar Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/5130" data-url="5130" class="tooltip-link link">Partisan's Pike</a>) then


>**Drill Master Vygan says:** You have perfomed just as expected. I bestow upon you the rank of militiaman. Here is your new pike. Past this, you shall require the [geozite tool] to upgrade your future pikes and mancatchers. We see much promise in you, militiaman. Go forth to serve the realm.


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+10</span>)



Your faction standing with [Cabilis Residents](/faction/440) got better (<span class='text-success'>+2</span>)



Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+2</span>)



Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+2</span>)




Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+2</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/5131" data-url="5131" class="tooltip-link link">Militia's Pike</a> (+200 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/12658" data-url="12658" class="tooltip-link link">Full Pincer Satchel</a>) then


>**Drill Master Vygan says:** You are a true warrior of Cabilis. You obviously are aware that in order to upgrade your pike you shall need a [geozite tool]. Take this note to the Lord of the outer gates. He desires a young warrior for a small task. Do this and he is instructed to reward you with the tool.


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+5</span>)



Your faction standing with [Cabilis Residents](/faction/440) got better (<span class='text-success'>+1</span>)



Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+1</span>)



Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+1</span>)




Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18213" data-url="18213" class="tooltip-link link">Note to Iksar Lord</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18211" data-url="18211" class="tooltip-link link">Note to Iksar Lord</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18210" data-url="18210" class="tooltip-link link">Note to Iksar Lord</a>) (+200 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-3 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**






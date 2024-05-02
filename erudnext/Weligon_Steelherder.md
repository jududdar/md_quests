# Weligon Steelherder
## Dialog

**You say:** `hail`



>**Weligon Steelherder says:** Hail, Soandso! This is the Deepwater Temple. Here you shall find the wisdom and courage of Prexus, the Ocean Lord. I am glad to see you have an interest. Forgive me if I cut our conversation short, but I have many [Deepwater tasks] to complete.

**You say:** `deepwater task`



if **Faction** >= Amiable +100 then



>**Weligon Steelherder says:** We here at the Deepwater Temple must tend to the [Peacekeeper battlestaff] and the [Deepwater harpoon] as well as other duties such as [ocean protection]. There is always something we must do.


elseif **Faction** >= Indifferent then



>**Weligon Steelherder says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Weligon Steelherder says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.





**You say:** `peacekeeper.* staff`



if **Faction** >= Amiable then



>**Weligon Steelherder says:** Every sentinel in Erudin carries a High Guard battlestaff.  The creation of these weapons is the duty of the Deepwater Temple and the Temple of Divine Light.  Our portion of the task is to send young members to [collect the Pearls of Odus].  These are imbedded into the staff and used to store mystical power.


elseif **Faction** >= Indifferent then



>**Weligon Steelherder says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Weligon Steelherder says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.





**You say:** `prove allegiance.* erudin`



if **Faction** >= Amiable +250 then



>**Weligon Steelherder says:** Yes, you are ready. We have heard rumors of a great bridge which will connect Antonica with Odus!! This must not happen! We must shield ourselves from the savage and evil ways of the other races. They say that a list exists. A list of three grand architects who wish to see this bridge erected. You will venture to Qeynos and find the list, then exterminate these three men. Return the list along with their heads and the Deepwater Harpoon is yours. Go!!


elseif **Faction** >= Indifferent then



>**Weligon Steelherder says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Weligon Steelherder says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.





**You say:** `ocean protection`



if **Faction** >= Amiable +50 then



>**Weligon Steelherder says:** In the name of Prexus, we are sworn to protect all ocean creatures.  We have heard reports of a shark carrying a deadly malady.  We believe she is pregnant.  If she delivers her young to the ocean, it will endanger all other creatures.  We need to find a young paladin to [hunt the diseased shark].


elseif **Faction** >= Indifferent then



>**Weligon Steelherder says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Weligon Steelherder says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.





**You say:** `hunt.* diseased shark`



if **Faction** >= Amiable +50 then



>**Weligon Steelherder says:** Ah, yes!  Take this bag with you.  When you have collected the remains of the diseased shark and no fewer than three of her young in it, combine them in it and return it to me.  Then, you shall get your reward.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17938" data-url="17938" class="tooltip-link link">Empty Shark Bag</a>


elseif **Faction** >= Indifferent then



>**Weligon Steelherder says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Weligon Steelherder says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.





**You say:** `collect.* pearls.* odus`



if **Faction** >= Amiable then



>**Weligon Steelherder says:** Then venture to the harbor of Erudin. There, you shall dive into the shark-infested water and search for the Pearls of Odus. They lie upon the grounds of our waters.  Fill the bag I have given you, combine it, and return it to me.  Good luck.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17939" data-url="17939" class="tooltip-link link">Empty Bag</a>




  






elseif **Faction** >= Indifferent then



>**Weligon Steelherder says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Weligon Steelherder says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.





**You say:** `honored member`



if **Faction** >= Indifferent +50 then



>**Weligon Steelherder says:** Yes.  The light of righteousness shines from within you.


elseif **Faction** >= Indifferent then



>**Weligon Steelherder says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Weligon Steelherder says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.



**You say:** `harpoon no more`



>**Weligon Steelherder says:** The Deepwater harpoon's distribution has been restricted by order of the High Council. The last one awarded was to an outsider, the brave and noble paladin, Sentry Xyrin. She hailed from the Temple of Marr.

**You say:** `deepwater harpoon`



>**Weligon Steelherder says:** We do not award the Deepwater harpoon to just any paladin. Nobility is all well and good, but you must still prove yourself.  We have heard rumors of a very distressing matter.  Perhaps it is your calling.  Are you ready to [prove allegiance to Erudin] and earn the Deepwater harpoon?
end

## Turn-Ins



local text1 = "I called for the list of engineers and all three of their heads!";


if **Faction** >= Amiable +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/13876" data-url="13876" class="tooltip-link link">Bag of Shark Remains</a>) then 


>**Weligon Steelherder says:** Very good, my dear young follower of Prexus. You will learn that swimming is a strong skill among the Deepwater Knights. Keep this up and you may wield a Deepwater harpoon soon enough. For now, you shall wear this barnacle breastplate. It is strong enough to aid a young knight in his quest for perfection.





Your faction standing with [Deepwater Knights](/faction/242) got better (<span class='text-success'>+20</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+3</span>)



Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/12194" data-url="12194" class="tooltip-link link">Barnacle Breastplate</a> (+2500 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/13879" data-url="13879" class="tooltip-link link">Full Bag of Pearls</a>) then 


>**Weligon Steelherder says:** Fine work, Deepwater Knight. You have proven yourself an excellent addition to our ranks. These shall be used to create more Peacekeeper staffs. Oh yes, I almost forgot your reward. Here you are. Now, go, and serve Prexus.





Your faction standing with [Deepwater Knights](/faction/242) got better (<span class='text-success'>+5</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+1</span>)



Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2104" data-url="2104" class="tooltip-link link">Patchwork Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2106" data-url="2106" class="tooltip-link link">Patchwork Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2108" data-url="2108" class="tooltip-link link">Patchwork Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2111" data-url="2111" class="tooltip-link link">Patchwork Pants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2112" data-url="2112" class="tooltip-link link">Patchwork Boots</a>) (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1 <img src='/static/icons/item_645.png' width='14' height='14'/> 3 <img src='/static/icons/item_646.png' width='14' height='14'/> 9 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable +250 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18835" data-url="18835" class="tooltip-link link">A Sealed List</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/13838" data-url="13838" class="tooltip-link link">Human Decapitated Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/13839" data-url="13839" class="tooltip-link link">Dwarf Decapitated Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_994.png" alt="" /> <a
                                href="/item/13840" data-url="13840" class="tooltip-link link">Gnome Decapitated Head</a>) then 


>**Weligon Steelherder says:** It is done!! I pray to Prexus that the knowledge of the bridge's design has departed from this world with the passing of these intelligent men. A pity they had to die. As for you, the other states may not tolerate your presence any longer, but you have proven that allegiance to Erudin is paramount among all Erudites. I am afraid the [harpoon is no more]!! I bestow upon you Deep Six, my personal cutlass!! May you wield it in the name of Erudin.





Your faction standing with [Deepwater Knights](/faction/242) got better (<span class='text-success'>+25</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+3</span>)



Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5377" data-url="5377" class="tooltip-link link">Deep Six Cutlass</a> (+100 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18725" data-url="18725" class="tooltip-link link">A tattered note</a>) then 


>**Weligon Steelherder says:** Greetings and welcome to the Deepwater Knights. Here is your guild tunic. Wear it with pride, and Prexus will keep a watchful eye on you. Go find sister Laoni, she will help you get started with your studies.


Your faction standing with [Deepwater Knights](/faction/242) got better (<span class='text-success'>+100</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+15</span>)



Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13544" data-url="13544" class="tooltip-link link">Old Blue Tunic*</a> (+20 exp)

 

**This NPC *should* return incorrect items given.**
;


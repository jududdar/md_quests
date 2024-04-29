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



**You receive:**  [Empty Shark Bag](/item/17938)


elseif **Faction** >= Indifferent then



>**Weligon Steelherder says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Weligon Steelherder says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.





**You say:** `collect.* pearls.* odus`



if **Faction** >= Amiable then



>**Weligon Steelherder says:** Then venture to the harbor of Erudin. There, you shall dive into the shark-infested water and search for the Pearls of Odus. They lie upon the grounds of our waters.  Fill the bag I have given you, combine it, and return it to me.  Good luck.



**You receive:**  [Empty Bag](/item/17939)




  






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


if **Faction** >= Amiable +50 and  **You turn in:** [Bag of Shark Remains](/item/13876)) then 


>**Weligon Steelherder says:** Very good, my dear young follower of Prexus. You will learn that swimming is a strong skill among the Deepwater Knights. Keep this up and you may wield a Deepwater harpoon soon enough. For now, you shall wear this barnacle breastplate. It is strong enough to aid a young knight in his quest for perfection.





* __Faction:__ [Deepwater Knights](/faction/242) (20)


* __Faction:__ [High Council of Erudin](/faction/266) (3)



* __Faction:__ [Heretics](/faction/265) (-3)


 **You receive:**  [Barnacle Breastplate](/item/12194) (+2500 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Full Bag of Pearls](/item/13879)) then 


>**Weligon Steelherder says:** Fine work, Deepwater Knight. You have proven yourself an excellent addition to our ranks. These shall be used to create more Peacekeeper staffs. Oh yes, I almost forgot your reward. Here you are. Now, go, and serve Prexus.





* __Faction:__ [Deepwater Knights](/faction/242) (5)


* __Faction:__ [High Council of Erudin](/faction/266) (1)



* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:** eq.ChooseRandom( [Patchwork Tunic](/item/2104), [Patchwork Cloak](/item/2106), [Patchwork Sleeves](/item/2108), [Patchwork Pants](/item/2111), [Patchwork Boots](/item/2112)) (+1000 exp)

elseif **Faction** >= Amiable +250 and  **You turn in:** [A Sealed List](/item/18835), [Human Decapitated Head](/item/13838), [Dwarf Decapitated Head](/item/13839), [Gnome Decapitated Head](/item/13840)) then 


>**Weligon Steelherder says:** It is done!! I pray to Prexus that the knowledge of the bridge's design has departed from this world with the passing of these intelligent men. A pity they had to die. As for you, the other states may not tolerate your presence any longer, but you have proven that allegiance to Erudin is paramount among all Erudites. I am afraid the [harpoon is no more]!! I bestow upon you Deep Six, my personal cutlass!! May you wield it in the name of Erudin.





* __Faction:__ [Deepwater Knights](/faction/242) (25)


* __Faction:__ [High Council of Erudin](/faction/266) (3)



* __Faction:__ [Heretics](/faction/265) (-3)


 **You receive:**  [Deep Six Cutlass](/item/5377) (+100 exp)

elseif( **You turn in:** [A tattered note](/item/18725)) then 


>**Weligon Steelherder says:** Greetings and welcome to the Deepwater Knights. Here is your guild tunic. Wear it with pride, and Prexus will keep a watchful eye on you. Go find sister Laoni, she will help you get started with your studies.


* __Faction:__ [Deepwater Knights](/faction/242) (100)


* __Faction:__ [High Council of Erudin](/faction/266) (15)



* __Faction:__ [Heretics](/faction/265) (-15)


 **You receive:**  [Old Blue Tunic*](/item/13544) (+20 exp)

**This NPC *should* return incorrect items given.**
;


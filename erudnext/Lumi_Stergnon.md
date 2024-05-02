# Lumi Stergnon
## Dialog

**You say:** `hail`



>**Lumi Stergnon says:** Peace and tranquility be with you. Soandso.  Are you a [new acolyte of peace] or are you [here to pay homage] to the child of tranquility?

**You say:** `new acolyte of peace`



if **Faction** >= Amiable then 




**You say:** `new acolyte of peace`





>**Lumi Stergnon says:** Then you shall learn the ways of Quellious and learn to do as you are told by higher ranking members. It is time for you to do the lesser duties of a young priest. Which will it be? [Retrieve the Peacekeeper staffs] or [battle the undead]?



**You say:** `retrieve the Peacekeeper staffs`





>**Lumi Stergnon says:** Then take this note to the woodworker in Toxxulia Forest. His name is Emil Parsini. He shall have the staff to be returned to the temple.




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18833" data-url="18833" class="tooltip-link link">a sealed letter</a>



**You say:** `battle the undead`





>**Lumi Stergnon says:** Then you shall venture to Toxxulia Forest. There has been an increase in skeleton sightings lately. I do not know their origin, but I believe that your efforts will reduce their numbers! Take this box. Return it to me when you have filled it with the bones of these undead creatures and combined it. May Quellious' light guide you.




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17941" data-url="17941" class="tooltip-link link">Box For Bones</a>




**You say:** `important missions`





>**Lumi Stergnon says:** We have need of skilled priests. We have learned that a High Guard battle staff has been stolen. We require a priest to [track down the staff].



**You say:** `track down the staff`





>**Lumi Stergnon says:** In the mountain keep called High Hold, we have heard there is a person hiring mercenaries for an attempt to obtain a High Guard battle staff. We are missing one of our staffs and believe this person has it. Go to Highpass Hold and find this person. Return the High Guard battle staff to me!








elseif **Faction** >= Indifferent then



>**Lumi Stergnon says:** You have not done much to upset the Peacekeepers of this temple, but we must ask you to prove yourself to us before we may discuss things such as this.


else



>**Lumi Stergnon says:** Leave my sight at once! You are no friend to the Peacekeepers of the Temple of Divine Light.


**You say:** `here to pay homage`




>**Lumi Stergnon says:** Then respect our temple and keep your prayers silent.
end





## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/13882" data-url="13882" class="tooltip-link link">A Box of Bones</a>) then 


>**Lumi Stergnon says:** This is fabulous work, my friend! You have served your people well. Take this as a gift. I hope it can be of use to you. We need proof of these skeletons' origins. Continue the eradication of the undead and find out who creates them. Once you know, bring their head to me.





Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+10</span>)
  


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+2</span>)
  


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-2</span>)





 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/17005" data-url="17005" class="tooltip-link link">Backpack</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_561.png" alt="" /> <a
                                href="/item/17002" data-url="17002" class="tooltip-link link">Belt Pouch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/10018" data-url="10018" class="tooltip-link link">Hematite</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2144" data-url="2144" class="tooltip-link link">Raw-hide Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/2145" data-url="2145" class="tooltip-link link">Raw-hide Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2146" data-url="2146" class="tooltip-link link">Raw-hide Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/6011" data-url="6011" class="tooltip-link link">Rusty Mace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6016" data-url="6016" class="tooltip-link link">Rusty Morning Star</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15203" data-url="15203" class="tooltip-link link">Spell: Cure Poison</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15207" data-url="15207" class="tooltip-link link">Spell: Divine Aura</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15201" data-url="15201" class="tooltip-link link">Spell: Flash of Light</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15208" data-url="15208" class="tooltip-link link">Spell: Lull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15209" data-url="15209" class="tooltip-link link">Spell: Spook the Dead</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15014" data-url="15014" class="tooltip-link link">Spell: Strike</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15205" data-url="15205" class="tooltip-link link">Spell: True North</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15210" data-url="15210" class="tooltip-link link">Spell: Yaulp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/6012" data-url="6012" class="tooltip-link link">Worn Great Staff</a>) (+2500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/13816" data-url="13816" class="tooltip-link link">Peacekeeper Staff</a>) then 


>**Lumi Stergnon says:** You have done well, neophyte.Let me add the touch of harmony to finish the job.. Here, then. Take these supplies. I am sure you'll need them. Soon you may be able to assist us in [important missions].





Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+10</span>)
  


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+2</span>)
  


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-2</span>)
  


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/17005" data-url="17005" class="tooltip-link link">Backpack</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_561.png" alt="" /> <a
                                href="/item/17002" data-url="17002" class="tooltip-link link">Belt Pouch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/10018" data-url="10018" class="tooltip-link link">Hematite</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2144" data-url="2144" class="tooltip-link link">Raw-hide Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/2145" data-url="2145" class="tooltip-link link">Raw-hide Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2146" data-url="2146" class="tooltip-link link">Raw-hide Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/6011" data-url="6011" class="tooltip-link link">Rusty Mace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6016" data-url="6016" class="tooltip-link link">Rusty Morning Star</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/6012" data-url="6012" class="tooltip-link link">Worn Great Staff</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/2109" data-url="2109" class="tooltip-link link">Tattered Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/2101" data-url="2101" class="tooltip-link link">Tattered Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2106" data-url="2106" class="tooltip-link link">Patchwork Cloak</a>) (+2500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;


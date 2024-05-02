# Brugga
## Dialog

if(e.language == 19 and e.other:GetLanguageSkill(19) >= 100) then


if( **Faction is** > Indifferent) then



**You say:** `Hail`





e.self:Say("Ragh!' His eyes you with pure hatred. 'Indigo, my dark bowels. . . treachery it is, treachery against the clan. Gharol paid! Paid for it!' He shows you his hands and grins maliciously. 'Paid, he did!",19);



**You say:** `rare disease`





>*Brugga snorts 'You have someone that needs killing, or someone that needs saving? It not matter to Brugga, but you smell of a hero, so Brugga think there someone need saving. Well Brugga have time, so you give Brugga the disease and Brugga see.*




else



e.self:Say("I wont deal with one such as you...",19);


else


 >*Brugga 'does not appear to understand you.'*
end

## Turn-Ins





if( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1134.png" alt="" /> <a
                                href="/item/29302" data-url="29302" class="tooltip-link link">Purified Bubonian Bile</a>) then


>*Brugga dips his finger into the flask and tastes the liquid, 'Hmm, someone start work on this already and it still vile. This nothing that Brugga have trouble to cure, we just need stronger toxins to drive this one back. Brugga need a gnome made crawlerpoison, a venom sack from the Terror Matriarch, and the stinger from a Nettling Wraith, Brugga make you a cure.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1134.png" alt="" /> <a
                                href="/item/29302" data-url="29302" class="tooltip-link link">Purified Bubonian Bile</a> 

 

elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/29297" data-url="29297" class="tooltip-link link">Mechanical Clockwork Venom</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_818.png" alt="" /> <a
                                href="/item/29298" data-url="29298" class="tooltip-link link">Terror Matriarch Venom Sack</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_907.png" alt="" /> <a
                                href="/item/29299" data-url="29299" class="tooltip-link link">Nettling Wraith Stinger</a>) then


e.self:Say("Yes, Brugga work with this.' Brugga chants and makes strange gestures while mixing the objects in his mortar and pestle. 'Ok, Brugga finished now. You have your cure, give cure with the bile and that will heal. You go now, Brugga done talking.",19);





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_808.png" alt="" /> <a
                                href="/item/29295" data-url="29295" class="tooltip-link link">Vial of Opaque Fluid</a> (+100000 exp)

 

**This NPC *should* return incorrect items given.**

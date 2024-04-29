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





if( **Faction is** > Indifferent and  **You turn in:** [Purified Bubonian Bile](/item/29302)) then


>*Brugga dips his finger into the flask and tastes the liquid, 'Hmm, someone start work on this already and it still vile. This nothing that Brugga have trouble to cure, we just need stronger toxins to drive this one back. Brugga need a gnome made crawlerpoison, a venom sack from the Terror Matriarch, and the stinger from a Nettling Wraith, Brugga make you a cure.*


 **You receive:**  [Purified Bubonian Bile](/item/29302) 

elseif( **Faction is** > Indifferent and  **You turn in:** [Mechanical Clockwork Venom](/item/29297), [Terror Matriarch Venom Sack](/item/29298), [Nettling Wraith Stinger](/item/29299)) then


e.self:Say("Yes, Brugga work with this.' Brugga chants and makes strange gestures while mixing the objects in his mortar and pestle. 'Ok, Brugga finished now. You have your cure, give cure with the bile and that will heal. You go now, Brugga done talking.",19);





 **You receive:**  [Vial of Opaque Fluid](/item/29295) (+100000 exp)

**This NPC *should* return incorrect items given.**

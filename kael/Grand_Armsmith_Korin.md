# Grand Armsmith Korin
## Dialog

**You say:** `hail`



if **Faction** >= Kindly then



>**Grand Armsmith Korin says:** What do you want from me " .. e.other:Race() .. "? I can only imagine that you are here to ask me to use my obviously superior smithing talents to create some [special helmets] to help protect your obviously frail body.


elseif **Faction** >= Indifferent then



>**Grand Armsmith Korin says:** You are still young to the true armies of Rallos, Soandso, come back after you have served us more.




else



>**Grand Armsmith Korin says:** Go back to the dog pit where you belong, " .. e.other:Race() .. ", you are not welcome here.


**You say:** `special helmet`



if **Faction** >= Kindly then



>**Grand Armsmith Korin says:** Just as I suspected " .. e.other:Race() .. ". Using my superior skills I can customize a plate helmet to help better protect you. Give me your Malevolent Crown, Warlord's Crown, Shining Helm, Templar's Crown, Troubadour's Helm, Frostreaver's Velium Crown, Crown of the Kromzek Kings or a Cowl of Mortality and I shall make you a new helm that will better protect you.


elseif **Faction** >= Indifferent then



>**Grand Armsmith Korin says:** You are still young to the true armies of Rallos, Soandso, come back after you have served us more.




else



>**Grand Armsmith Korin says:** Go back to the dog pit where you belong, " .. e.other:Race() .. ", you are not welcome here.

end

## Turn-Ins





if( **Faction is** > Amiable) then


if **You turn in:** [Malevolent Crown](/item/25349)



>**Grand Armsmith Korin says:** Ah, here is your helm, Soandso, may it serve you as well as you have served us.



 **You receive:**  [Custom Malevolent Crown](/item/31520) 


elseif **You turn in:** [Warlord's Crown](/item/25433)



>**Grand Armsmith Korin says:** Ah, here is your helm, Soandso, may it serve you as well as you have served us.



 **You receive:**  [Custom Warlord's Crown](/item/31524) 


elseif **You turn in:** [Shining Helm](/item/25370)



>**Grand Armsmith Korin says:** Ah, here is your helm, Soandso, may it serve you as well as you have served us.



 **You receive:**  [Custom Shining Helm](/item/31521) 


elseif **You turn in:** [Templar's Crown](/item/25391)



>**Grand Armsmith Korin says:** Ah, here is your helm, Soandso, may it serve you as well as you have served us.



 **You receive:**  [Custom Templar's Crown](/item/31523) 


elseif **You turn in:** [Troubadour's Helm](/item/25384)



>**Grand Armsmith Korin says:** Ah, here is your helm, Soandso, may it serve you as well as you have served us.



 **You receive:**  [Custom Troubadour's Helm](/item/31522) 


elseif **You turn in:** [Frostreaver's Velium Crown](/item/30507)



>**Grand Armsmith Korin says:** Ah, here is your helm, Soandso, may it serve you as well as you have served us.



 **You receive:**  [Custom Frostreavers Velium Crown](/item/2610) 


elseif **You turn in:** [Crown of the Kromzek Kings](/item/25194)



>**Grand Armsmith Korin says:** Ah, here is your helm, Soandso, may it serve you as well as you have served us.



 **You receive:**  [Custom Crown of the Kromzek Kings](/item/2611) 


elseif **You turn in:** [Cowl of Mortality](/item/26025)



>**Grand Armsmith Korin says:** Ah, here is your helm, Soandso, may it serve you as well as you have served us.



 **You receive:**  [Custom Cowl of Mortality](/item/2612) 


**This NPC *should* return incorrect items given.**
 
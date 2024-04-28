# Naygog Mitope


## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Naygog Mitope says:** Hail Soandso. I train those young gnomes who wish to [serve as a warrior] in the service of the Dark Reflection and our patron. Bertoxxulous the Plaguelord. Decay and destruction are powerful forces that influence Norrath. It is the duty of the Warriors of the Dark Reflection to bring destruction to the weak and injury to the strong so that our fellow gnomes may be reminded of their own mortality and new strong individuals may rise to power before Bertoxxulous decides it is their time to decay and be replaced like countless before them.



e.self:DoAnim(67);


**You say:** `serve as a warrior`




>**Naygog Mitope says:** Ours is the duty of a martyr. to be the hated and feared hand of destruction and catalyst of change. All roads are paved with destruction and in turn are eventually destroyed. All machines are built from the rubble of broken mountains and in turn become rust and bits of metal. You must outfit yourself with the tools of a warrior. crafted from the destruction of archaic clockworks that have long since finished serving the purpose for which they were built. Take this parchment to Windlebeck Tobokog. he will assist you in the construction of a suit of armor. When you have been properly outfitted return to me for [further instruction].



**You receive:**  [Parchment to Windlebeck](/item/10986)


**You say:** `further instruction`




>**Naygog Mitope says:** It is one thing to destroy the artificial life of a clockwork. It is another thing entirely to claim the life of another gnome. There is a member of the Dark Reflection. Yulcabis. who has been assigned to a task in the Steamfont Mountains. He has failed repeatedly in the tasks assigned to him in the past and has become a burden to the Dark Reflection. Find Yulcabis and slay him. Return to me with the weapon he carries.


**You say:** `armor`




>**Naygog Mitope says:** Armor? For a warrior? Oh yes. You'll need to speak with Windlebeck for that.


else


**You say:** `hail`




>**Naygog Mitope says:** Hail Soandso. I train those young gnomes who wish to [serve as a warrior] in the service of the Dark Reflection and our patron. Bertoxxulous the Plaguelord. Decay and destruction are powerful forces that influence Norrath. It is the duty of the Warriors of the Dark Reflection to bring destruction to the weak and injury to the strong so that our fellow gnomes may be reminded of their own mortality and new strong individuals may rise to power before Bertoxxulous decides it is their time to decay and be replaced like countless before them.

end

## Turn-Ins

local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** [Yulcabis Axe](/item/10990)


>**Naygog Mitope says:** Well done Soandso. Take this Dull Dark Reflection Axe and sharpen it in a forge with a sharpening stone. It may take several attempts if you are unfamiliar with the process. Once the axe has been sharpened take it to Clockwork SmithXIII with a Coyote Pelt and he will put the finishing touches on the weapon.


* __Faction:__ [Dark Reflection](/faction/238) (10)



* __Faction:__ [Eldritch Collective](/faction/245) (-1)



* __Faction:__ [Gem Choppers](/faction/255) (-1)


* __Faction:__ [Deepmuses](/faction/240) (-1)



 **You receive:**  [Dull Dark Reflection Axe](/item/10995) (+100 exp)


elseif  **You turn in:** [Stained Parchment](/item/18759)


>**Naygog Mitope says:** This is fabulous news!!  You have done well, young one. Once you are ready for [further instruction] please let me know, I will guide you through your early and most dangerous days. When you have become more experienced in our art, I will be able to further instruct you on how to progress through your early ranks.


* __Faction:__ [Dark Reflection](/faction/238) (100)



* __Faction:__ [Eldritch Collective](/faction/245) (-10)



* __Faction:__ [Gem Choppers](/faction/255) (-10)


* __Faction:__ [Deepmuses](/faction/240) (-10)



 **You receive:**  [Tin Patched Tunic*](/item/13518) (+20 exp)


**This NPC *should* return incorrect items given.**

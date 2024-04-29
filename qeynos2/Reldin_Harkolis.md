# Reldin Harkolis
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Reldin Harkolis says:** Hail Soandso. Know that only within these few passageways and rooms whose borders are marked by the symbol of the Circle of Unseen Hands can we speak freely of our organization and its undertakings. Neither the streets of the city above nor the sewers and catacombs are free of ears that would harm the Circle of Unseen Hands should they hear of our [secrets].


**You say:** `secret`




>**Reldin Harkolis says:** The Circle has many secrets some of which only Hans may know. Our agents are all about, mingling among the common law abiding folk and working in all manner of profession. At one time we had a significant number of the Qeynos Guard allied to our organization but the loyal soldiers of Antonius Bayle IV has discovered and punished many of them. The ones that remain are hesitant at best to continue their association with us. You will need to exercise much caution within this city as you learn the ropes. I will help get you outfitted in some [gear] that you will find useful in our line of work.


**You say:** `gear`




>**Reldin Harkolis says:** Take this Curing Kit. With it you can assemble an outfit of light, flexible, and sturdy yet inconspicuous leather clothing to protect you from the perils of your job. The materials required will depend on the piece of clothing you desire to craft. Do you plan on crafting Sturdy Workmans [Gloves], Sturdy Workmans [Boots], a Sturdy Workmans [Bracer], a Sturdy Workmans [Cap], Sturdy Workmans [Leggings], Sturdy Workmans [Sleeves], or a Sturdy Workmans [Tunic]? Once you are suitably outfitted return to me and I will inform you of your [next job].



**You receive:**  [Curing Kit](/item/17125)


**You say:** `boot`




>**Reldin Harkolis says:** To craft Sturdy Workmans Boots you require two [silk thread], two ruined wolf pelts, two giant field rat whiskers, and a large king snake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Boot Pattern.



**You receive:**  [Tattered Boot Pattern](/item/19561)
  


**You say:** `bracer`




>**Reldin Harkolis says:** To craft an Sturdy Workmans Bracer you require a [silk thread], a ruined wolf pelt, and a giant field rat whiskers. Once you have the necessary components combine them in your Curing Kit with this Tattered Wristband Pattern.



**You receive:**  [Tattered Wristband Pattern](/item/19558)


**You say:** `cap`




>**Reldin Harkolis says:** To craft a Sturdy Workmans Cap you require two [silk thread], a ruined wolf pelt, a large myotis bat fur, and a large king snake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Coif Pattern.



**You receive:**  [Tattered Cap Pattern](/item/19555)


**You say:** `glove`




>**Reldin Harkolis says:** To craft Sturdy Workmans Gloves you require two [silk thread], a ruined wolf pelt, two giant field rat whiskers, and a large king snake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Glove Pattern.



**You receive:**  [Tattered Glove Pattern](/item/19559)


**You say:** `legging`




>**Reldin Harkolis says:** To craft Sturdy Workmans Leggings you require three [silk thread], a low quality wolf pelt, two large myotis bat furs, and a giant king snake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Pant Pattern.



**You receive:**  [Tattered Pant Pattern](/item/19560)


**You say:** `sleeve`




>**Reldin Harkolis says:** To craft Sturdy Workmans Sleeves you require two [silk thread], a low quality wolf pelt, two large myotis bat furs, and a giant king snake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Sleeves Pattern.



**You receive:**  [Tattered Sleeve Pattern](/item/19557)


**You say:** `tunic`




>**Reldin Harkolis says:** To craft a Sturdy Workmans Tunic you require four [silk thread], a medium quality wolf pelt, a giant myotis bat fur, and a giant king snake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Tunic Pattern.



**You receive:**  [Tattered Tunic Pattern](/item/19556)


**You say:** `next job`




>**Reldin Harkolis says:** A message between two of our agents was recently intercepted by a Qeynos Guardsman. The message is encoded in thieves cant but should the guards eventually decode it we would expect trouble. Guard Gregor, the guard who currently is in possession of the message is out patrolling somewhere in the West Karanas. Find this guard and recover the message. Bring it back to me when you have done so.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** [Message in Thieves Cant](/item/19942)) then


>**Reldin Harkolis says:** Excellent! It is fortunate you recovered this message in time. Take this Rusty Unseen Hands Dagger to a forge and sharpen it with a sharpening stone. It may take you several attempts if you are unfamiliar with the process. Once that is accomplished bring me the sharpened dagger, a gnoll fang, and a large king snake skin and I will put the finishing touches on the weapon for you.





* __Faction:__ [Circle of Unseen Hands](/faction/223) (10)




* __Faction:__ [Merchants of Qeynos](/faction/291) (-1)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)




* __Faction:__ [Guards of Qeynos](/faction/262) (-1)



* __Faction:__ [Kane Bayle](/faction/273) (1)




 **You receive:**  [Rusty Unseen Hands Dagger](/item/19943) (+1000 exp)

elseif(expansion_flag >= 4.0 and  **You turn in:** [Sharpened Unseen Hands Dagger](/item/19944), [Gnoll Fang](/item/13915), [Large King Snake Skin](/item/19945)) then


>*Reldin Harkolis fashions a grip out of the large king snake skin, fastens the gnoll fang to the heel of the hilt, and polishes the blade with a faintly glowing polish. 'Herei syour new weapon young rogue.'*





 **You receive:**  [Dagger of Unseen Hands](/item/20266) (+1000 exp)

**This NPC *should* return incorrect items given.**

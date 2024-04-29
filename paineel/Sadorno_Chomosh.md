# Sadorno Chomosh
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Sadorno Chomosh says:** Salutations. I am Sadorno Chomosh, Templar of Terror. The path of terror taught to us by Cazic-Thule is a dangerous way of life. The perils are great, but the rewards are unimaginable power. In order to harness the powers of fear, you must first know that which you seek to control: terror, dread and fright. I presume that you are still young and have much to learn. If that is the case, I will assist you in acquiring [armaments] to aid you on your journey to power.


**You say:** `armament`




>**Sadorno Chomosh says:** You will require this Mail Assembly Kit that has been prepared in advance for the construction of Templar of Fright armor. The materials required for the armor's construction vary according to the section you desire to craft. When you have acquired your suit of armor, return to me and perhaps you can assist me with a [pending task]. Do you desire to craft a templar of fright [helm], a templar of fright [bracer], templar of fright [gauntlets], templar of fright [boots], templar of fright [vambraces], templar of fright [greaves], or a templar of fright [breastplate]?



**You receive:**  [Mail Assembly Kit](/item/17124)


**You say:** `boot`




>**Sadorno Chomosh says:** To assemble Templar of Fright Boots, obtain two bricks of crude bronze and smelt them in a forge with a water flask and this crude boot mold. Then combine the crude bronze boots with two ruined kobold pelts and two kobold foot bones in the Mail Assembly Kit.



**You receive:**  [Crude Boot Mold](/item/19634)


**You say:** `helm`




>**Sadorno Chomosh says:** To assemble a Templar of Fright Helm you, obtain two bricks of crude bronze and smelt them in a forge with a water flask and this crude helm mold. Then combine the crude bronze helm with one ruined kobold pelt and a kobold skull in the Mail Assembly Kit.



**You receive:**  [Crude Helm Mold](/item/19631)


**You say:** `bracer`




>**Sadorno Chomosh says:** To assemble a Templar of Fright bracer, you will need to obtain a brick of crude bronze and smelt it in a forge with a water flask and this crude bracer mold. Once that is done, combine the crude bronze bracer with a ruined kobold pelt and a kobold ulna bone in the Mail Assembly Kit.



**You receive:**  [Crude Bracer Mold](/item/19632)


**You say:** `gauntlet`




>**Sadorno Chomosh says:** To assemble Templar of Fright gauntlets, obtain two bricks of crude bronze and smelt them in a forge with a water flask and this crude gauntlet mold. Then combine the crude bronze gauntlets with one ruined kobold pelt and two kobold finger bones in the Mail Assembly Kit.



**You receive:**  [Crude Gauntlets Mold](/item/19633)


**You say:** `vambrace`




>**Sadorno Chomosh says:** To assemble Templar of Fright vambraces, obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Vambrace Mold. Then combine the Crude Bronze Vambraces with an Intact Kobold Pelt and two Kobold Humerus Bones in the Mail Assembly Kit.



**You receive:**  [Crude Vambrace Mold](/item/19635)


**You say:** `greave`




>**Sadorno Chomosh says:** To assemble Templar of Fright Greaves, obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Greaves Mold. Then combine the Crude Bronze Greaves with two Intact Kobold Pelts and two Kobold Tibia bones in the Mail Assembly Kit.



**You receive:**  [Crude Greaves Mold](/item/19636)


**You say:** `breastplate`




>**Sadorno Chomosh says:** To assemble a Templar of Fright Breastplate, obtain four bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Breastplate Mold. Then combine the Crude Bronze Breastplate with a Pristine Kobold Pelt, a Kobold sternum, and a Kobold ribcage in the Mail Assembly Kit.



**You receive:**  [Crude Breastplate Mold](/item/19637)


**You say:** `pending task`




>**Sadorno Chomosh says:** The Tabernacle of Terror has many enemies here on Odus who oppose our teachings to our patron deity, Cazic-Thule. The priests of Prexus and Quellious in the city of Erudin seek to purge Odus of our kind, for they view us as a disgrace to the Erudite race. Behind their disdain, however, lies fear. It is this fear that allows us to prosper and become more powerful than the closed-minded fools of Erudin. In the Toxxulia Forest, you will find such a fool, a priest named Terago Omath. This priest attempts to ward the Toxxulia Forest from the presence of the undead.  Seek this Terago Omath and return to me with his head.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** [Terago Omath's Head](/item/20419)) then


>**Sadorno Chomosh says:** Ah, it appears you have learned to control your fear while ridding us of another fool.  Very well done. Take this Cudgel and return to me after sharpening it in a forge, along with a large Briar snake skin, and a petrified eyeball.


 **You receive:**  [Rusty Templar of Fright Cudgel](/item/20414) 

elseif(expansion_flag >= 4.0 and  **You turn in:** [Refined Templar of Fright Cudgel](/item/20415), [Large Briar Snake Skin](/item/20355), [Petrified Eyeball](/item/20402)) then


>**Sadorno Chomosh says:** Very good work. Here is the Cudgel, use it well!


 **You receive:**  [Templar of Fright Cudgel](/item/20417) (+500 exp)

**This NPC *should* return incorrect items given.**






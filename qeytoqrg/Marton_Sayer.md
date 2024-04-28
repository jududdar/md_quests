# Marton Sayer
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Marton Sayer says:** Welcome. Please stock up on provisions, especially if you are headed toward the lair of the vile gnolls. If so, I wish you much luck and many gnoll pelts!! I also have knowledge of a [powerful dog]. I pray you do not encounter him.


**You say:** `powerful dog`




>**Marton Sayer says:** I have encountered a gnoll who spoke the common tongue. He dared to call himself Lord Elgnub. He swore that some day we would cross paths and he would snatch my infant son Joseph from our home. He would stand no chance against me and the mighty [Gnoll Slayer].


**You say:** `gnoll slayer`




>**Marton Sayer says:** Gnoll Slayer is the mighty longsword which was passed down unto me through generations of Sayers. My days of battle are over, but I can still wield her with ferocity. The only thing more precious would be my son, Joseph Sayer. I would trade Gnoll Slayer only for him to be safe and sound at home.


**You say:** `potential`




>**Marton Sayer says:** The true potential of Gnoll Slayer is an enchantment which was once imbedded into a gnoll's eye which was placed into the hilt of the blade. The spell would help you fight off disease and call forth a wolf to fight beside you. Alas, the gnoll eye was stolen from the blade by a great, one-eyed, white gnoll. Alone with the eye, the only book which explained how to return the enchantment was also stolen. I know not where this gnoll might be. If you can find the journal and the eye, return them with the Gnoll Slayer to me for I have been searching for decades.


**You say:** `joseph`




>**Marton Sayer says:** You speak of my son, Joseph Sayer. He is but an infant and is safe here with Mira and me... At least, I believe he is.


else


**You say:** `hail`




>**Marton Sayer says:** Welcome. Please stock up on provisions, especially if you are headed toward the lair of the vile gnolls. If so, I wish you much luck and many gnoll pelts!! I also have knowledge of a [powerful dog]. I pray you do not encounter him.


**You say:** `powerful dog`




>**Marton Sayer says:** I have encountered a gnoll who spoke the common tongue. He dared to call himself Lord Elgnub. He swore that some day we would cross paths and he would snatch my infant son Joseph from our home. He would stand no chance against me and the mighty [Gnoll Slayer].


**You say:** `gnoll slayer`




>**Marton Sayer says:** Gnoll Slayer is the mighty longsword which was passed down unto me through generations of Sayers. My days of battle are over, but I can still wield her with ferocity. The only thing more precious would be my son, Joseph Sayer. I would trade Gnoll Slayer only for him to be safe and sound at home.


**You say:** `joseph`




>**Marton Sayer says:** You speak of my son, Joseph Sayer. He is but an infant and is safe here with Mira and me... At least, I believe he is.

end

## Turn-Ins




if **You turn in:** [Baby Joseph Sayer](/item/12204)


if(eq.get_current_expansion() >= 4.0) then



>**Marton Sayer says:** Baby Joseph!! Look, Momma!! Baby Joseph has been rescued by this good adventurer!! That evil Lord Elgnub made good on his word and snatched my son from under our noses. You saved the day!! For this you shall wield 'Gnoll Slayer'!! Be aware of its [true potential].


else



>**Marton Sayer says:** Baby Joseph!! Look, Momma!! Baby Joseph has been rescued by this good adventurer!! That evil Lord Elgnub made good on his word and snatched my son from under our noses. You saved the day!! For this you shall wield 'Gnoll Slayer'!!



* __Faction:__ [Merchants of Qeynos](/faction/291) (20)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-4)


* __Faction:__ [Antonius Bayle](/faction/219) (3)


* __Faction:__ [Coalition of Tradefolk](/faction/229) (2)


* __Faction:__ [Guards of Qeynos](/faction/262) (4)


 **You receive:**  [Gnoll Slayer](/item/5416) (+500 exp)

elseif(eq.get_current_expansion() >= 6.0 and  **You turn in:** [Gnolls Eye](/item/8357), [Journal of Greater Enchantment](/item/8356), [Gnoll Slayer](/item/5416)


>**Marton Sayer says:** The eye and the journal! What a great day! The Gnoll Slayer shall be returned to full strength because of you. Your service to Qeynos will not soon be forgotten.


* __Faction:__ [Merchants of Qeynos](/faction/291) (200)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-40)


* __Faction:__ [Antonius Bayle](/faction/219) (30)


* __Faction:__ [Coalition of Tradefolk](/faction/229) (20)


* __Faction:__ [Guards of Qeynos](/faction/262) (40)


 **You receive:**  [Gnoll Slayer](/item/5417) (+1500 exp)

**This NPC *should* return incorrect items given.**

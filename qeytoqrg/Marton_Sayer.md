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




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_720.png" alt="" /> <a
                                href="/item/12204" data-url="12204" class="tooltip-link link">Baby Joseph Sayer</a>) then


if(eq.get_current_expansion() >= 4.0) then



>**Marton Sayer says:** Baby Joseph!! Look, Momma!! Baby Joseph has been rescued by this good adventurer!! That evil Lord Elgnub made good on his word and snatched my son from under our noses. You saved the day!! For this you shall wield 'Gnoll Slayer'!! Be aware of its [true potential].


else



>**Marton Sayer says:** Baby Joseph!! Look, Momma!! Baby Joseph has been rescued by this good adventurer!! That evil Lord Elgnub made good on his word and snatched my son from under our noses. You saved the day!! For this you shall wield 'Gnoll Slayer'!!



Your faction standing with [Merchants of Qeynos](/faction/291) got better (<span class='text-success'>+20</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-4</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+3</span>)


Your faction standing with [Coalition of Tradefolk](/faction/229) got better (<span class='text-success'>+2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+4</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5416" data-url="5416" class="tooltip-link link">Gnoll Slayer</a> (+500 exp)

 

elseif(eq.get_current_expansion() >= 6.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_886.png" alt="" /> <a
                                href="/item/8357" data-url="8357" class="tooltip-link link">Gnolls Eye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/8356" data-url="8356" class="tooltip-link link">Journal of Greater Enchantment</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5416" data-url="5416" class="tooltip-link link">Gnoll Slayer</a>) then


>**Marton Sayer says:** The eye and the journal! What a great day! The Gnoll Slayer shall be returned to full strength because of you. Your service to Qeynos will not soon be forgotten.


Your faction standing with [Merchants of Qeynos](/faction/291) got better (<span class='text-success'>+200</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-40</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+30</span>)


Your faction standing with [Coalition of Tradefolk](/faction/229) got better (<span class='text-success'>+20</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+40</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5417" data-url="5417" class="tooltip-link link">Gnoll Slayer</a> (+1500 exp)

 

**This NPC *should* return incorrect items given.**

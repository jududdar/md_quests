# Elder Animist Dumul



[Elder Animist Dumul](/npc/155040) is a level 60 Vah Shir Warrior that spawns in [The City of Shar Vahl](/zone/155).



## Dialog

**You say:** `spiritual`



>**Elder Animist Dumul says:** Well, my prying little friend. Someone as inquisitive as you may be of use to us. Perhaps you were sent to us by the very ones we seek to help. The spirits are capable of far more impressive manipulations. If any time warrants such trickery or nudging of fate, I would guess that this day would qualify. Be aware of one thing, youth... the beastlord that follows the path I see before us this day may not return to this house unscathed... if they return to me at all. If you are the Khati Sha I seek, prove your worth in combat and return to me with the Copper Medal of War. You can get this medal from assisting the soldiers in the Grimling Forest.

**You say:** `ready`



>**Elder Animist Dumul says:** As you may have gathered during our first meeting, we have been dealing with a situation that differs from any that we have dealt with in the past. We dismissed the situation as improbable at first, but unfortunately we have just attained certain proof. Our scouts have found that an individual has discovered a means of manipulating elder spirits. These spirits have a great deal of power over their natural environments. This person has used some new magic to take that power for himself

**You say:** `new magic`



>**Elder Animist Dumul says:** The scouts were able to witness some of the rituals used to capture the spirits. They described a process that involved the use of a wooden totem, shaped in the image of the spirit's true form. The magic-user is able to use that totem to siphon the power of the spirit. He then uses that power to transform the spirit into an entity of malign intent. Fortunately, our research has given us the name of this vile magic-user.

**You say:** `name`



>**Elder Animist Dumul says:** His name is Draz Nurakk. It appears that he has learned the ways of the Khati Sha to the point of mastery. His magic and will seem to defy even the darkest secular beliefs of his people. We harbor no ill will toward the Iksar, but this individual must be stopped. This leads us to your mission.

**You say:** `mission`



>**Elder Animist Dumul says:** We need you to meet our scouts and assist them in releasing the spirits that have already been affected by this magic. None of the scouts have reported in for some time, so you will need to find them. Once you find them, show them the seal that I gave you. They will help you to release the spirits and capture the totems. Please have the scouts help you to place the totems in the case that I gave you. If you lose the seal or damage it in combat, please return to me for another. Good luck, Soandso. You must succeed if we are to maintain the balance of the spiritual realm.

**You say:** `lost seal`



if( **Faction is** > Kindly) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/9031" data-url="9031" class="tooltip-link link">Official Seal of the Khati Sha</a>


else



>**Elder Animist Dumul says:** You need to prove your dedication to our cause before I can discuss such matters with you.

end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/9061" data-url="9061" class="tooltip-link link">Collection of Spirit Lore</a>) then


>**Elder Animist Dumul says:** Thank you, young courier. I will not need anything more from you at this time. We have a great deal of research to do and absolutely no time to complete said studies. Did the Historian tell you anything? Matters are bad enough without rumors floating about in the shadows. Speak up... did you hear anything about our situation?

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/4393" data-url="4393" class="tooltip-link link">Copper Medal of War</a> or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/4375" data-url="4375" class="tooltip-link link">Silver Lined Copper Medal of War</a> or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/4378" data-url="4378" class="tooltip-link link">Gold Lined Copper Medal of War</a>) then


>**Elder Animist Dumul says:** You have returned at a most opportune time, Soandso. If this medal is indicative of your abilities in combat, I may be able to find a slight amount of hope soon. We have learned answers for many of the questions that we had prior to your last visit. Please take this seal and this container. Place them somewhere safe, while I gather the information that we've accumulated so far. Let me know when you have the seal packed and are ready to be briefed. Should you ever lose it, just ask for another.


Your faction standing with [Savage Spirit](/faction/5064) got better (<span class='text-success'>+900</span>)


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/9031" data-url="9031" class="tooltip-link link">Official Seal of the Khati Sha</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_837.png" alt="" /> <a
                                href="/item/17361" data-url="17361" class="tooltip-link link">Carved Wooden Chest</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/9044" data-url="9044" class="tooltip-link link">Sealed Box of Totems</a>) then


>**Elder Animist Dumul says:** I have received word from several of our scouts indicating your impending arrival. We are all very pleased that you were able to release all of the spirits before any true harm could manifest itself. Your efforts have not only restored balance to the spirit realm, they seem to have also acted to hinder any other plans our antagonist may have had... for the time being.


>**Elder Animist Dumul says:** Our Taruun scouts have discovered Draz Nurakk's location. A scout has returned from a set of islands on the Old World. The islands are in a place called Timorous. The Taruun returned while leaving a scout behind to insure that the foul Animist does not evade us any further. You will need to find the island on which our scout has set up camp. The island has a great statue on it. Hopefully, he will still be in that location. Show him this seal and he will know that I sent you to assist.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/9045" data-url="9045" class="tooltip-link link">Seal of Elder Dumul</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/9048" data-url="9048" class="tooltip-link link">Sack of Broken Glass</a>) then


>**Elder Animist Dumul says:** My fears were well founded, and I am glad that I have had people that are able to understand those fears. Please do not think that I have intentionally placed you in the path of harm, but I did have my suspicions about our adversary's strength. I am not surprised that he was able to deceive us in this manner. I thank the spirits that you were able to evade harm in your completion of this task.


>**Elder Animist Dumul says:** Take this note to Arms Historian Qua. He has been researching a means of circumventing any protective magic that Draz Nurakk may have in place. When you meet him next, you will be well equipped to complete the restoration of balance to the spirit realm. Make your way to Qua and do as he says.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/9049" data-url="9049" class="tooltip-link link">Note for Historian Qua</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_518.png" alt="" /> <a
                                href="/item/9055" data-url="9055" class="tooltip-link link">Jagged Claw of Rending</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_518.png" alt="" /> <a
                                href="/item/9056" data-url="9056" class="tooltip-link link">Jagged Claw of Rending</a>) then


>**Elder Animist Dumul says:** These claws are exquisite. I can see that a great deal of thought went into their design. Now it is your turn to demonstrate your proficiency in your chosen role. You have a great challenge ahead of you, for we have determined that only these claws will work to harm this dark animist, this corrupter of spirits. You will need the support of your people; but in the only the strength of your will can save us.


>**Elder Animist Dumul says:** Our scouts have tracked Draz Nurakk to an abandoned village in the Fungus Grove. We learned of his intent to track you down. I take it that he did not appreciate your willingness to assist us. He knows who you are, so it will be best for us to get him before he can conjure up any more surprises. Find Scout Halmia in the Grove and give her this seal. Then bring the evidence of his destruction to me when you are done. Place his head, the seal, and those claws in this box and return it to me.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_518.png" alt="" /> <a
                                href="/item/9055" data-url="9055" class="tooltip-link link">Jagged Claw of Rending</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_518.png" alt="" /> <a
                                href="/item/9056" data-url="9056" class="tooltip-link link">Jagged Claw of Rending</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/9057" data-url="9057" class="tooltip-link link">Khati Sha Seal of War</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_837.png" alt="" /> <a
                                href="/item/17362" data-url="17362" class="tooltip-link link">Acrylia Gilded Box</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/9060" data-url="9060" class="tooltip-link link">Sealed Gilded Wooden Chest</a>) then


>*Elder Animist Dumul opens the container and looks at its contents and says, 'Soandso, you have saved the balance of the spirit realm. Your selflessness has made an impression that will last well beyond the effects of your recent deeds. The inhabitants of this realm are all in your debt. Your efforts to restore balance in the material realm have been worth more than we can reward you for.'*


**Elder Animist Dumul shouts:** <span class="text-danger">Citizens of Shar Vahl, please take the time to acknowledge the efforts of a true champion and hero to our people. Soandso has worked valiantly with great personal risk, to restore balance to our realm. We, the Khati Sha of Shar Vahl, feel that only a spirit as strong as Soandso can be entrusted with the Claws of the Savage Spirit. Please take this time to give Soandso your thanks and respect.</span>


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_518.png" alt="" /> <a
                                href="/item/8496" data-url="8496" class="tooltip-link link">Claw of the Savage Spirit</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_518.png" alt="" /> <a
                                href="/item/8495" data-url="8495" class="tooltip-link link">Claw of the Savage Spirit</a>) 

 

**This NPC *should* return incorrect items given.**

# Spiritist Ragnar



[Spiritist Ragnar](/npc/155195) is a level 50 Vah Shir Shopkeeper that spawns in [The City of Shar Vahl](/zone/155).




## Dialog

**You say:** `Hail`



>**Spiritist Ragnar says:** Well hello... How may I help you?

**You say:** `love potion`



>**Spiritist Ragnar says:** Love potion? Never been done and not worth the risk to try after what happened to Kanaad. 

**You say:** `Kanaad`



>**Spiritist Ragnar says:** Old Kanaad taught me a lot of what I know- he was about the greatest potions expert in the city back then. He started gathering legends and lore about some infamous love potion. Not some silly thing to make the girl of your dreams fall in love mind you- this fabled tonic was intended to be shared only between two who had found true love. If their feelings were strong enough it would... well, that was part of the problem, no one knew what it was supposed to do. Kanaad learned of some crazy human in the mountains that had supposedly figured out the secret to the potion. The results were not what anyone had hoped for.

**You say:** `result`



if( **Faction is** > Indifferent) then



>*Spiritist Ragnar shuffles a bit uncomfortably, considering whether or not he should be telling you this, 'This is not something that I would normally talk about, but Soroush came by and told me that you are on the trail of Behari- if this will help you find him, then I will tell you all that I know... Kanaad had a time getting the ingredients and was only to make just a very little bit. He sat down with his love, alone in a room and intended to share the elixir. Well, that was the last anyone saw of her, and he was manic, out of his mind... The mixture had driven him from his senses and he snapped. It took quite a bit to restrain him and figure out what to do next.'*


else



>**Spiritist Ragnar says:** I am sorry, but I am right in the middle or something.


**You say:** `next`



if( **Faction is** > Indifferent) then



>*Spiritist Ragnar considers you for a moment and, as though reminding himself that you are trustworthy, continues, 'Well what we learned was that not only did the mixture drive the drinker mad, but it was incredibly addictive as well- a horrible combination. All that we could do was give him a controlled intake of the potion for his addiction and try to treat his dementia. With his returning sanity came the realization of what he had done to his love. It was the most harrowing thing I have ever seen someone go through in all of my life... He is better now, but has never quite been the same and rarely speaks to strangers. Give him this and you should at least get a chance to explain.'*



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/5990" data-url="5990" class="tooltip-link link">Kanaad's Supplies</a>


else



>**Spiritist Ragnar says:** I am sorry, but I am right in the middle or something.

end



## Turn-Ins





local gland =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_818.png" alt="" /> <a
                                href="/item/30665" data-url="30665" class="tooltip-link link">A Whiptail Poison Gland</a>}


if(gland > 0) then


repeat



>**Spiritist Ragnar says:** A blessing indeed! You have done well to bring this to me. With these glands I will be able to save many lives. Thank you friend. Shar Vahl And its people are in your debt. Please, accept these gifts to assist you in your endeavors. It Is the least I can do to return the favor!



Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_639.png" alt="" /> <a
                                href="/item/31584" data-url="31584" class="tooltip-link link">Padded Cap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_656.png" alt="" /> <a
                                href="/item/31589" data-url="31589" class="tooltip-link link">Padded Cape</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_500.png" alt="" /> <a
                                href="/item/31586" data-url="31586" class="tooltip-link link">Padded Choker</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_572.png" alt="" /> <a
                                href="/item/31590" data-url="31590" class="tooltip-link link">Padded Cord</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_517.png" alt="" /> <a
                                href="/item/31593" data-url="31593" class="tooltip-link link">Padded Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_631.png" alt="" /> <a
                                href="/item/31594" data-url="31594" class="tooltip-link link">Padded Pants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_666.png" alt="" /> <a
                                href="/item/31595" data-url="31595" class="tooltip-link link">Padded Sandals</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_665.png" alt="" /> <a
                                href="/item/31588" data-url="31588" class="tooltip-link link">Padded Shawl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/31585" data-url="31585" class="tooltip-link link">Padded Veil</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_638.png" alt="" /> <a
                                href="/item/31592" data-url="31592" class="tooltip-link link">Padded Wristband</a>) (+250 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 



gland = gland - 1;


until gland == 0





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_927.png" alt="" /> <a
                                href="/item/30602" data-url="30602" class="tooltip-link link">A Bloodling Carapace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1137.png" alt="" /> <a
                                href="/item/30964" data-url="30964" class="tooltip-link link">Siver's Claw</a>) then


>**Spiritist Ragnar says:** Well done Soandso, I hope it isnt too late.'' Ragnar begins to chant over the carapace and the claw, holding each in opposite hands. A soft light travels from the claw to the carapace as the claw turns to dust. Ragnar opens his eyes and begins to speak, ''It has worked, but all we have done is buy ourselves more time. While you were away, I have been speaking to Master Barkhem. He has a shield frame that can support these carapaces. You will need to craft such a shield by including this carapace and into the frame along with enough to fill each slot. You are doing quite well young Astrall, Siver has grown a little stronger. You can make use of her innate dexterity by weaving this spell.'


>*Spiritist Ragnar hands Soandso a scroll before he continues to speak. 'When you have completed the construction of the shield, return it to me and I will strengthen the anchor.'*


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15040" data-url="15040" class="tooltip-link link">Spell: Strengthen</a> 

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_927.png" alt="" /> <a
                                href="/item/30977" data-url="30977" class="tooltip-link link">A Frosted Carapace</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1244.png" alt="" /> <a
                                href="/item/30965" data-url="30965" class="tooltip-link link">Dull Frostweavers Shield</a>) then


>**Spiritist Ragnar says:** Nicely done Soandso. This anchor should be sufficient to keep Siver bound to this realm for a while. She is strong enough to blind your enemies with a bright flash of light now, all you have to do is call on her spirit. I still cannot make complete sense of her thoughts. I think she is trying to tell me of another whisperling entrapped within the crater. Keep an eye open for the whisperling Scorpialis.


>**Spiritist Ragnar says:** In the meantime, you can seek out a shield made of Xakra. Xakra made of the ethereal fabric of the spirit realm. I know the Shak Dratha within the thicket are weavers of this rare form of shadow silk. Such a shield can help us strengthen the anchor, making it easier for Siver to aid you. It will also improve her health greatly. She has been through a lot and is in rather poor condition as it stands now.


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15201" data-url="15201" class="tooltip-link link">Spell: Flash of Light</a> (+1000 exp)

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1244.png" alt="" /> <a
                                href="/item/30966" data-url="30966" class="tooltip-link link">Frostweavers Shield</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1136.png" alt="" /> <a
                                href="/item/30962" data-url="30962" class="tooltip-link link">A Frosted Bag</a>) then


>**Spiritist Ragnar says:** Eh? What have we here?'' Ragnar examines the frosted claw carefully. He closes his eyes and begins to chant while holding the claw cupped between his hands. As he opens his eyes he nods at you and begins to speak. ''You have done well to bring her here Astrall. This is a whisperling, her name is Siver. She is very young, so it is hard for me to understand her. From what I gather, she has an important task to fulfill, but I am still unsure what that task may be. Please take her with you for now, I think that is her wish. Perhaps Grawleh will be able to assist us further, and maybe even find a more suitable anchor for her. I think it would be wise to show her to him.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1137.png" alt="" /> <a
                                href="/item/30963" data-url="30963" class="tooltip-link link">Claw of Frost</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**

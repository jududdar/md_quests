# Herald Telcha





## Dialog

**You say:** `hail`



>**Herald Telcha says:** Hail to you, lesser being! It is good to see you seeking the enlightenment and satisfaction that can only come from serving the Sarnak! Experience for yourself the joy of fealty to our Lord the Overking Bathezid Di'zok! I am Telcha, lesser apprentice sub-herald in training to the Court of Di'zok and I stand ready to welcome those who would serve our noble Overking. Are you here to [aid] us?

**You say:** `aid`



>**Herald Telcha says:** Ah, so good of you to strive to improve yourself! So often members of your pathetic lesser races plod along in ignorance, unaware of the most Noble empire of the Di'zok. Enough though of the chit-chat, as I'm sure you are most eager to make yourself useful! Before you may enter our worthy city and be looked upon as a valuable servant, you must prove your worth to our [cause].

**You say:** `cause`



>**Herald Telcha says:** The first task I shall set you is the slaying of goblins! Ooh, how very heroic you must feel to finally have a worthy goal guiding your previously menial existance! Yes, go forth from here and journey to Droga, stronghold of our enemies. Slay the warriors and menials of the Mountain Death Clan, bring havoc to their homes. Return to me with proof of your deeds, to raise in your standing with the Dizok. Bring me [tokens] of many dead goblins, and one day you shall walk among us.

**You say:** `token`



>**Herald Telcha says:** As proof of your deeds I shall require either 2 Mountain Death mineral salts, or a patch of green goblin skin. Bring me many of these, as you bring destruction on the goblin city, and I shall speak to my superiors of your efforts on our behalf. Do enough for our cause, and I shall reward you directly. Return to me later and remind me that you serve the Sarnak, and I may have a ring for you if you are worthy.

**You say:** `serve the sarnak`



if( **Faction is** < Kindly) then 



>**Herald Telcha says:** Away with you! I am the herald of the Dizok Overking, here to greet the servants of my master. If you would walk within our city, go forth and prove yourself our ally by slaying our goblin enemies! Advance into our city at your own peril, as our soldiers regard you as a foe!


elseif( **Faction is** == Kindly) then 



>**Herald Telcha says:** You have not yet done enough service for the Sarnak Collective, and my Dizok Masters. Return to me when you have done more, and I may reward you with a ring of service.


elseif(( **Faction is** > Kindly) and (**Your level** < 50)) then 



>**Herald Telcha says:** What to do, what to do.. You've served the Di'zok well, young one but you are not yet experienced enough to wear the Signet of the Di'zok. Come back when you've seen a bit more of the world, and the ring shall be yours.


elseif(( **Faction is** > Kindly) and (**Your level**> 49)) then 



>**Herald Telcha says:** Indeed you do my friend, indeed you do! Walk among us in safety, wear this ring as a symbol of your service to our cause. Continue your efforts in our war on the goblins, and your rewards shall increase. Return to me your ring, along with the head of the Drogan Warlord Skargus, and I'll give you an even greater badge of honor. Good day to you, servant of the Sarnak.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1045.png" alt="" /> <a
                                href="/item/5728" data-url="5728" class="tooltip-link link">Di'zok Signet of Service</a>

end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_996.png" alt="" /> <a
                                href="/item/6476" data-url="6476" class="tooltip-link link">Head of Skargus</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1045.png" alt="" /> <a
                                href="/item/5728" data-url="5728" class="tooltip-link link">Di'zok Signet of Service</a>) then 


>**Herald Telcha says:** Ah hah! You are notworthy indeed amongst the servants of the Sarnak! Perhaps I should have you killed, before your deeds outdo mine.. Hmm.. Guards! Guards! Haha, do not panic menial being, in fact I am most impressed with your service. Here is the ring I promised you in exchange for your efforts.





Your faction standing with [Brood of Di`Zok](/faction/451) got better (<span class='text-success'>+500</span>)


Your faction standing with [Sarnak Collective](/faction/307) got better (<span class='text-success'>+500</span>)


Your faction standing with [Goblins of Mountain Death](/faction/259) got worse (<span class='text-danger'>-200</span>)


eq.delete_global("RegalBandBathezid");


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1148.png" alt="" /> <a
                                href="/item/5727" data-url="5727" class="tooltip-link link">Regal band of Bathezid</a> (+50000 exp)

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1045.png" alt="" /> <a
                                href="/item/5728" data-url="5728" class="tooltip-link link">Di'zok Signet of Service</a> 

 

elseif(( **Faction is** >= Ally) and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1148.png" alt="" /> <a
                                href="/item/5727" data-url="5727" class="tooltip-link link">Regal band of Bathezid</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1148.png" alt="" /> <a
                                href="/item/5727" data-url="5727" class="tooltip-link link">Regal band of Bathezid</a> 

 

else 


local salt =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1015.png" alt="" /> <a
                                href="/item/16972" data-url="16972" class="tooltip-link link">Mt. Death Mineral Salts</a>}, 2


local skin =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1233.png" alt="" /> <a
                                href="/item/22135" data-url="22135" class="tooltip-link link">Green Goblin Skin</a>}


if(salt > 0) then



repeat




>**Herald Telcha says:** Ah, most excellent! You are sure to be more highly valued as our servant once I speak to my masters of this! Mountain Death Mineral Salts, they shall grace the Overkings table this very night! Be off, minion! Fetch us some more salts to prove your value!









Your faction standing with [Brood of Di`Zok](/faction/451) got better (<span class='text-success'>+3</span>)




Your faction standing with [Sarnak Collective](/faction/307) got better (<span class='text-success'>+3</span>)




Your faction standing with [Goblins of Mountain Death](/faction/259) got worse (<span class='text-danger'>-1</span>)




 &#127873; **You receive:** 0 (+500 exp)

 




salt = salt -1;



until salt == 0;



if(skin > 0) then 



repeat




>**Herald Telcha says:** Green Goblin Skin! You have indeed been busy! I shall speak to my masters of this, continue your good work and return to me with more skins.









Your faction standing with [Brood of Di`Zok](/faction/451) got better (<span class='text-success'>+3</span>)




Your faction standing with [Sarnak Collective](/faction/307) got better (<span class='text-success'>+3</span>)




Your faction standing with [Goblins of Mountain Death](/faction/259) got worse (<span class='text-danger'>-1</span>)




 &#127873; **You receive:** 0 (+500 exp)

 




skin = skin - 1;



until skin == 0;



**This NPC *should* return incorrect items given.**






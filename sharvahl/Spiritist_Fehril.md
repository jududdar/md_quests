# Spiritist Fehril




## Dialog

**You say:** `Hail`



>*Spiritist Fehril opens his eyes as he awakens from a deep meditaion, 'Hello, Soandso, how might I be of assistance to you?*

**You say:** `Merchant Ayyad`



>**Spiritist Fehril says:** You can find Merchant Ayyad in 'The Merchants' Quarter which lies in the middle of the city just east of the Royal Palace.

**You say:** `love potion`



>**Spiritist Fehril says:** Hmmm, while I dabble in the art of potions mixing myself, I am no scholar in the field. Perhaps Spiritist Ragnar would be of more assistance to you.
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a>) then


>**Spiritist Fehril says:** Soandso! So good to see you! It is my honor to guide you for a time. May the spirits inspire my words that you might grow wise in the hearing. You are young and need to be strengthened. Bring me three hairless hides of rockhopper young. You can find them in the crater surrounding our city, formed when the portion of Norrath our city is built upon came to rest in its current location.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1221.png" alt="" /> <a
                                href="/item/3488" data-url="3488" class="tooltip-link link">Hairless Rockhopper Hide</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1221.png" alt="" /> <a
                                href="/item/3488" data-url="3488" class="tooltip-link link">Hairless Rockhopper Hide</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1221.png" alt="" /> <a
                                href="/item/3488" data-url="3488" class="tooltip-link link">Hairless Rockhopper Hide</a>) then


>*Spiritist Fehril craftily places the hides in a circular frame and hands you the product, 'You've completed my first task and as a reward I present you with this small token. May it serve to protect you from our enemies.*


>**Spiritist Fehril says:** As a member of the sacred Dar Khura, you will be asked to become proficient in the art of brewing. Sweetwater is produced by combining xakra bile and scorpion blood with a flask of water in a brew barrel. Pour two flasks of sweetwater into this cask and return it to me.


**Signaled to:**  [Elder Spiritist Grawleh](/npc/155164)


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_759.png" alt="" /> <a
                                href="/item/3489" data-url="3489" class="tooltip-link link">Hopperhide Buckler</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_979.png" alt="" /> <a
                                href="/item/17232" data-url="17232" class="tooltip-link link">Empty Cask</a>) (+500 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_979.png" alt="" /> <a
                                href="/item/3493" data-url="3493" class="tooltip-link link">Cask of Sweetwater</a>) then


>*Spiritist Fehril takes a sip from the cask and furrows his brow.*


>**Spiritist Fehril says:** Well, it's a start I suppose. With a little practice you are certain to get better. Here is some hide treatment I just made, it will make your buckler stronger. It just needs some time to ferment before I apply it.


>**Spiritist Fehril says:** Citizens often need assistance and the Dar Khura must be available whenever possible. [Merchant Ayyad] has requested someone to run an errand and I am sending you. Return to me with Ayyad's seal, the hide treatment, your buckler, and your initiate's cloak.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1153.png" alt="" /> <a
                                href="/item/3494" data-url="3494" class="tooltip-link link">Hopperhide Treatment</a> (+500 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_759.png" alt="" /> <a
                                href="/item/3489" data-url="3489" class="tooltip-link link">Hopperhide Buckler</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1153.png" alt="" /> <a
                                href="/item/3494" data-url="3494" class="tooltip-link link">Hopperhide Treatment</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/3499" data-url="3499" class="tooltip-link link">Ayyad's seal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_656.png" alt="" /> <a
                                href="/item/2878" data-url="2878" class="tooltip-link link">Initiate's Cloak of Shar Vahl</a>) then


>**Spiritist Fehril says:** Well done you Soandso, your deeds will not go unnoticed. You will now be known throughout the land as an official recruit of the revered Dar Khura. As your status improves so will the rewards for your service. Here is your treated buckler, your new cloak, and a spell I trust you will find a use for. Show your buckler to Fharra Cawfeet and she will continue your training.


>*Spiritist Fehril shouts, 'My fellow Vah Shir, I present to you the newest recruit to the sacred Dar Khura. Soandso has shown great potential in the service of our sect. Please join me in thanking this citizen for service to our people!'*


eq.set_global("Shar_Vahl_Cit","8",5,"F");


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_760.png" alt="" /> <a
                                href="/item/3495" data-url="3495" class="tooltip-link link">Treated Hopperhide Buckler</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_841.png" alt="" /> <a
                                href="/item/3496" data-url="3496" class="tooltip-link link">Cloak of the Dar Khura Recruit</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15275" data-url="15275" class="tooltip-link link">Spell: Frost Rift</a>) (+500 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1053.png" alt="" /> <a
                                href="/item/5542" data-url="5542" class="tooltip-link link">Mydi's Token</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_841.png" alt="" /> <a
                                href="/item/3496" data-url="3496" class="tooltip-link link">Cloak of the Dar Khura Recruit</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_760.png" alt="" /> <a
                                href="/item/5543" data-url="5543" class="tooltip-link link">Imbued Hopperhide Buckler</a>) then


>**Spiritist Fehril says:** Your progress fills me with pride. Please take these things as a sign of our appreciation. I hope that they help you as much as you have helped us. When you are ready to continue your training, please contact Jaima Seyel. You'll most likely find her in the Dar Khura Guildhall. She will train you from this point.


**Spiritist Fehril shouts:** <span class="text-danger">Fellow citizens, may I present to you with our newest apprentice to the sacred Dar Khura. Soandso has assisted us for some time now and we can only hope that this assistance doesn't go unnoticed. Now, please join me in thanking Soandso for such selfless service to our people.</span>


Your faction standing with [Dar Khura](/faction/1533) got better (<span class='text-success'>+20</span>)


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_760.png" alt="" /> <a
                                href="/item/5543" data-url="5543" class="tooltip-link link">Imbued Hopperhide Buckler</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_841.png" alt="" /> <a
                                href="/item/5544" data-url="5544" class="tooltip-link link">Cloak of the Dar Khura Apprentice</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15282" data-url="15282" class="tooltip-link link">Spell: Spirit Strike</a>) (+ <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/1500" data-url="1500" class="tooltip-link link">Box of the Guilty</a> exp)

 

**This NPC *should* return incorrect items given.**

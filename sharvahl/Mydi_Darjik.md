# Mydi Darjik

## Dialog

**You say:** `Hail`



>**Mydi Darjik says:** Greetings, did you need assistance with something or are you just browsing?

**You say:** `treat`



>**Mydi Darjik says:** Sure, I can help you with that.  You'll need a specially soaked cloth to help the tincture set into the material of the shield.  Please let me see the buckler so that I can give you the appropriate size of cloth.

**You say:** `soaking solution`



>**Mydi Darjik says:** It's really not as difficult as it sounds. The spores required to make the solution that you'll need are easy to find. They grow in the dulfis mushrooms that are found in the caves beyond the thicket. You'll just need to throw the whole mushroom into a flask of water to brew. Once the dulfis has boiled in the water for a while, you'll get a murky gray liquid. Boil the cloth in that liquid for a bit in the brew barrel and then wrap the steaming cloth around the buckler and the tincture that Fharra gave you. Let the cloth cool and you should see the desired results. Bring the buckler to me once you're done and I'll tell you if you did it correctly.
end

## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_760.png" alt="" /> <a
                                href="/item/3495" data-url="3495" class="tooltip-link link">Treated Hopperhide Buckler</a>) then


>*Mydi Darjik cuts the cloth big enough to cover your buckler twice over and folds it neatly. She puts the cloth on the buckler and hands it to you. She looks around for a moment...*


>**Mydi Darjik says:** Sometimes I feel as if the spirits are playing tricks on me. I'm out of spores. I never seem to run out of spores until the times when I need them most. You'll need to gather them on your own to make the [soaking solution].


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_760.png" alt="" /> <a
                                href="/item/3495" data-url="3495" class="tooltip-link link">Treated Hopperhide Buckler</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/5538" data-url="5538" class="tooltip-link link">Large Folded Cloth</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_760.png" alt="" /> <a
                                href="/item/5543" data-url="5543" class="tooltip-link link">Imbued Hopperhide Buckler</a>) then


>**Mydi Darjik says:** Quite impressive! Quite impressive, indeed! To be honest it took me a very long time to become that good at imbuing items and enhancing their natural properties. You show a great deal of promise. If you will be willing to help me with another task, I could recommend you for a possible promotion within the ranks of the Dar Khura. I need you to take this bag and fill it with wet fang eyes. Just find a stagnant body of water, spear a wet fang, and pop its eyes out!


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_760.png" alt="" /> <a
                                href="/item/5543" data-url="5543" class="tooltip-link link">Imbued Hopperhide Buckler</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/17076" data-url="17076" class="tooltip-link link">Small Slimy Bag</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/5541" data-url="5541" class="tooltip-link link">Very Slimy Bag</a>) then


>**Mydi Darjik says:** Thank you very much! I was almost out of these eyes and I'm sure you'll agree they aren't easy to come by. Your assistance will not go unnoticed. Here is the blessing I promised you. Take this token to Spiritualist Fehril along with your recruits cloak, and your wonderful new buckler. He'll know that I send you with my blessing. Take care and may the spirits guide you, young Dar Khura.


Your faction standing with [Dar Khura](/faction/1533) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1053.png" alt="" /> <a
                                href="/item/5542" data-url="5542" class="tooltip-link link">Mydi's Token</a> (+3500 exp)

 

**This NPC *should* return incorrect items given.**

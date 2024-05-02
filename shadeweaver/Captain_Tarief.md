# Captain Tarief

local count = 0;
## On NPC Spawn

**Set a timer** named *tarief* for 180 seconds
## Timer(s)

count = count + 1;

if(count == 1) then


>**Captain Tarief says:** It is important for us to hunt well and provide food to our brethren. Use stealth to surprise your opponent and attack them from behind. This is a vital tactic for the Taruun.

if(count == 2) then


>**Captain Tarief says:** Taking a spit with you into battle allows you to cook the meat you find in the field. This will help sustain your companions as well as yourself.

if(count == 3) then


>**Captain Tarief says:** Remember to try to maneuver behind your opponent, attack with wisdom and cunning.

if(count == 4) then


>**Captain Tarief says:** We must clear out the hoppers that attack us. These beasts can become very dangerous if they are left to breed. We have already lost many of our brethren to the larger ones.

if(count == 5) then


>**Captain Tarief says:** It is important for us to stay light and nimble on our feet. Do not overburden yourself with equipment you have no need for.

if(count == 6) then


>**Captain Tarief says:** Avoid heavier armor, let the Khala Dun take the brunt of the blows while you maneuver behind the enemy. If they focus their attacks on you, it is wise to retreat until your companions are able to distract them from you.

if(count == 7) then


>**Captain Tarief says:** Remember your honor. Do not lay claim to a kill that does not belong to you. Both victory and spoils belong to the one who has initiated the battle.

if(count == 8) then


>**Captain Tarief says:** Pay close attention to your surroundings. When you are in danger, it is best to know the quickest way back to safety.


count = 0;


**Set a timer** named *tarief* for 180 seconds
end

## Dialog

**You say:** `hail`



>**Captain Tarief says:** Well met, have you [come to aid] us in hunting the hoppers of the thicket?

**You say:** `come to aid`



>**Captain Tarief says:** If you are preparing to hunt, then there are a few things you should know. Some of the hoppers have unique abilities. Knowledge of these abilities can mean the difference between life and death. I will tell you a little bit about them if you [wish to listen].

**You say:** `wish to listen`



>**Captain Tarief says:** A wise choice, it is good to learn all that you can of the prey before initiating the hunt. Such a tactic is vital when you set out for larger game. Learn of your prey's strengths and weaknesses and you shall have the upper hand. Saureks may all seem similar to one another at first glance, but this is not the case. Such a mistake has left many Taruun dead. I have learned that the darkclaw saureks have venom dripping from their claws. There are a few other [unique qualities] to the saureks as well.

**You say:** `unique qualities`



>**Captain Tarief says:** Each of the saureks have their own unique set of scales. I am able to tell which saurek my trainees have managed to hunt successfully by the scale they return to me. Feel free to join in our lesson or the hunt. I hope that you will benefit from my advice. Hunt well, Soandso.
end

## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30861" data-url="30861" class="tooltip-link link">Saurek Hopper Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30861" data-url="30861" class="tooltip-link link">Saurek Hopper Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30861" data-url="30861" class="tooltip-link link">Saurek Hopper Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30861" data-url="30861" class="tooltip-link link">Saurek Hopper Scales</a>) then 


>**Captain Tarief says:** What have we here? Aha! Look here everyone. Soandso has returned victorious! Well done. You are entitled to the reward for slaying the Saurek Hoppers. I hope all my trainees turn out as skilled as you. Perhaps you should consider hunting more difficult prey from now on.' Captain Tarief hands Soandso a pair of masterfully tailored hunting boots.


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/30870" data-url="30870" class="tooltip-link link">Hunting Leather Boots</a> (+2500 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30862" data-url="30862" class="tooltip-link link">Saurek Darkclaw Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30862" data-url="30862" class="tooltip-link link">Saurek Darkclaw Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30862" data-url="30862" class="tooltip-link link">Saurek Darkclaw Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30862" data-url="30862" class="tooltip-link link">Saurek Darkclaw Scales</a>) then 


>**Captain Tarief says:** So the hunter returns victorious. Well done! You have earned yourself a hunting bracer to protect you from the claws of the hoppers. I am sure many of your companions will revel in the feast you are able to provide them with the meat you have collected.


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/30867" data-url="30867" class="tooltip-link link">Hunting Leather Bracer</a> (+2500 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30863" data-url="30863" class="tooltip-link link">Saurek Shredder Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30863" data-url="30863" class="tooltip-link link">Saurek Shredder Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30863" data-url="30863" class="tooltip-link link">Saurek Shredder Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/30863" data-url="30863" class="tooltip-link link">Saurek Shredder Scales</a>) then 


>*Captain Tarief blinks in astonishment. 'Perhaps the true shredder was you this time around Soandso' He chuckles, 'Well done, you have earned the reward.' Tarief hands Soandso a pair of masterfully tailored hunting sleeves. 'Be sure to have your battle wounds tended to. I am sure you have many scars to show from hunting those shredders.*


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/30866" data-url="30866" class="tooltip-link link">Hunting Leather Sleeves</a> (+2500 exp)

 

**This NPC *should* return incorrect items given.**






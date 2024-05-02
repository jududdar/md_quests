# Wu the Enlightened
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Wu the Enlightened says:** Greetings Warrior of mind and body. To prove your worth to me, you must complete a test. Which test do you wish to take? I will permit you to take the test of Tears, Fists, or Tranquility.

**You say:** `tears`



>**Wu the Enlightened says:** The test of tears involves knowing when to release, and when to provide a shoulder for another. Bring me a Spiroc Statuette, a Spiroc Talon, and a Silken Wrap. I will teach you the way.

**You say:** `fists`



>**Wu the Enlightened says:** A monk must know when to use his or her fists, and when to use ones mind. You must decide in this endevour, which you shall use. Return to me, once you have found them, a pair of Brass Knuckles, a White Spiroc Feather, an Ethereal Amethyst, and a Nebulous Sapphire.

**You say:** `tranquility`



>**Wu the Enlightened says:** Ah, the test of tranquility. Only the tranquil monk can achieve enlightenment. Are you such an individual? Time shall tell. Retrieve these items for me. Bring an aged nectar, a Writ of Quellious, and a Tear of Quellious. Then we shall assess your ability.
end

## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_853.png" alt="" /> <a
                                href="/item/20800" data-url="20800" class="tooltip-link link">Silken Wrap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/20954" data-url="20954" class="tooltip-link link">Spiroc Statuette</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1067.png" alt="" /> <a
                                href="/item/20799" data-url="20799" class="tooltip-link link">Spiroc Talon</a>) then 


>**Wu the Enlightened says:** You have moved closer to enlightenment.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_665.png" alt="" /> <a
                                href="/item/1283" data-url="1283" class="tooltip-link link">Ton Po's Shoulder Wraps</a> (+100000 exp)

 


**Wu the Enlightened despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_505.png" alt="" /> <a
                                href="/item/20803" data-url="20803" class="tooltip-link link">Brass Knuckles</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/20801" data-url="20801" class="tooltip-link link">Ethereal Amethyst</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/20802" data-url="20802" class="tooltip-link link">Nebulous Sapphire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1146.png" alt="" /> <a
                                href="/item/20960" data-url="20960" class="tooltip-link link">White Spiroc Feather</a>) then 


>**Wu the Enlightened says:** You have moved closer to enlightenment.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_971.png" alt="" /> <a
                                href="/item/27715" data-url="27715" class="tooltip-link link">Wu's Fist of Mastery</a> (+100000 exp)

 


**Wu the Enlightened despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/20967" data-url="20967" class="tooltip-link link">Aged Nectar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/20804" data-url="20804" class="tooltip-link link">Writ of Quellious</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/20805" data-url="20805" class="tooltip-link link">Tear of Quellious</a>) then 


>**Wu the Enlightened says:** You have moved closer to enlightenment.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_933.png" alt="" /> <a
                                href="/item/11698" data-url="11698" class="tooltip-link link">Golden Sash of Tranquility</a> (+100000 exp)

 


**Wu the Enlightened despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Wu the Enlightened despawns.**





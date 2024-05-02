# Tabben Bromal
## Dialog

**You say:** `hail`



e.self:Say("What is it? What do you wan. . . Oh bloody underfoot, do forgive me, traveler. I'm not used to all this bickering and flittering about 

**You say:** `ready to write down`



if(**You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/17278" data-url="17278" class="tooltip-link link">Small Parts Container</a> x 1



>**Tabben Bromal says:** Very well. You'll need to gather up a dense hammered casing for the outer shell; a crystalline carapace will act to protect the face of the device; and it requires a fiery power source to propel the rotor mechanism. The device is then attached around the neck, much like the one you are wearing. The only difference will be the strands of living chain that will keep it from slipping from around your neck. Place those four items and your talisman in that box and return it to me. We should be able to get this thing built for you without much fuss at all, should all things go well on yourof the task, of course.


else



>**Tabben Bromal says:** Ready for what?

end

## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/28278" data-url="28278" class="tooltip-link link">Strange Jeweler's Schematic</a>) then 


>*Tabben Bromal takes the document from you and looks at it for a moment. 'Well, this is a beautiful looking schematic. I wonder what they are trying to make with it? Where did you get this? No wait; don't tell me. I'd rather not know. I can make some of this writing out but just barely. What I can read leads me to believe that I'd be better off not knowing.'*


e.self:Emote("falls victim to his curiosity and grabs a small kit from the table behind him. 'Take this kit and look for the following parts,' he says as he scrunches his nose at the schematic again. 'We'll need a Tri-coated Metal Casing, one Size C spring, some Creeping silk strands 


>**Tabben Bromal says:** Seal those things up in the container that I just gave you and bring it straight back to me. I'll wait here for you and see if I can decipher anymore of this schematic.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/17277" data-url="17277" class="tooltip-link link">Small parts kit</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/28278" data-url="28278" class="tooltip-link link">Strange Jeweler's Schematic</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/28283" data-url="28283" class="tooltip-link link">Sealed Parts Box</a>) then 


>**Tabben Bromal says:** Oh, you've returned! Very good, Soandso! Saria and I have made some real progress on the document that you brought us. Watch this and you'll see what I mean!


>*Tabben Bromal quickly opens the small case and removes the parts. He takes a tiny spanner, several small bolts, and a long wire and quickly pieces together what appears to be a small clockwork talisman. He pulls a leather string through the top of it and offers it to you.*


>**Tabben Bromal says:** That should work for you, but from what we gathered, there's another layer of mechanics that works to shield and envelope the existing talisman. It's going to require more parts. So take this container and let me know when you're [ready] to write down the names of the next set of parts.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/17278" data-url="17278" class="tooltip-link link">Small Parts Container</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/28284" data-url="28284" class="tooltip-link link">Small Clockwork Talisman</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/28289" data-url="28289" class="tooltip-link link">Locked Parts Box</a>) then


>*Tabben Bromal nods at you and takes the parts box over to the table. He seems to have laid out the extra tools that he needs prior to your return. With only a few twists and clicks, the pieces of the talisman lock together and begin to glow. The gnome turns and hands you the talisman and the design schematic in an exaggeratedly sharp gesture.*


>**Tabben Bromal says:** Please take the schematic to Elder Clinka. I'm afraid that I don't have the courage to spend any more time working on this for you. I wish I had a more adventurous spirit, but I don't. I like it here because it's peaceful. I don't need anyone changing that for you. Take care and be cautious on your way to see her. There's no telling who or what may be after you! When you show her the schematic, you may want to mention that most of that writing wasn't on there when we got it.


>**Tabben Bromal says:** It's seems that words are beginning to write themselves onto that schematic of yours. Maybe she'll be able to understand them. I sure don't want to. Take care.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/28291" data-url="28291" class="tooltip-link link">The Talisman Schematic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/28290" data-url="28290" class="tooltip-link link">Powered Clockwork Talisman</a>) 

 

**This NPC *should* return incorrect items given.**

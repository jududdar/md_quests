# Konia Swiftfoot



[Konia Swiftfoot](/npc/12117) is a level 40 Human Warrior that spawns in [Western Plains of Karana](/zone/12).












## Dialog

**You say:** `hail`



e.self:Say(string.format("Hello there, %s.  I am hosting a relay running contest.  Would you like to participate?",e.other:GetName()));

**You say:** `like to participate`



>**Konia Swiftfoot says:** Great!  The prize will be this silly old music sheet.  Let me know when you are ready and I will pass you the torch and tell you where the next stop is.

**You say:** `ready`



>**Konia Swiftfoot says:** Here you go.  Run with this torch as fast as you can to the Misty Thicket and hand this torch off to Fajio Knejo.  He will tell you where to go from there.  Hurry!  You do not have much time!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_559.png" alt="" /> <a
                                href="/item/20532" data-url="20532" class="tooltip-link link">Torch of Misty</a>
end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_765.png" alt="" /> <a
                                href="/item/20379" data-url="20379" class="tooltip-link link">Proof of Speed</a>) then


>**Konia Swiftfoot says:** Excellent!  You are quite a runner.  Here is half of the sheet music.  I decided to keep the other half because it has this wonderful signature.  I think it might be quite valuable.  It is probably worth as much as an instrument the great Mahlin used.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_870.png" alt="" /> <a
                                href="/item/20376" data-url="20376" class="tooltip-link link">Maestro's Symphony Page 24 Top</a> (+1000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1152.png" alt="" /> <a
                                href="/item/20366" data-url="20366" class="tooltip-link link">Mahlins Mystical Bongos</a>) then


>**Konia Swiftfoot says:** Mahlin's bongos!  Here, take the other half of the sheet music.  I can't really make out what the signature was, anyway.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/20383" data-url="20383" class="tooltip-link link">Maestro's Symphony Page 24 Bottom</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**




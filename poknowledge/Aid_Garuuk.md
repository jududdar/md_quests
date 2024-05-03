# Aid Garuuk



## Dialog

**You say:** `hail`



>**Aid Garuuk says:** Hullo traveler, an' welcum ta New Tanaan. Have ya been sittin' in da library very long? Da pages contained whif'in dese walls hold many inturestin' bits uv knowledge. As aides ta da council, our job is ta help assist our represenuhtives wif da task uv cullectin' more an' more knowledge fer da library. Right now I'm busy researchin' artifacts uv power fer Srethix but I'm missin' sum books I need. An' worse den dat, all dis werk has made me late in deliverin' sum supplies ta Grobb. Do ya think you could [give me a hand] whif dat?

**You say:** `hand`



if(e.other:Race() == "Troll") then



>**Aid Garuuk says:** Dat wud be great! My cuzin has been lookin' fer sum new ingredients ta experuhment whif his alchemy. I wuz suppos'd ta bring him sum but I didn't have da time. If you could get a Swirling Banshee Essense, Arachnae Fangs, a Wrulon Claw, an' a Blood Raven Tailfeather, take dem ta my cuzin Bregna in Grobb. He'll be most happy ta see dem delivured.


else



>**Aid Garuuk says:** Umm, on secund thought, maybe you shudn't help me after all. Da trolls where I come frum aren't as kind an' undurstandin' as I am.

end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/28740" data-url="28740" class="tooltip-link link">Troll Receipt</a>) then 


if(e.other:Race() == "Troll") then



>**Aid Garuuk says:** Great! I see you got da supplies ta Bregna after all. I wuz worried you might not make it too. Silly me fer tinkin' dat. Here, you can have dis as payment fer yer time. Oh hey, if you got sum more time, maybe you can help me again? Srethix is lookin' fer sum books, but I don't know where dey be at. You shud ask Srethix what books you can help him find. I put in a gud werd fer you, don't worry!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_535.png" alt="" /> <a
                                href="/item/2418" data-url="2418" class="tooltip-link link">Hoop of the Traveler</a> (+1000 exp)

 


else



>**Aid Garuuk says:** What's dis? A receipt frum a " .. e.other:Race() .. "? You cud not have gottun dis from Bregna, dis must be a forgury. I'll keep dis so you can't fool anywun else whif dis again.


**This NPC *should* return incorrect items given.**

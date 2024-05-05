# Gindlin Toxfodder



[Gindlin Toxfodder](/npc/12011) is a level 40 Human Shopkeeper that spawns in [Western Plains of Karana](/zone/12).





## Dialog

**You say:** `hail`



>**Gindlin Toxfodder says:** Enough with the formalities. I don't make it to these parts often and I only plan on being here a couple days. My time is precious. You must be a rogue in search of the [death juice].

**You say:** `death juice`



>**Gindlin Toxfodder says:** Spider venom. You can't mix it yourself. If you want, I can do it. I'll need two spider venom sacs from the giant spiders. There should be some around these plains. I also demand a fee of 20 gold pieces, oh yeah!... I have been banished from Qeynos... I also want a bottle of my favorite brew, Crow's special brew, purchased from Crow himself in North Qeynos.
end



## Turn-Ins



local text = "You did hear me, didn't you? I want two spider venom sacs, a bottle of Crow's special brew and 20 gold pieces.";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_819.png" alt="" /> <a
                                href="/item/14018" data-url="14018" class="tooltip-link link">A Spider Venom Sac</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_819.png" alt="" /> <a
                                href="/item/14018" data-url="14018" class="tooltip-link link">A Spider Venom Sac</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_702.png" alt="" /> <a
                                href="/item/13799" data-url="13799" class="tooltip-link link">Crows Special Brew</a>, gold = 20) then


>**Gindlin Toxfodder says:** Here. I could care less what you do with this. Hopefully you'll lay some on the Circle of Unseen Hands.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_806.png" alt="" /> <a
                                href="/item/14015" data-url="14015" class="tooltip-link link">Spider Venom</a> (+500 exp)

 

**This NPC *should* return incorrect items given.**

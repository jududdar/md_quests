# Winon Glahar



[Winon Glahar](/npc/202050) is a level 60 Human Warrior that spawns in [Plane of Knowledge](/zone/202).





## Dialog

**You say:** `Hail`



e.self:DoAnim(70);


if(**You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1357.png" alt="" /> <a
                                href="/item/28745" data-url="28745" class="tooltip-link link">Planar Traveler's Manual</a> x 1



>**Winon Glahar says:** Good day, Soandso. I see your curiosity of the planes is growing, as you have obtained a manual on planar travel. It is good to see young adventurers interested in planar exploration, but there is one aspect of discovery you must always be prepared for, the struggle for survival. There are very dangerous places to be seen and experienced out there, and it would behoove you to be ready to face what challenges may come. With my help, I can teach you the basics of planar stealth and reflexes if you are [willing to learn].


else



>**Winon Glahar says:** Good day, Soandso. I trust you are enjoying your visist to New Tanaan? If you have not already been, be sure to visit the Myrist library. There is much to be learned there; things you may have never thought possible before. I myself am a teacher of sorts, but I am only available to those who have obtained the proper tools of learning. Perhaps you will be a student of mine someday?


**You say:** `willing to learn`



e.self:DoAnim(48);


>**Winon Glahar says:** This is good. Through your trials of planar travel shall your knowledge of stealth techniques grow, and the more you learn, the more you shall produce. In order to prove your newfound knowledge, your first lesson will be to create a special [planar stein] of particular design. Once you have acquired this stein, you must give it to me along with your Planar Traveler's Manual. Once done, new lessons may be opened up to you.

**You say:** `planar stein`



e.self:DoAnim(64);


>**Winon Glahar says:** To fashion the stein I seek, you must acquire a Block of Tanaan Clay, a Ceramic Lining Sketch, Tainted Planar Essence, a Water Flask, and some Sculpting Tools. Use these items in a pottery wheel to create your base model to work from. Crush some Valor Crystals together with some Glaze Lacquer in a glaze mortar to make Crystalline Valor Glaze. You must then take a Lacquered Peridot, the Crystalline Valor Glaze, a High Quality Firing Sheet, and the base model stein and merge them in a kiln to put the finishing touches on your work. I hope to see you bring me a handsome-looking stein soon. Good luck!

**You say:** `willing to learn`



e.self:DoAnim(57);


>**Winon Glahar says:** I am glad to see you are willing to learn, however I'm afraid you are not ready for my teachings. Come back when you have acquired the proper tools of learning.
end



## Turn-Ins





if(**Your level** > 19 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_708.png" alt="" /> <a
                                href="/item/29168" data-url="29168" class="tooltip-link link">Planar Peridot Encrusted Stein</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1357.png" alt="" /> <a
                                href="/item/28745" data-url="28745" class="tooltip-link link">Planar Traveler's Manual</a>) then


>**Winon Glahar says:** Marvelous! You certainly have shown to be a skilled craftsman, and I thank you for such a lovely beverage conveyance. Take this book and use it to learn from. When you are ready, speak with Leramas Feston for your next lesson. Do not lose this manual or else he will not be able to train you.





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_789.png" alt="" /> <a
                                href="/item/28792" data-url="28792" class="tooltip-link link">Beginner Stealth Manual</a> (+500000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

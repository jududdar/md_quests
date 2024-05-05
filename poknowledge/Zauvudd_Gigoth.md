# Zauvudd Gigoth



[Zauvudd Gigoth](/npc/202045) is a level 60 Troll Warrior that spawns in [Plane of Knowledge](/zone/202).





## Dialog

**You say:** `hail`



e.self:DoAnim(70);


if(**You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1357.png" alt="" /> <a
                                href="/item/28745" data-url="28745" class="tooltip-link link">Planar Traveler's Manual</a> x 1



>**Zauvudd Gigoth says:** Hello, Soandso. I see you have obtained a manual on planar travel. It is good to see your determination has taken its first step to true glory. I think you may finally be ready to learn the basics of planar combat, that is if you are [willing to learn]. Remember, courage is imperial. It underlies true achievement. With your courage you shall achieve many great things.


else



>**Zauvudd Gigoth says:** Hello, Soandso. If you are looking for something in particular, I might be able to help you. I spent many years teaching combat techniques to the finest warriors in Grobb. I came to New Tanaan to further develop my teaching skills; it seems we all have our own lessons to learn. I can teach you a few things if you are looking to be taught. You will need to prepare yourself with the necessary equipment before I can begin though.


**You say:** `willing to learn`



e.self:DoAnim(57);


>**Zauvudd Gigoth says:** This is good. One of the most important aspects to your battle readiness is your strong willpower and bravery. Years ago I discovered a particular concoction that will very readily put your willpower to the test. Unfortunately I ran out not too long ago and I am in need of some more [Planar Blood Brew]. If you can make some more for my students, it would certainly look favorably upon you in your future teachings. Bring me some along with your Planar Traveler's Manual.

**You say:** `planar blood brew`



e.self:DoAnim(57);


>**Zauvudd Gigoth says:** To make the infamous Planar Blood Brew, you must attain some Nightmare Mephit Blood, Slarghilug Blood, Bubonian Blood, Soda Water, Grapes, a Cask, a Cork, and a Corking Device. Mix them in a Brew Barrel, and if you are skilled enough, the resulting swill should curl the hairs on even the hardiest of traveler's heads!

**You say:** `willing to learn`



e.self:DoAnim(48);


>**Zauvudd Gigoth says:** I am glad to see you are willing to learn, however I'm afraid you are not ready for my teachings. Come back when you have acquired the proper tools of learning.

**You say:** `planar blood brew`



e.self:DoAnim(64);


>**Zauvudd Gigoth says:** I am glad to see you are willing to learn, however I'm afraid you are not ready for my teachings. Come back when you have acquired the proper tools of learning.
end



## Turn-Ins



if(**Your level** > 19 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_706.png" alt="" /> <a
                                href="/item/28787" data-url="28787" class="tooltip-link link">Planar Blood Brew</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1357.png" alt="" /> <a
                                href="/item/28745" data-url="28745" class="tooltip-link link">Planar Traveler's Manual</a>) then 


>**Zauvudd Gigoth says:** Wow, this is great! Wow! This is may be the best Planar Blood Brew I have ever tasted! You have passed the first test with flying colors. Here, you take this book and learn well from it. When you are ready for your next lesson, speak to Xasri Virek.





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/28788" data-url="28788" class="tooltip-link link">Beginner Combat Manual</a> (+500000 exp)

**You receive coin:** 0-10 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

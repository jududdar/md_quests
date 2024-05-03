# Acomar Lothwol




## Dialog

**You say:** `Hail`



e.self:DoAnim(70);


if(**You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1357.png" alt="" /> <a
                                href="/item/28745" data-url="28745" class="tooltip-link link">Planar Traveler's Manual</a> x 1



>**Acomar Lothwol says:** It is good to see you. Soandso. As a teacher, my job is to share the knowledge of all things mystical with eager students. I sense you have obtained the basics of planar knowledge, you are now ready to begin your first lesson in the ways of magical ability. Are you [willing to learn] what life has to offer?


else



>**Acomar Lothwol says:** It is good to see you. Soandso.  I trust the people of New Tanaan have treated you well thus far.  It is refreshing to see so many people of different cultures coming together in harmony. don't you think?  So many shared experiences from all corners of the universe provide us with a great benefit of wisdom.  As a teacher, my job is to share the knowledge of all things mystical with eager students.  If you are truly interested in knowledge, you should prepare yourself with the basics first. A solid foundation leads to a new heights of achievement.


**You say:** `willing to learn`



e.self:DoAnim(57);


>**Acomar Lothwol says:** The use of magic can be a taxing ordeal on the body, and quite often may leave you in a weakened state. Fortunately, I happen to know of a rather rejuvenating meal that will grant new power to your condition. If you are not familiar with the recipe for [Hobgoblin Surprise], I can tell you. What you must do is bring me some as well as your Planar Traveler's Manual. I hope you won't be long, for I am beginning to get quite hungry.

**You say:** `hobgoblin surprise`



e.self:DoAnim(57);


>**Acomar Lothwol says:** Don't be put off by the name, it's actually quite tasty. To make Hobgoblin Surprise, get a pie tin, some bread, add some hobgoblin meat and brown gravy. Cook it in the oven and enjoy the results. Mmm mmm, it waters my mouth just thinking about it.

**You say:** `willing to learn`



e.self:DoAnim(48);


>**Acomar Lothwol says:** I am glad to see you are willing to learn, however I'm afraid you are not ready for my teachings. Come back when you have acquired the proper tools of learning.

**You say:** `hobgoblin surprise`



e.self:DoAnim(64);


>**Acomar Lothwol says:** I am glad to see you are willing to learn, however I'm afraid you are not ready for my teachings. Come back when you have acquired the proper tools of learning.
end



## Turn-Ins



if(**Your level** > 19 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_797.png" alt="" /> <a
                                href="/item/29751" data-url="29751" class="tooltip-link link">Hobgoblin Surprise</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1357.png" alt="" /> <a
                                href="/item/28745" data-url="28745" class="tooltip-link link">Planar Traveler's Manual</a>) then


>**Acomar Lothwol says:** How delicious! You have done well here, I can't remember how long it's been since I've tasted a meal so fine. Take this book, it will certainly help you in your use of the magical arts. When you are ready, Cadelid Etord will give you your next lesson, so be sure to speak to him. Do not lose your book or else he may not appreciate you coming to class unprepared.





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/28795" data-url="28795" class="tooltip-link link">Beginner Magic Manual</a> (+500000 exp)

**You receive coin:** 0-5 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

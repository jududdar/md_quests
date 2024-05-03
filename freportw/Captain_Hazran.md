# Captain Hazran


## Dialog

**You say:** `hail`



>**Captain Hazran says:** Hail, citizen! Welcome to the Freeport Militia House. It is time for you to serve the state. You will assist us in our war with [Clan Deathfist] before you are truly accepted into our city. We urge you to be all we command you to be.

**You say:** `clan deathfist`



>**Captain Hazran says:** Clan Deathfist are the orcs of the Commonlands. They are a nuisance and Sir Lucan has ordered their extermination. You will go forth into the Commonlands and kill these orcs. Clan Deathfist members are known to wear a clan belt. Bring a belt to me as proof of each death and you shall receive your wages and prove your allegiance to Freeport and all that is good.
end



## Turn-Ins




local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/13916" data-url="13916" class="tooltip-link link">Deathfist Slashed Belt</a>}, 1

if(count > 0) then


repeat



>**Captain Hazran says:** Good work, warrior. You are good militia material. Beware though, there are some who dare to call us foe. You have performed so well!



Your faction standing with [The Freeport Militia](/faction/330) got better (<span class='text-success'>+5</span>)



Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got better (<span class='text-success'>+1</span>)



Your faction standing with [Knights of Truth](/faction/281) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Priests of Marr](/faction/362) got worse (<span class='text-danger'>-1</span>)



 &#127873; **You receive:** 0 (+9350 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
;


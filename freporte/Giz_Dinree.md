# Giz Dinree


## Dialog

**You say:** `hail`



>**Giz Dinree says:** Excuse me! I came here in hopes of being alone!

**You say:** `sent by tani`



if( **Faction is** >= Amiable) then



>**Giz Dinree says:** You're a new rogue, then! Your mission is to kill the young daughter of the owner of the Seafarer's Roost. Wait for the right time. Why? You don't need to know. Do it and return Lyda's head to Tani in Neriak. I hope you can make it back to Neriak alive. Good hunting!


elseif( **Faction is** == Indifferent) then



>**Giz Dinree says:** You have done nothing to upset the Ebon Mask, but there is much more which you must do before we do business.  Perhaps a task from Master Hekzin shall set things right.


else



>**Giz Dinree says:** You are quite bold to approach a member of the Ebon Mask. Now be smart and run away.

end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18844" data-url="18844" class="tooltip-link link">A Sealed Letter</a>) then 


>**Giz Dinree says:** I am glad to see you. We have a problem. The last runner and I attempted to carry the chest from a boat. It fell overboard! He went in after it, but the sharks made a meal of him. If you want to try and get it, it is down below in the water in the harbor. Be careful.

**This NPC *should* return incorrect items given.**

end
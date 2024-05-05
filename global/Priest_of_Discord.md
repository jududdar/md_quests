# Priest of Discord







## Dialog

local is_special_flag_response = false;

**You say:** `Hail`



>**Priest of Discord says:** Greetings, Soandso .  Are you a child of Order?  If you have come seeking the path of Discord. I require only that you give me your [Tome of Order and Discord] and I shall show you the way.  Only then will you be freed from Order's confining restraints. If you are drawn to the allure of the uncharted, inquire about the secret [challenges] and their hidden [rites]. These are not mere adventures, but tests of your true mettle.

**You say:** `tome`



>**Priest of Discord says:** The Tome of Order and Discord was penned by the seventh member of the Tribunal and has become the key to a life of Discord, in spite of the author's pitiful warnings.  Do you not have one, child of Order?  Would you [like to read] it?

**You say:** `read`



>**Priest of Discord says:** Very well. Here you go. Simply return it to me to be released from the chains of Order.


e.other:SetPVP(false);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/18700" data-url="18700" class="tooltip-link link">Tome of Order and Discord</a>

**You say:** `rites`



if(e.other:IsSelfFound() == 1 or e.other:IsSoloOnly() == 1) then



>**Priest of Discord says:** The path to greatness is paved with the rarest of elements. Find those who deal in silver and gold. Secure a piece of such wealth and seek guidance on how to imbue it with arcane energy.


else



>**Priest of Discord says:** Ah, you tread the common path, where certain secrets remain veiled.


if(**Your level** == 1 and e.other:IsSelfFound() == 0 and e.other:IsSoloOnly() == 0 and e.other:IsHardcore() == 0) then


**You say:** `challenges`








>**Priest of Discord says:** I can offer you flags for the [solo], [self found], and [hardcore] challenges. You must tell me all of the challenges you wish to embark on in the same sentence. In the [solo] challenge, all external interactions become unavailable - as well as external buffs. In the [self found] challenge you are prevented from interacting with anyone else except others with the same flags of similar level, though you are additionally prevented from trading. There is also the [hardcore] challenge, which will result in your mortal coil being emptied - permanently - on death. You may include all three of these challenges together.



**Message:** <span class="text-warning">*By accepting any of these options, you will immediately be completely reset and sent back to your starting location. This will be irreversible.*</span>





**You say:** `solo`




>**Priest of Discord says:** Very well. You will now play solo, without any friends.



e.other:SetSoloOnly(1);



is_special_flag_response = true;



**You say:** `self found`




>**Priest of Discord says:** Very well. You will now play through the game using the self found ruleset.



e.other:SetSelfFound(1);



is_special_flag_response = true;



**You say:** `hardcore`




>**Priest of Discord says:** Very well. You will now have your character permanently unavailable upon your next death, along with all of their items.



e.other:SetHardcore(1);



is_special_flag_response = true;






**You say:** `i want to suffer`




>**Priest of Discord says:** Very well, then. Welcome to true Discord.



e.other:SetSelfFound(1);



e.other:SetHardcore(1);



e.other:SetBaseClass(0);



is_special_flag_response = true;






if(is_special_flag_response) then



e.other:ClearPlayerInfoAndGrantStartingItems();


else


**You say:** `challenges`



>**Priest of Discord says:** I can't offer you anything as you are above the first season, or have already chosen your challenges. Begone, mortal.


**You say:** `solo`




>**Priest of Discord says:** I can't offer you anything as you are above the first season, or have already chosen your challenges. Begone, mortal.


**You say:** `self found`




>**Priest of Discord says:** I can't offer you anything as you are above the first season, or have already chosen your challenges. Begone, mortal.


**You say:** `hardcore`




>**Priest of Discord says:** I can't offer you anything as you are above the first season, or have already chosen your challenges. Begone, mortal.

end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/18700" data-url="18700" class="tooltip-link link">Tome of Order and Discord</a>) then


>**Priest of Discord says:** I see you wish to join us in Discord! Welcome! By turning your back on the protection of Order you are now open to many more opportunities for glory and power. Remember that you can now be harmed by those who have also heard the call of Discord.


e.other:SetPVP(true);


e.other:Ding();
end







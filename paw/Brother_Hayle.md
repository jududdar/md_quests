# Brother Hayle



[Brother Hayle](/npc/18071) is a level 24 Human Cleric that spawns in [Lair of the Splitpaw](/zone/18).



## Dialog

**You say:** `hail`



>**Brother Hayle says:** This is no place for you. These Splitpaws are very fierce. Only the power of Rodcet Nife will guide them to the light. By the way, I might warn you that the cells here lock behind you.

**You say:** `free`



>**Brother Hayle says:** I am in no need of rescue.  I shall become a beacon of light to lead these beasts to the goodness of Rodcet Nife.

**You say:** `rodcet`



>**Brother Hayle says:** Rodcet Nife is the Prime Healer. The god unto whom all creatures pray at some time in their lives. He will show these gnolls the true inner light. I have converted a few of these creatures, but I fear they have all been executed. My turn will come soon, but I believe that in my martyrdom they shall see the true glory of Rodcet Nife and a new life will heal their evil souls.

**You say:** `here`



>**Brother Hayle says:** I was in the process of converting some of these beasts into disciples of Rodcet Nife when their shamans found out and captured me. That was weeks ago, I believe. Now, here, we shall all die.

**You say:** `proof of nobility`



if **Faction** >= Warmly then



>**Brother Hayle says:** I require the returned note I gave you, a Testimony of Truth, a Sword of Faith and finally the hilt of Soulfire. The Testimony and Sword of Faith are earned in the Hall of Truth, but for the hilt of Soulfire you shall have to battle [Xicotl].


elseif **Faction** >= Indifferent then



>**Brother Hayle says:** The Temple of Life smiles upon you, friend...  but such a delicate matter can only be entrusted to our most loyal members.



else



>**Brother Hayle says:** Your mere presence disgusts me.  Please remove yourself from my sight.  Until you change yourself and your ways, you are unwelcome in the Temple of Life.




**You say:** `xicotl`



if **Faction** >= Indifferent then



>**Brother Hayle says:** Xicotl is the evil troll who attempted to steal Soulfire from the vaults of the Temple of Life. The hilt of Soulfire broke off during the battle and now rests in the hands of this troll shadowknight. From what I have heard, he is frequently an invited guest at the castle called Mistmoore. Woe to any paladin who dares set foot upon the land of Mistmoore, but should you attempt it you might search the guest rooms for the troll. May Rodcet Nife walk with you.


else



>**Brother Hayle says:** Your mere presence disgusts me.  Please remove yourself from my sight.  Until you change yourself and your ways, you are unwelcome in the Temple of Life.


end



## Turn-Ins



local text = "I will not hand Soulfire to you until you hand me the Soulfire hilt, Testimony of Truth, Sword of Faith and the returned note. I require them as [proof of nobility].";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18927" data-url="18927" class="tooltip-link link">Temple Summons</a>) then 


>**Brother Hayle says:** I am needed!! What am I doing here? I must return to the Temple of Life to commune with the Prime Healer. Rodcet Nife will give me more strength to finish this job. Thank you, young one! Take this key as a reward. Turn it into Tyokan in the temple shop. Safe journey to you!





Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+20</span>)




Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+6</span>)




Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+10</span>)




Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-5</span>)




Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+3</span>)




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1081.png" alt="" /> <a
                                href="/item/13306" data-url="13306" class="tooltip-link link">T.O.L. 2020</a> (+1000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18936" data-url="18936" class="tooltip-link link">A Sealed Note</a>) then 


>**Brother Hayle says:** Finally!! I see that Ariska has found a noble knight to retrieve Soulfire. Per Ariska's orders I am not to give Soulfire to you until you can show me [proof of nobility]. You must honor both the Temple of Life as well as the Hall of Truth and to a high degree. Only then shall you hold Soulfire.


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+10</span>)




Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+3</span>)




Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+5</span>)




Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-2</span>)




Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+1</span>)




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_870.png" alt="" /> <a
                                href="/item/18937" data-url="18937" class="tooltip-link link">A Note</a> (+200 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_870.png" alt="" /> <a
                                href="/item/18937" data-url="18937" class="tooltip-link link">A Note</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/13947" data-url="13947" class="tooltip-link link">Brilliant Sword of Faith</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18828" data-url="18828" class="tooltip-link link">Testimony</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_973.png" alt="" /> <a
                                href="/item/12197" data-url="12197" class="tooltip-link link">Glowing Sword Hilt</a>) then 


if **Faction** >= Warmly then 



>**Brother Hayle says:** You have proven yourself worthy to hold Soulfire. Do not let her slip into the hands of evil. There are many who wish to free the many trapped souls of shadowknights and necromancers trapped inside the blade. The power of the blade can be called upon to heal you if need be. May Rodcet Nife and the twins of Marr hold you in their glory.



Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+100</span>)





Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+30</span>)





Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+50</span>)





Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-25</span>)





Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+15</span>)





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5504" data-url="5504" class="tooltip-link link">SoulFire</a> (+10000 exp)

 



else



>**Brother Hayle says:** Your mere presence disgusts me.  Please remove yourself from my sight.  Until you change yourself and your ways, you are unwelcome in the Temple of Life.







e.self:DeleteQuestLoot();


**This NPC *should* return incorrect items given.**



# Brother Hayle
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


if **You turn in:** [Temple Summons](/item/18927)


>**Brother Hayle says:** I am needed!! What am I doing here? I must return to the Temple of Life to commune with the Prime Healer. Rodcet Nife will give me more strength to finish this job. Thank you, young one! Take this key as a reward. Turn it into Tyokan in the temple shop. Safe journey to you!





* __Faction:__ [Priests of Life](/faction/341) (20)




* __Faction:__ [Knights of Thunder](/faction/280) (6)




* __Faction:__ [Guards of Qeynos](/faction/262) (10)




* __Faction:__ [Bloodsabers](/faction/221) (-5)




* __Faction:__ [Antonius Bayle](/faction/219) (3)




 **You receive:** None 

elseif **You turn in:** [A Sealed Note](/item/18936)


>**Brother Hayle says:** Finally!! I see that Ariska has found a noble knight to retrieve Soulfire. Per Ariska's orders I am not to give Soulfire to you until you can show me [proof of nobility]. You must honor both the Temple of Life as well as the Hall of Truth and to a high degree. Only then shall you hold Soulfire.


* __Faction:__ [Priests of Life](/faction/341) (10)




* __Faction:__ [Knights of Thunder](/faction/280) (3)




* __Faction:__ [Guards of Qeynos](/faction/262) (5)




* __Faction:__ [Bloodsabers](/faction/221) (-2)




* __Faction:__ [Antonius Bayle](/faction/219) (1)




 **You receive:**  [A Note](/item/18937) (+200 exp)

elseif **You turn in:** [A Note](/item/18937), [Brilliant Sword of Faith](/item/13947), [Testimony](/item/18828), [Glowing Sword Hilt](/item/12197)


if **Faction** >= Warmly then 



>**Brother Hayle says:** You have proven yourself worthy to hold Soulfire. Do not let her slip into the hands of evil. There are many who wish to free the many trapped souls of shadowknights and necromancers trapped inside the blade. The power of the blade can be called upon to heal you if need be. May Rodcet Nife and the twins of Marr hold you in their glory.



* __Faction:__ [Priests of Life](/faction/341) (100)





* __Faction:__ [Knights of Thunder](/faction/280) (30)





* __Faction:__ [Guards of Qeynos](/faction/262) (50)





* __Faction:__ [Bloodsabers](/faction/221) (-25)





* __Faction:__ [Antonius Bayle](/faction/219) (15)





 **You receive:** None 



else



>**Brother Hayle says:** Your mere presence disgusts me.  Please remove yourself from my sight.  Until you change yourself and your ways, you are unwelcome in the Temple of Life.







e.self:DeleteQuestLoot();


**This NPC *should* return incorrect items given.**



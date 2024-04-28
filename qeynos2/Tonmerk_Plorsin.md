# Tonmerk Plorsin
## Dialog

**You say:** `hail`



>**Tonmerk Plorsin says:** Hello, child.  Welcome to the Temple of Life. Here, you may pay homage to the [Prime Healer], [Rodcet Nife].  If you are in need of [healing] or require me to [cure disease] or [cure poison], please inform me.  I am the resident healer of all Qeynos citizens.

**You say:** `cure disease`



>**Tonmerk Plorsin says:** Yes, we can do that.  First, you must fetch me some bandages and brew me some bog juice.  I.. err.. require the bog juice to.. to dampen the bandages.. Yes that's it!  To dampen the bandages.

**You say:** `cure poison`



>**Tonmerk Plorsin says:** To cast the poison from your body I require one snake fang.  The fang will contain a hint of poison which will help me focus my casting.

**You say:** `healing`



>**Tonmerk Plorsin says:** You must pay a tribute of five gold coins before I perform the binding of your wounds.

**You say:** `prime healer`



>**Tonmerk Plorsin says:** He is the sustaining force of all life.  It is in honor of Him that the Temple of Life was built.  Engineered with the help of the [Academy of Arcane Science].

**You say:** `academy of arcane science`



>**Tonmerk Plorsin says:** The Academy of Arcane Science is the greatest school of magic in Antonica.  It houses a wealth of resources and knowledge pertaining to any of the circles of magic.  It is also a marvel of magical engineering.  If you should ever visit Freeport. be sure to let me know.  I seek a faithful cleric to [pickup a reagent].

**You say:** `pickup.* reagent`



if( **Faction is** < Indifferent) then 



>**Tonmerk Plorsin says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.


elseif( **Faction is** < Amiable) then 



>**Tonmerk Plorsin says:** The Temple of Life smiles upon you, friend... but such a delicate matter can only be entrusted to our most loyal members.


else 



>**Tonmerk Plorsin says:** That would be grand! It is a long journey to Freeport. I am lucky to find one who can endure the trip. Go to Freeport and seek out the Temple of Marr. Within, you shall find a cleric named [Serna Tasknon]. Give her this flask. It is an inert potion which she can use. In exchange she will give you the [shark powder] to return to me. Do this and I shall grant you the ability to call upon the power of life and smite thy foes.



**You receive:**  [Inert Potion](/item/13983)


**You say:** `Serna Tasknon`




>**Tonmerk Plorsin says:** Serna Tasknon is a member of the Priests of Marr in the trade city of Freeport. I studied their ways of healing. The Priests of Marr can be found in the Temple of Marr.

**You say:** `shark powder`




>**Tonmerk Plorsin says:** I am not sure what it is, but it surely has been proven to aid one's strength. Serna Tasknon in Freeport is the only one who can create it. She won't make it for you unless you bring her a potion from Toresian however. Last I saw of him he had returned to his home in Erudin.

**You say:** `bertoxxulous`



>**Tonmerk Plorsin says:** Bertoxxulous is the vile lord of all disease. We of the Temple of Life are sworn to put anto any being who serves the evil god.
end

## Turn-Ins




if **You turn in:** [Shark Powder](/item/12125)


>**Tonmerk Plorsin says:** I thank you, my good friend. Surely the road to Freeport was not easily trod. Please take this as compensation for your costs and I also grant you the ability to call forth the power of Rodcet Nife to smite the enemy. Go forth to defend life.





* __Faction:__ [Priests of Life](/faction/341) (20)


* __Faction:__ [Knights of Thunder](/faction/280) (6)


* __Faction:__ [Guards of Qeynos](/faction/262) (10)


* __Faction:__ [Bloodsabers](/faction/221) (-5)


* __Faction:__ [Antonius Bayle](/faction/219) (3)


 **You receive:** None 

elseif **You turn in:** [Bog Juice](/item/16581), [Bandages](/item/13009)


>**Tonmerk Plorsin says:** The glory of Rodcet Nife flows through your soul. May your body and soul live in righteous health.


**Tonmerk Plorsin casts:** [Counteract Disease](/spell/96) on target.

elseif **You turn in:** [Snake Fang](/item/13067)


>**Tonmerk Plorsin says:** The glory of Rodcet Nife flows through your soul. May your body and soul live in righteous health.


**Tonmerk Plorsin casts:** [Counteract Poison](/spell/95) on target.

elseif **You turn in:** gold = 5


>**Tonmerk Plorsin says:** The glory of Rodcet Nife flows through your soul. May your body and soul live in righteous health.


**Tonmerk Plorsin casts:** [Light Healing](/spell/17) on target.

**This NPC *should* return incorrect items given.**

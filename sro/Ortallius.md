# Ortallius










## Dialog

**You say:** `hail`



>**Ortallius says:** Welcome to the lands of Ro. Stand and fight with me. We shall fight to reclaim the desert in the name of Solusek Ro. Death to all [dervish cutthroats]!!

**You say:** `dervish cutthroats`



>**Ortallius says:** The dervish cutthroats are the vile scum who inhabit the desert. They are rogues who assault wayward travelers. Solusek Ro has commanded their extermination!! Do you wish to [join the crusade]?

**You say:** `join the crusade`



>*Ortallius grins enthusiastically. 'The scum rarely wander far from their camps. Hunt them down and I will reward you for every three insignia rings you bring as proof of their deaths.*

**You say:** `solusek`



>**Ortallius says:** Solusek Ro is the Burning Prince.  He watches over this land which He created.  He will soon come to burn the evil from the desert.  He has chosen Ortallius to begin His crusade.  He has bestowed upon me the power of righteousness,  I am His paladin!  All shall fall before His greatness!

**You say:** `rathmana`



>**Ortallius says:** Rathmana is a great wizard.  He is also my best friend.  [Solusek] sent him to save me from the savage desert when I was but a child in my dying mother's arms.  He saved me from being captured by the [dervish cutthroats].
end

## Turn-Ins



local text = "I was instructed to wait for two gems.";



if( **You turn in:** [Gem of Stamina](/item/12348), [A Sparkling Sapphire](/item/12349)) then 


>**Ortallius says:** You serve the Burning Prince as I do. The Redeemed has instructed me to give you this reward upon completion of your test. Practice your arts and prepare yourself. Evil approaches our realm. Long live Ro!!


* __Faction:__ [Temple of Solusek Ro](/faction/415) (25)



* __Faction:__ [Shadowed Men](/faction/416) (-1)



 **You receive:**  [Burning Rapier](/item/7041) 


elseif( **You turn in:** [Cutthroat Insignia Ring](/item/1903), [Cutthroat Insignia Ring](/item/1903), [Cutthroat Insignia Ring](/item/1903)) then


>**Ortallius says:** You will make a fine addition to the crusade. Continue the cleansing of the desert. Let it be known that the Defenders of Ro are here to challenge the evils of the desert. I call upon the righteousness of all paladins to assist me.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (5)




* __Faction:__ [Shadowed Men](/faction/416) (-1)




 **You receive:** eq.ChooseRandom( [Rusty Short Sword](/item/5013), [Rusty Axe](/item/5014), [Rusty Scythe](/item/5015), [Rusty Broad Sword](/item/5016), [Rusty Long Sword](/item/5019), [Rusty Battle Axe](/item/5020), [Rusty Battle Axe](/item/5020), [Rusty Scimitar](/item/5021), [Rusty Bastard Sword](/item/5022), [Rusty Two Handed Sword](/item/5023), [Rusty Halberd](/item/5024), [Rusty Two Handed Battle Axe](/item/5025), [Rusty Short Sword](/item/5013), [Rusty Axe](/item/5014), [Rusty Scythe](/item/5015), [Rusty Broad Sword](/item/5016), [Rusty Long Sword](/item/5019), [Rusty Battle Axe](/item/5020), [Rusty Battle Axe](/item/5020), [Rusty Scimitar](/item/5021), [Rusty Bastard Sword](/item/5022), [Rusty Two Handed Sword](/item/5023), [Rusty Halberd](/item/5024), [Rusty Two Handed Battle Axe](/item/5025), [Rusty Short Sword](/item/5013), [Rusty Axe](/item/5014), [Rusty Scythe](/item/5015), [Rusty Broad Sword](/item/5016), [Rusty Long Sword](/item/5019), [Rusty Battle Axe](/item/5020), [Rusty Battle Axe](/item/5020), [Rusty Scimitar](/item/5021), [Rusty Bastard Sword](/item/5022), [Rusty Two Handed Sword](/item/5023), [Rusty Halberd](/item/5024), [Rusty Two Handed Battle Axe](/item/5025), [Bronze Brazier](/item/4778), [Bronze Battle Axe](/item/5028), [Bronze Axe](/item/5032), [Bronze Dagger](/item/7012), [Bronze Halberd](/item/5031), [Bronze Long Sword](/item/5027), [Splintering Club](/item/6017), [Bronze Mace](/item/6019), [Bronze Main Gauche](/item/7015), [Bronze Rapier](/item/7013), [Bronze Flail](/item/6023), [Bronze Scimitar](/item/5034), [Bronze Scythe](/item/5035)) (+7500 exp)

**This NPC *should* return incorrect items given.**

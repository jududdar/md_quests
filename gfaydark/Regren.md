# Regren
## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Regren says:** Welcome, warrior! Show the Emerald Warriors your mettle and bring me a ruined wolf pelt, some bat fur, some bone chips, and a spiderling eye from the depths of Greater Faydark. If you succeed, my admiration and a reward will be yours. To battle!


elseif( **Faction is** == Indifferent) then



>**Regren says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Regren says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



local text = "Impressive, do you have the rest?";



if( **You turn in:** [Recruitment Letter](/item/18782)) then 


>**Regren says:** Welcome to the Emerald Warriors. Hmmm, you have a lot of training to do, so let's get started right away. Here's our guild tunic, represent us well, young Soandso.


* __Faction:__ [Emerald Warriors](/faction/326) (100)


* __Faction:__ [Indigo Brotherhood](/faction/270) (-15)


* __Faction:__ [Merchants of Felwithe](/faction/325) (10)


* __Faction:__ [Kelethin Merchants](/faction/276) (10)


 **You receive:**  [Old Green Tunic*](/item/13533) (+20 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Bone Chips](/item/13073), [Ruined Wolf Pelt](/item/13782), [Spiderling Eye](/item/13253), [Bat Fur](/item/13069)) then


>**Regren says:** Fine work! You are on your way to becoming an adequate combatant.


* __Faction:__ [Emerald Warriors](/faction/326) (10)


* __Faction:__ [Indigo Brotherhood](/faction/270) (-1)


* __Faction:__ [Kelethin Merchants](/faction/276) (1)


* __Faction:__ [Merchants of Felwithe](/faction/325) (1)


 **You receive:** eq.ChooseRandom( [Rusty Short Sword](/item/5013), [Rusty Axe](/item/5014), [Rusty Scythe](/item/5015), [Rusty Broad Sword](/item/5016), [Rusty Long Sword](/item/5019), [Rusty Battle Axe](/item/5020), [Rusty Scimitar](/item/5021), [Rusty Bastard Sword](/item/5022), [Rusty Two Handed Sword](/item/5023), [Rusty Halberd](/item/5024), [Rusty Two Handed Battle Axe](/item/5025), [Tarnished Short Sword](/item/5042), [Tarnished Axe](/item/5043), [Tarnished Broad Sword](/item/5044), [Tarnished Long Sword](/item/5045), [Tarnished Battle Axe](/item/5046), [Tarnished Scimitar](/item/5047), [Tarnished Bastard Sword](/item/5048), [Tarnished Scythe](/item/5049), [Tarnished Two Handed Sword](/item/5070), [Tarnished Two Handed Battle Axe](/item/5071), [Rusty Mace](/item/6011), [Rusty Two Handed Hammer](/item/6013), [Rusty Warhammer](/item/6014), [Rusty Flail](/item/6015), [Rusty Morning Star](/item/6016), [Tarnished Mace](/item/6030), [Tarnished Warhammer](/item/6031), [Tarnished Flail](/item/6032), [Tarnished Morning Star](/item/6033), [Rusty Dagger](/item/7007), [Rusty Rapier](/item/7008), [Rusty Spear](/item/7009), [Rusty Shortened Spear](/item/7010), [Tarnished Dagger](/item/7021), [Tarnished Shortened Spear](/item/7022), [Tarnished Rapier](/item/7023), [Tarnished Spear](/item/7024)) (+1000 exp)

**This NPC *should* return incorrect items given.**



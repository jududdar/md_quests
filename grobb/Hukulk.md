# Hukulk

## Dialog

**You say:** `hail`



>**Hukulk says:** What you want!! You make fun of [helm of Hukulk]?!! Me smash you!! Maybe you come learn ways of Hate and Fear! You be dark power. You be Pain. You [want join Nightkeep]?

**You say:** `helm`



>**Hukulk says:** Oh!!  Yooz tink you great enough to wear helm of Hukulk?  Me have another just like it. Me make deal with yooz.  If yooz want helm den yooz help Hukulk get revenge.  Youz better be strong or yooz useless!!  So.. Yooz [make deal with Hukulk]?

**You say:** `deal`



if **Faction** >= Amiable then



>**Hukulk says:** Yooz smart!!  Yooz go and walks to dark elf city.  Yooz finds one whos make Lynuga breaks up with Hukulk!  Maybe first yooz find Lynuga.  Find who she visits in dark elf city!!  Den yooz go and top off him head!!  Bash Lynuga too, if she no give me back [happy love bracer]!!  Me want head of dat home wrecker an' me happy love bracers, den me give yooz helm of Hukulk.


elseif **Faction** >= Indifferent then



>**Hukulk says:** Me talk to you 'bout dat when you do more to help Nightkeep!  Kill all Greenbloods!  Kill all froggies!


else



>**Hukulk says:** <..Sniff, sniff, sniff..>  Me smell the blood of enemy in you.  You fool to talk to Nightkeep shadowknight!  Me bleed you if you no run!


**You say:** `bracer`



if **Faction** >= Amiable then






>**Hukulk says:** Happy love bracers are mines!!  Me make dem for Lynuga.  Dey all shiny and green like da forests me see in adventures when me young.  Dey make Hukulk all warm and happy.  Den me give to Lynuga and.. and <sob>.. and.. AND LYNUGA RIP OUT HUKULK HEART!!  Yooz makes Lynuga give back [happy love bracers]!!


elseif **Faction** >= Indifferent then



>**Hukulk says:** Me talk to you 'bout dat when you do more to help Nightkeep!  Kill all Greenbloods!  Kill all froggies!


else



>**Hukulk says:** <..Sniff, sniff, sniff..>  Me smell the blood of enemy in you.  You fool to talk to Nightkeep shadowknight!  Me bleed you if you no run!


**You say:** `join`



if **Faction** >= Amiable then






>**Hukulk says:** Good. Hate and Pain. Innoruuk teach power, I teach power. Me make you power. You do what me say. You no mess up, I no kill you. We no like dead creature we no own. Go, kill dem. Bring four bone chips. I make you power.


elseif **Faction** >= Indifferent then



>**Hukulk says:** Me talk to you 'bout dat when you do more to help Nightkeep!  Kill all Greenbloods!  Kill all froggies!


else



>**Hukulk says:** <..Sniff, sniff, sniff..>  Me smell the blood of enemy in you.  You fool to talk to Nightkeep shadowknight!  Me bleed you if you no run!


**You say:** `lynuga`



>**Hukulk says:** Oooh!  Lynuga!  Why yooz leave powerful Hukulk?  Now yooz just spen' time collectin' gems and tings in Innothule.
end

## Turn-Ins



local text = "No, No, No! I said to bring me the happy love bracers and the troll head of the homewrecker! You not done the right things! Messed up you are!";



if  **You turn in:** [A tattered note](/item/18792)


>**Hukulk says:** Haaah!! Bow to Hukulk!! Hukulk make you feared.. make you powered! Dark power flow through you! Hate and Fear in your blood! Go to Vergad. He give you first lesson in pain.


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (100)



* __Faction:__ [Green Blood Knights](/faction/261) (-15)



* __Faction:__ [Broken Skull Clan](/faction/222) (-25)



* __Faction:__ [Da Bashers](/faction/235) (5)



 **You receive:**  [Black and Green Tunic*](/item/13530) (+20 exp)


elseif  **Faction** >= Amiable and  **You turn in:** [Bone Chips](/item/13073), [Bone Chips](/item/13073), [Bone Chips](/item/13073), [Bone Chips](/item/13073)


>**Hukulk says:** You good. Take dis. Make much pain and hurt. Make tings bleeds. Kill, hurt all. Innoruuk and me say do, now go. You do much, come bak. Teach you how more hurt and pain make. Go.


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (5)



* __Faction:__ [Green Blood Knights](/faction/261) (-1)



* __Faction:__ [Broken Skull Clan](/faction/222) (-1)



* __Faction:__ [Da Bashers](/faction/235) (1)






 **You receive:**  [Rusty Two Handed Sword](/item/5023) (+1000 exp)

elseif  **Faction** >= Amiable and  **You turn in:** [Troll Head](/item/12201), [Happy Love Bracers](/item/12202)


>**Hukulk says:** Ha!! Ha!! Who have last laugh now!! You do good werk.  Now me give you extra helm of Hukulk. Now go away!!


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (40)



* __Faction:__ [Green Blood Knights](/faction/261) (-6)



* __Faction:__ [Broken Skull Clan](/faction/222) (-10)



* __Faction:__ [Da Bashers](/faction/235) (2)



 **You receive:** None 

**This NPC *should* return incorrect items given.**

# Bilf
local count = 0;



## On NPC Spawn

**Set a timer** named *roll* for 70 seconds


## Dialog

**You say:** `hail`



>**Bilf says:** Shove off, mate.  We're busy 'scoutin'.  Can't ya see?  Hehehe!


if(**spawned NPC:**  [Blik](/npc/110054)) then



eq.get_entity_list():GetMobByNpcTypeID( [Blik](/npc/110054)):Say("Har har!  Scoutin'.  Yah, thats what we be doin'!");



if(**spawned NPC:**  [Feld](/npc/110055)) then



eq.get_entity_list():GetMobByNpcTypeID( [Feld](/npc/110055)):Say("Har har!  Scoutin'.  Yah, thats what we be doin'!");

end



## Timer(s)

count = count + 1;

if(count == 1) then


>*Bilf rolls a pair of handcarved dice.  'Har har!  The bones be favorin' me today!'*

elseif(count == 2) then


>*Bilf rolls a pair of handcarved dice.  'Bah!  You loaded these dice!  I never roll this bad!'*


if(**spawned NPC:**  [Feld](/npc/110055)) then



eq.get_entity_list():GetMobByNpcTypeID( [Feld](/npc/110055)):Say("I ain't loaded nothin'.  Just roll and lose yer chips.  Har har!");


elseif(count == 3) then


>*Bilf gets a strange smile and throws down a couple of chips.  'Time ta ante up.  I'm feelin' lucky.'*

elseif(count == 4) then


count = 0;
end
# Niera Farbreeze
## On NPC Spawn

local xloc = e.self:GetX();

local yloc = e.self:GetY();

eq.set_proximity(xloc - 20, xloc + 20, yloc - 20, yloc + 20);
function event_enter(e)

**Set a timer** named *hum* for 0 seconds
## Timer(s)

if(e.timer == "hum") then


>*Niera Farbreeze hums softly, a little tune that tickles the back of your mind but you can't quite recall.*


**Stop timer** named *hum*
end

## Dialog

**You say:** `tune`



>**Niera Farbreeze says:** Ohh. Just a little song my mother taught me when I was young. It speaks of the earth, the sky, and the sparkling stars above, always there.

**You say:** `always there`



>**Niera Farbreeze says:** Aye, always there. Like this small bag I wear around my neck. The last gift of my dying mother. It holds a fine dust, a dust she collected during her short life, that she believed brought her luck. It's speckled, flecked as the night sky is with stars.

**You say:** `speckled flecked dust`



>**Niera Farbreeze says:** I've had this little bit of dust, all I have of my mother, for many years now. It's the only reminder I have of her. She said it was special, magical, a warmth to help me through the nights. Even if my life were in the balance, I would have a hard time giving it up.

**You say:** `giving it up`



>*Niera Farbreeze stares at you with a flame in her eye. 'Did you hear everything I just told you? There is no way I will let go of this pouch. You find me another reminder and maybe I'll let it go. Not until then. Good luck doing that. Last anyone saw my mother she was exploring the blasted wastes of the newly discovered lands.*
end

## Turn-Ins




if( **You turn in:** [Silver Chained Locket](/item/20476)) then


>**Niera Farbreeze says:** This, this is my mother's amulet. I cannot believe it. Please, take this powder you say you need. Perhaps it does have powers, I don't know, I don't care. Thank you, my eternal thanks for this.


 **You receive:**  [Platinum Speckled Powder](/item/20456) 

**This NPC *should* return incorrect items given.**
